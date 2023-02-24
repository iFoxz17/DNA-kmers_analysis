# DNA-kmers_analysis
Python jupyter-notebook to analyze k-mers in DNA reads.

## Progetto
Presi in input un file <code>FASTQ</code> di **reads** di **lunghezza costante**, una **soglia di frequenza** <code>F</code> (tra 0 e 1) e una **lunghezza** <code>k</code>, produrre in output il report dell'uso dei **k-mers per posizione** nei reads in input. Un **k-mer** è una *sottostringa di read* di lunghezza <code>k</code>. Il report deve presentare per ciascun *k-mer* che ha una frequenza almeno pari a *F* (nel dataset di input) quante volte appare in **ciascuna delle posizioni dei reads** dalla prima a <code>L - k + 1</code> (<code>L</code>: lunghezza dei reads). Selezionare il *k-mer* che appare più volte in una *certa posizione* e produrre in un file <code>FASTA</code> i *reads* che lo contengono (in quella posizione) con la loro **qualità media**.

## Input
* ***File*** <code>FASTQ</code> di una o più reads (*SRR18961685-5000.fastq* è un esempio);
* ***F***: soglia di frequenza minima;
* ***k***: lunghezza dei k-meri

## Output
***File*** <code>FASTA</code> contente i *reads selezionati* e le loro *qualità medie*.

## Parametri
* ***L*** : lunghezza dei reads (costante);
* ***N*** : numero dei reads



