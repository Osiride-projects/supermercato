# supermercato

UniPi, Informatica
Laboratorio di Sistemi Operativi 
Progetto a.a. 2019-2020

DESCRIPTION
  programma multithreaded che simula un supermercato. 
  Le entità principali saranno Clienti, Cassieri e Direttore, ogniuno rappresentato da un thread.
  Per maggiori informazioni riguardo il testo consultare il file specifiche.pdf

INSTALL
  make

RUN
  make test
  
UNISTALL
  make clean
  
BUGS
  il direttore aspetta in attesa attiva utilizzando così un core al 100%.
