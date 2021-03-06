# Anuvaad Corpus Tools

## Overview
This repository houses the crawler code for building the Anuvaad parallel corpus.
The ultimate goal is to build quality parallel datasets across various domains
(General, Judicial, Educational, Financial, Press, etc) & various Indian languages.

The current set of crawlers are built to scrape, tokenizer and align
multilingual reports/documents available at various sources.

1. Press Information Bureau ([http://pib.gov.in](http://pib.gov.in))
2. Press Information Bureau Archives ([http://pibarchive.nic.in](http://pibarchive.nic.in))
3. Wikipedia ([https://www.wikipedia.org](https://www.wikipedia.org))


## Processing Steps
The broader steps involved in all the tools can be generalized to the following :
##### 1. Scraping
Hit the required web page & download the contents in respective languages.

##### 2. Tokenizing
The process of spliting the scraped document into individual sentences using the Tokenizer.

##### 3. Sentence Aligning
The process of pairing the sentences across different languages which has the same meaning.

## Parallel Corpus
The parallel corpus of the above datasets are available under :
[anuvaad-parallel-corpus](https://github.com/project-anuvaad/anuvaad-parallel-corpus)
