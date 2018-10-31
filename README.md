# Egyptian Wikipedia Extracts
Documents extracts from [Egyptian Wikipedia](arz.wikipedia.org) downloaded from [Egyptian Wikipedia dumps](https://dumps.wikimedia.org/arzwiki/)

## Instructions 
1. get the corpus dump 
```
wget https://dumps.wikimedia.org/arzwiki/latest/arzwiki-latest-pages-articles.xml.bz2 
```
2. get the tool
```
git clone https://github.com/attardi/wikiextractor.git
```
3. extract: 
```
python3 wikiextractor/WikiExtractor.py arzwiki-latest-pages-articles.xml.bz2 -o 20181020 --json 
```

## License
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
 
This corpus is extracted by [wikiextractor](https://github.com/attardi/wikiextractor)

## corpus extracts from 20-10-2018 

## corpus extracts from 20-01-2017 

### Corpus Information

| documents | words | vocabulary |
| --- | --- | --- |
| 16,203 | 2.18M | 293.5K |

## To cite this resource:

Motaz Saad and Basem Alijla (2017). _WikiDocsAligner: an off-the-shelf Wikipedia Documents Alignment Tool_. in The Second Palestinian International Conference on Information and Communication Technology (PICICT 2017). 
