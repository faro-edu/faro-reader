# Dizionario degli accenti

È il dizionario che Farō Reader usa per sapere dove cade l'accento di una parola e se la vocale accentata è aperta o chiusa.

## File

**`it_stress.tsv`**: circa 48.000 parole, una per riga, tre colonne separate da tabulazione.

| Colonna | Contenuto |
|---|---|
| 1 | la parola, in minuscolo |
| 2 | quale vocale porta l'accento, contando da zero |
| 3 | il timbro della vocale accentata: `e` o `o` chiusa, `ɛ` o `ɔ` aperta, `-` se la vocale non è una e o una o |

**`it_func.tsv`**: circa 140 parole funzionali (articoli, preposizioni, ausiliari) con il peso che hanno nella frase: `none` se si appoggiano alla parola vicina, `secondary` se hanno un accento debole.

## Da dove viene

L'abbiamo costruito noi a partire da:

- [WikiPron](https://github.com/CUNY-CL/wikipron), che raccoglie le pronunce di [Wikizionario](https://it.wiktionary.org);
- un elenco delle parole italiane più frequenti, da [FrequencyWords](https://github.com/hermitdave/FrequencyWords);
- controlli e correzioni nostre.

## Licenza

[Creative Commons Attribuzione - Condividi allo stesso modo 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.it) (CC BY-SA 4.0), la stessa dei dati di Wikizionario da cui deriva.
Puoi usarlo, modificarlo e ridistribuirlo citando Farō e Wikizionario e mantenendo la stessa licenza.

## Correzioni

Se trovi un accento sbagliato, [segnalalo](../../../issues/new?template=lettura.yml).
