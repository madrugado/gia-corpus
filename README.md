# gia-corpus
Corpus of exam tests for 9-graders in Russia for NLP/ML purposes

## About contents
The two folders with files: "raw" and "processed". If "processed", so this text is alredy cleaned from the all other text, than questions and answers. In "raw" folder there are text contents of PDFs without post-processing.

We're only using (mostly) first twenty multiple choice questions, since they have only one right answer.

*UPD:* Added tsv folder with files in format compatible to Kaggle Allen AI Challenge (https://www.kaggle.com/c/the-allen-ai-science-challenge/data)

## Format
Subject tag is: 
 * GE - geography
 * OB - social studies
 * IS - history


and year is in YYYY format.

For example, IS_2009.processed.txt

## License
Since the contents of this repo is scraped from PDFs from Russian Ministry of Education website and according to it the content of PDF is in public domain, so the license is *CC BY-NC*.
