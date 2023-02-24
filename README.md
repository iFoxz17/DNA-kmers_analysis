# DNA-kmers_analysis
Python jupyter-notebook to analyze k-mers in DNA reads.

## Progetto
Presi in input un file FASTQ di reads di lunghezza costante, una soglia di frequenza F (tra 0 e 1) e una lunghezza, produrre in output il report dell'uso dei *k-mers* per posizione nei reads in input. Un *k-mer* è una *sottostringa di read* di lunghezza k. Il report deve presentare per ciascun *k-mer* che ha una frequenza almeno pari a F (nel dataset di input) quante volte appare in ciascuna delle posizioni dei reads dalla prima a L - k + 1 (L: lunghezza dei reads). Selezionare il *k-mer* che appare più volte in una certa posizione e produrre in un file FASTA i reads che lo contengono (in quella posizione) con la loro qualità media.

## Input
* File <code>FASTQ</code> di una o più reads ( è un esempio);
* F: soglia di frequenza minima;
* k: lunghezza dei k-meri

## Parametri
* L : lunghezza dei reads (costante);
* N : numero dei reads

