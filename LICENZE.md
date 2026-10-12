# Crediti e licenze

Farō Reader poggia sul lavoro di altri: qui c'è l'elenco completo, con la licenza di ogni parte e il collegamento alla fonte.

Ultima verifica sulle fonti originali: 12 ottobre 2026.

## Voci

| Parte | Autore | Licenza | Fonte |
|---|---|---|---|
| Pocket TTS, modello `italian_24l` | Kyutai | CC BY 4.0 | <https://huggingface.co/kyutai/pocket-tts> |
| Pocket TTS, codice | Kyutai | MIT | <https://github.com/kyutai-labs/pocket-tts> |
| Voce **Giovanni** | registrazione dal corpus Mozilla Common Voice (italiano), voce predefinita di Pocket TTS | CC0 (Common Voice) | <https://commonvoice.mozilla.org> |
| Voce **Valentina** (nome originale: voce "paola" di Piper, modello `it_IT-paola-medium`) | progetto Piper; dati di Paola Persico | dati: CC0 | <https://huggingface.co/rhasspy/piper-voices> · <https://huggingface.co/datasets/paolapersico1/Voice-Dataset-Italian> |
| Piper, codice | Rhasspy | MIT | <https://github.com/rhasspy/piper> |

In Farō Reader la voce "paola" di Piper si chiama Valentina. Il modello è stato ottenuto dai suoi autori affinando la voce inglese "lessac" di Piper.

Kyutai chiede che i suoi modelli non siano usati per imitare o clonare una voce senza il consenso esplicito della persona. È anche la nostra regola: vedi la [guida alle voci](voci/GUIDA.md).

## Analisi del testo e pronuncia

| Parte | Autore | Licenza | Fonte |
|---|---|---|---|
| Dizionario degli accenti, pubblicato in [`dizionario/`](dizionario/) | costruito da noi a partire da WikiPron (dati di Wikizionario) e da un elenco di frequenza delle parole | CC BY-SA 4.0 | <https://github.com/CUNY-CL/wikipron> · <https://github.com/hermitdave/FrequencyWords> |

Numeri in lettere, pause e scelta della pronuncia secondo la frase sono regole scritte da noi.

## Motore e librerie dell'app

| Parte | Autore | Licenza | Fonte |
|---|---|---|---|
| ONNX Runtime | Microsoft | MIT | <https://github.com/microsoft/onnxruntime> |
| AndroidX (core, appcompat, webkit, lifecycle, activity) | Android Open Source Project | Apache 2.0 | <https://developer.android.com/jetpack/androidx> |
| Kotlin e kotlinx.coroutines | JetBrains | Apache 2.0 | <https://kotlinlang.org> |

## Caratteri

Tutti con SIL Open Font License 1.1, usati senza modifiche.

| Carattere | Autore | Fonte |
|---|---|---|
| Atkinson Hyperlegible | Braille Institute of America | <https://github.com/google/fonts/tree/main/ofl/atkinsonhyperlegible> |
| Lexend | The Lexend Project Authors | <https://github.com/googlefonts/lexend> |
| OpenDyslexic | Abbie Gonzalez | <https://github.com/antijingoist/opendyslexic> |
| Literata | The Literata Project Authors | <https://github.com/googlefonts/literata> |

## Libro di prova

*Le avventure di Pinocchio* di Carlo Collodi, illustrato da Enrico Mazzanti: testo di pubblico dominio.
Il testo è stato preso dall'edizione elettronica dell'associazione [Liber Liber](https://www.liberliber.it), tratta dalla seconda edizione Rizzoli (Milano, 1949). Impaginazione e copertina sono nostre.

## Strumenti usati solo durante lo sviluppo

Non sono dentro l'app: sono serviti a costruire e controllare il dizionario e le voci.
eSpeak NG (GPL 3.0), num2words (LGPL 2.1), UDPipe (codice MPL 2.0, modello italiano CC BY-NC-SA 4.0), Praat, Whisper.
