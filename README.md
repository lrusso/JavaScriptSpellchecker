# JavaScript Spellchecker

## Web:

https://lrusso.github.io/JavaScriptSpellchecker/JavaScriptSpellchecker.htm

## How does it work?

The website extract all the words from the document and send those words to a web worker. The worker will download the required dictionary, start the spellchecking process for each word and returning a JSON with all the misspelled word (or unknown) with the suggestions.
