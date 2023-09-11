# JavaScript Spellchecker

Simple Spellchecker in JavaScript.

![alt screenshot](https://raw.githubusercontent.com/lrusso/JavaScriptSpellchecker/main/JavaScriptSpellchecker.png)

## Web:

https://lrusso.github.io/JavaScriptSpellchecker/JavaScriptSpellchecker.htm

## How does it work?

The website extracts all the words from the document and send those words to a web worker. The web worker will download the required dictionary, starts the spellchecking process and returns a JSON with all the misspelled word (or unknown) with the suggestions. No backend required.

## Dictionaries:

https://www.phpspellcheck.com/Download
