The original PDF coud be dounload from Russian Ministry of Education website: http://gia.edu.ru/ru/graduates_classes/demonstration/

To parse all the years and all the study samples tou need to do this:

(in the directory with files of particular subject and particular year)

'''mutool poster -y 2 *techno.pdf out.pdf
pdf2txt.py out.pdf >out.txt'''

The year 2009, 2011, 2013 and 2015 has no "techno" closing tag, so you need to find where is the actual tasks are (seems to be last file by alphabet).
In addition year 2011 has only one PDF file, so for it the processing is simplier.

The year 2010 has problem with zip files: on Mac you cannot unzip it without The Unarchiver. https://itunes.apple.com/app/the-unarchiver/

mutool is part of poppler-utils, you can download them here: https://poppler.freedesktop.org/

pdf2txt.py is part of PDFMiner library, it could be installed as usual for python: '''pip install pdfminer'''
