# Crediti e licenze

Farō Reader è gratuito e non ha scopo commerciale. Poggia sul lavoro di altri: qui c'è l'elenco completo, con la licenza di ogni parte e il collegamento alla fonte.

Ultima verifica sulle fonti originali: 12 ottobre 2026.

## Voci

| Parte | Autore | Licenza | Fonte |
|---|---|---|---|
| Pocket TTS, modello `italian_24l` | Kyutai | CC BY 4.0 | <https://huggingface.co/kyutai/pocket-tts> |
| Pocket TTS, codice | Kyutai | MIT | <https://github.com/kyutai-labs/pocket-tts> |
| Voce **Giovanni** | registrazione dal corpus Mozilla Common Voice (italiano), voce predefinita di Pocket TTS | CC0 (Common Voice) | <https://commonvoice.mozilla.org> |
| Voce **Paola**, modello `it_IT-paola-medium` | progetto Piper; dati di Paola Persico | dati: CC0 | <https://huggingface.co/rhasspy/piper-voices> · <https://huggingface.co/datasets/paolapersico1/Voice-Dataset-Italian> |
| Piper, codice | Rhasspy | MIT | <https://github.com/rhasspy/piper> |

Il modello di Paola è stato ottenuto dai suoi autori affinando la voce inglese "lessac" di Piper.

Kyutai chiede che i suoi modelli non siano usati per imitare o clonare una voce senza il consenso esplicito della persona. È anche la nostra regola: vedi la [guida alle voci](voci/GUIDA.md).

## Analisi del testo e pronuncia

| Parte | Autore | Licenza | Fonte |
|---|---|---|---|
| UDPipe 1, codice | Istituto di linguistica formale e applicata, Università Carolina di Praga | MPL 2.0 | <https://github.com/ufal/udpipe> |
| UDPipe, modello italiano ISDT | come sopra, da Universal Dependencies | CC BY-NC-SA 4.0 | <https://ufal.mff.cuni.cz/udpipe/1/models> |
| Dizionario degli accenti | costruito da noi a partire da WikiPron (dati di Wikizionario) e da un elenco di frequenza delle parole | dati di Wikizionario: CC BY-SA 4.0 | <https://github.com/CUNY-CL/wikipron> · <https://github.com/hermitdave/FrequencyWords> |

Il modello italiano di UDPipe è distribuito solo per uso non commerciale: Farō Reader lo usa così com'è, senza modifiche.

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
L'edizione elettronica è dell'associazione [Liber Liber](https://www.liberliber.it), che distribuisce impaginazione e copertina con licenza CC BY-NC-SA 4.0.

## Strumenti usati solo durante lo sviluppo

Non sono dentro l'app: sono serviti a costruire e controllare il dizionario e le voci.
eSpeak NG (GPL 3.0), num2words (LGPL 2.1), Praat, Whisper.
