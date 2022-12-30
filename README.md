RO en attente de la fin de migration













































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

# Imprimer en PDF une page Internet
Testé sous Firefox v94.0.2 avec succcès !
Installer une imprimante PDF telle cups-pdf. Pour conserver la page telle qu'elle est affichée avec toutes ses informations et sa présentation :
- toutes les pages (ou celles qu'on veut)
- en couleur (ou en noir pour alléger)
- A4 (sinon le PDF prendra plus d'espace de stockage)
- Ajuster à la largeur de la page (sinon on perdra les infos tronquées)
- 1 page par feuille
- Marges par défaut
- ne PAS imprimer les en-têtes et pieds de pages qui viennent chevaucher le texte et le rendre illisible à chaque pied et tête de page (si vraiment on veut indiquer des infos, le faire avec un outil spécialisé qui donnera une instance unique de l'info tels addon FF SingleFile avant export ou LibreOffice Draw ou Evince après export)
- imprimer les arrières plan (ou pas pour sûrement gagner en espace disque MAIS perdre en lisibilité)
