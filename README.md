ESITI PUBBLICATI 2/190 

- 17/01/2022 12 E4  Diritto dell'Unione europea	 [I fascia](https://asn21.cineca.it/pubblico/miur/esito/12%252FE4/1/1) [II fascia](https://asn21.cineca.it/pubblico/miur/esito/12%252FE4/2/1) 

- 22/12/2021 12 B2  Diritto del lavoro	 [I fascia](https://asn21.cineca.it/pubblico/miur/esito/12%252FB2/1/1) [II fascia](https://asn21.cineca.it/pubblico/miur/esito/12%252FB2/2/1) 

UPDATED 2022-01-17 14:37:51.159111
######################################################

Si tratta di un semplice script in python per controllare quando sono pubblicati gli esiti (ASN 2018, sesto quadrimestre).

E' sufficiente avere installato python3 e lanciare "python3 getasn.py". E' necessario che nella cartella esista il file secs.txt (contiene l'elenco dei SSC). Se presente il file tobenotified.txt, il programma manda avvisi alle e-mail presenti.

Per lanciarlo ripetutamente, si possono usare run.sh (file bash settato per ogni ora) oppure gestire un crontab.

Tiziano
