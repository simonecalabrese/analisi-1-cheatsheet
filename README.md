## Genera PDF
### Requisiti
Avere [latexmk](https://mg.readthedocs.io/latexmk.html) installato.
### Compilazione
```sh
# spostati dentro la cartella
cd analisi-1-cheatsheet

# compila il file main.tex 
latexmk

# elimina tutti i file generati tranne il PDF
latexmk -c
```
