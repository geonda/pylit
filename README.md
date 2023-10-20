# description
I have made some modifications to pdf-renamer to suit my personal needs. I have introduced a new format called {pylit}: LastNameYY.pdf. In addition to renaming the papers, the program now generates a bibtex.bib file that contains unique entries for the bibliographic information of the papers.

Installation:

`python setup.py install` 

Usage:

`for item in *.pdf; do; pdfrenamer -f {pylit} item; done`

More about [pdf-renamer](https://github.com/MicheleCotrufo/pdf-renamer) and [pdf2bib](https://github.com/MicheleCotrufo/pdf2bib/tree/master) libs. 
