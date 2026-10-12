# Farsi la propria voce

> Parte non ufficiale. Funziona, ma è sperimentale: non la garantiamo e non la seguiamo come le voci ufficiali.

Una voce per Farō Reader nasce da una registrazione di circa quindici secondi.
Non si addestra nulla: un programma sul computer "ascolta" la registrazione e produce un piccolo file che l'app sa importare.

## Prima di cominciare

**Usa solo voci di persone che sono d'accordo.** La tua, o quella di chi ti ha detto di sì.
Non clonare voci prese da audiolibri, video, trasmissioni o altri servizi.

## Cosa serve

- Un computer con Python.
- Una registrazione di circa quindici secondi. Più lunga non è meglio: oltre i trenta secondi la voce peggiora.
- Il pacchetto `pocket-tts` di Kyutai. La parte che crea le voci chiede di accettare i suoi termini d'uso.

## Passi

1. **Registra.** Stanza silenziosa, lettura tranquilla e continua, senza musica o rumori.
   Salva in formato WAV.
2. **Crea la voce.**

   ```bash
   python export_pocket_voice.py --language italian_24l --out voci nome=registrazione.wav
   ```

3. **Crea il pacchetto.**

   ```bash
   python pack_pocket_voice.py nome
   ```

   Ottieni `nome.zip`.
4. **Importa.** Copia `nome.zip` sul dispositivo. In Farō Reader tocca **Voce → Aggiungi voce…** e scegli il file.

Gli strumenti dei passi 2 e 3 saranno pubblicati in questa cartella.

## Se l'app rifiuta il pacchetto

Il messaggio "Questa voce non è fatta per il modello dell'app" significa che la voce è stata creata con un modello diverso.
Farō Reader usa il modello `italian_24l`.
