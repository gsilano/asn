ESITI PUBBLICATI 0/190 

UPDATED 2022-03-22 13:27:57.878026
######################################################

Si tratta di un semplice script in python per controllare quando sono pubblicati gli esiti (ASN 2021, secondo quadrimestre).

E' sufficiente avere installato python3 e lanciare "python3 getasn.py". E' necessario che nella cartella esista il file secs.txt (contiene l'elenco dei SSC). Se presente il file tobenotified.txt, il programma manda avvisi alle e-mail presenti.

Per lanciarlo ripetutamente, si possono usare run.sh (file bash settato per ogni ora) oppure gestire un crontab.

Tiziano
