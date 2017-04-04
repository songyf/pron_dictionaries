# Pronunciation Dictionaries for Multiple Languages

Pronunciation dictionaries can be used for several purposes. For example, one can convert text to a sequence of phonemes using them. Not surprisingly, you have free access to a great English pronunciation dictionary provided by [CMU](https://github.com/cmusphinx/cmudict), although the pronunciation symbols are Arpabets, not IPAs. Again not surprisingly, it's hard to get pronunciation dictionaries for other languages. One reason is that for several languages their scripts are phonetic more or less; the pronunciation of a word can be inferred by some rules. However, rules often fail to cover everything. Besides, not everybody is aware of them. Decent open-source pronunciation dictionaries are still necessary.

## Requirements
* lxml >= 3.3.3
* python >= 3.4
	
## References
* [CMU US English pronouncing dictionary](https://github.com/cmusphinx/cmudict)

## Work Flow
* STEP 1. Download the [wiktionary database backup dumps](http://ftp.acc.umu.se/mirror/wikimedia.org/dumps) of the language you want.
* STEP 2. Extract it to `data/raw/` folder.
* STEP 3. Run `make_dictionary.py`.

## Pre-built dictionaries
Click the name of the language to download the prebuilt dictionary.

* [German](https://dl.dropboxusercontent.com/u/42868014/pron_dicts/de.csv.tar.gz)
* [Italian](https://dl.dropboxusercontent.com/u/42868014/pron_dicts/it.csv.tar.gz)
* [Spanish](https://dl.dropboxusercontent.com/u/42868014/pron_dicts/es.csv.tar.gz)
* [French](https://dl.dropboxusercontent.com/u/42868014/pron_dicts/fr.csv.tar.gz)
* [Polish](https://dl.dropboxusercontent.com/u/42868014/pron_dicts/pl.csv.tar.gz)
* [Finnish](https://dl.dropboxusercontent.com/u/42868014/pron_dicts/fi.csv.tar.gz)
* [Korean](https://dl.dropboxusercontent.com/s/346v029h4fthgx4/ko.csv.tar.gz)
* [Turkish](https://dl.dropboxusercontent.com/s/7gzitspqhyw0405/tr.csv.tar.gz)
* [Portuguese](https://dl.dropboxusercontent.com/s/m837tkkclfxswp8/pt.csv.tar.gz)
* [Russian](https://dl.dropboxusercontent.com/s/4j433o46ipcq1cj/ru.csv.tar.gz)

## Note

We will keep adding languages. Any contributions / error reports are welcome. 

## Disclaimer

We are not responsible for the content (headwords and pronunciations). They may contain mistakes made by us or the original creator.



