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
| AndroidX Media3 (riproduzione dell'audiolibro, dalla 0.4) | Android Open Source Project | Apache 2.0 | <https://developer.android.com/media/media3> |
| libopus 1.5.2 (audio salvato, dalla 0.4) | Xiph.Org Foundation e altri | BSD a 3 clausole, testo qui sotto | <https://opus-codec.org> |

## Caratteri

Tutti con SIL Open Font License 1.1, usati senza modifiche.

| Carattere | Autore | Fonte |
|---|---|---|
| Atkinson Hyperlegible | Braille Institute of America | <https://github.com/google/fonts/tree/main/ofl/atkinsonhyperlegible> |
| Lexend | The Lexend Project Authors | <https://github.com/googlefonts/lexend> |
| OpenDyslexic | Abbie Gonzalez | <https://github.com/antijingoist/opendyslexic> |
| Literata | The Literata Project Authors | <https://github.com/googlefonts/literata> |

## Libri della Biblioteca Farō

*Le avventure di Pinocchio* di Carlo Collodi, illustrato da Enrico Mazzanti: testo di pubblico dominio.
Il testo è stato preso dall'edizione elettronica dell'associazione [Liber Liber](https://www.liberliber.it), tratta dalla seconda edizione Rizzoli (Milano, 1949). Impaginazione e copertina sono nostre.

Lo stesso vale per tutti i libri della [Biblioteca Farō](https://faro-edu.github.io/faro-reader/biblioteca.html): opere di pubblico dominio, testo preso dalle edizioni elettroniche di Liber Liber, impaginazione e copertine nostre. L'ultima pagina di ogni libro indica l'edizione a stampa da cui è tratto.

## Strumenti usati solo durante lo sviluppo

Non sono dentro l'app: sono serviti a costruire e controllare il dizionario e le voci.
eSpeak NG (GPL 3.0), num2words (LGPL 2.1), UDPipe (codice MPL 2.0, modello italiano CC BY-NC-SA 4.0), Praat, Whisper.

## Testo della licenza di libopus

```
Copyright 2001-2023 Xiph.Org, Skype Limited, Octasic,
                    Jean-Marc Valin, Timothy B. Terriberry,
                    CSIRO, Gregory Maxwell, Mark Borgerding,
                    Erik de Castro Lopo, Mozilla, Amazon

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:

- Redistributions of source code must retain the above copyright
notice, this list of conditions and the following disclaimer.

- Redistributions in binary form must reproduce the above copyright
notice, this list of conditions and the following disclaimer in the
documentation and/or other materials provided with the distribution.

- Neither the name of Internet Society, IETF or IETF Trust, nor the
names of specific contributors, may be used to endorse or promote
products derived from this software without specific prior written
permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
``AS IS'' AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER
OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR
PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF
LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

Opus is subject to the royalty-free patent licenses which are
specified at:

Xiph.Org Foundation:
https://datatracker.ietf.org/ipr/1524/

Microsoft Corporation:
https://datatracker.ietf.org/ipr/1914/

Broadcom Corporation:
https://datatracker.ietf.org/ipr/1526/
```
