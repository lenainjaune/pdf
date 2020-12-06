# PDF
Tout ce qui touche à ce format


# Modifier PDF
PDFArranger (anciennement PDFShuffler) ; j'ai testé PDFS pour Ubuntu 16 car PDFA dispo pour Ubuntu 19+
=> PDFA permet facilement de faire les rotations des pages sélectionnées

# Extraire sans toucher à la qualité
https://unix.stackexchange.com/questions/11835/pdf-to-jpg-without-quality-loss-gscan2pdf
```sh
pdfimages -f 4 -l 4 -all 'file.pdf' ~/temp/
```
