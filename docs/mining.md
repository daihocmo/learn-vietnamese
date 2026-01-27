# Mining Guide

If you did everything right in the previous guide, you should be able to look up words in Vietnamese with Yomitan. This section will cover everything you need to know to setup a proper mining experience. Mining is usually something one does after going through a vocabulary deck like [Basic Vietnamese for English Speakers](https://ankiweb.net/shared/info/285983903).

## Set up Yomitan and Anki for mining

In this section, we discuss various Anki card notes, install one and setup Yomitan for mining.

### Choosing a note type

There are multiple note types available out there for mining (especially for Vietnamese learning). I suggest using the [Vietnamese](assets/vietnamese.apkg) note type, which is the _simplest_ note type for beginners.

![alt text](img/mining/anki-back-1.png)

### Setting things up

To set up Anki integration, go to "Settings" > "Anki". Make sure "Enable Anki integration" is on, Anki is running and AnkiConnect is installed.

Scroll down and click "Configure Anki card format..." to select the Note Type for your mining deck.

The settings below are for the **Vietnamese** Note Type. You can install it by importing [this example deck](assets/vietnamese.apkg).

#### Fields

| Field      | Value                                             |
| ---------- | ------------------------------------------------- |
| `Word`     | `{expression}`                                    |
| `Sentence` | `{cloze-prefix}<b>{cloze-body}</b>{cloze-suffix}` |
| `Meaning`  | `{glossary-first-brief}`                          |

![alt text](img/mining/template.png)

#### Preview

![alt text](img/mining/anki-front-1.png)

![alt text](img/mining/anki-back-1.png)

### Further reading

- [Donkuri's guide to mining](https://donkuri.github.io/learn-japanese/mining/)
