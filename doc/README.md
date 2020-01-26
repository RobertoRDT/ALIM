# Origine dei file di Jan Ctibor

I file in questa cartella sono stati consegnati il 05/11/2018 da Jan Ctibor alla fine del suo lavoro di revisione, consistente principalmente nell'inserimento del markup strutturale (`<div>`, `<p>`, `<head>` e simili) e nel controllo dei metadati nei `<teiHeader>`.



# Log files

I file di log si trovano nella cartella `logs`. Ad esempio, il file `logs/log_00175-00203.txt` fa riferimento ai file da `00175_Albertus-Miliolus_Liber-de-temporibus-et-etatibus-Continuatio-Regina-et-Cronica-Imperatorum.xml` a `00202_Iacobus-Veronensis_Liber-peregrinationis.xml` (il file 203 non esiste nella cartella).

# Revisione linguistica dei log files

A luglio 2019, l'équipe di codifica ha intrapreso una revisione linguistica dei file di log, con l'obiettivo di inserire i log nei teiHeader di ogni file TEI XML e quindi renderli pubblici. Dal 20.07.2019, la cartella `logs` è dunque divisa in due sottocartelle:

* `Pre-revisione linguistica`
* `Post-revisione linguistica` (che contiene i file rivisti).


# Numeri identificativi

I numeri iniziali (ad es. 175 o 4628) sono quelli alla fine del'URL stabile assegnato al testo nel portale ALIM 2 <http://alim.unisi.it/>. Ad esempio, il testo 175 ha URL http://alim.unisi.it/dl/resource/175. Gli zeri iniziali dei nomi file di questa cartella (es. 00175 o 04628) non compaiono nell'URL: sono stati inseriti nei nomi file per facilitarne l'ordinamento.


# Altre cartelle

* `dtd` contiene una DTD TEI all
* `sh` contiene un paio di script bash usati da J. Ctibor per controlli sui file



# Due file tralasciati

Si noti che i file

* `00437_tralasciato.txt`
* `00438_tralasciato.txt`

sono semplici segnaposto per indicare che, come indicato anche nel log `logs/log_00431-00470.txt`, i testi 437 e 438 (Commenti di Th. Aq.) sono stati tralasciati, ovvero non si trovano in questa cartella e J. Ctibor non vi ha lavorato sopra.  I testi corrispondenti possono essere scaricati direttamente dal sito ALIM2, rispettivamente da

* <http://alim.unisi.it/dl/resource/437>
* e <http://alim.unisi.it/dl/resource/438>

I due file .txt tralasciati erano vuoti, e Dropbox non li accettava. Paolo Monella vi ha inserito come contenuto una riga di nota.



# Zeri iniziali nei nomi file TEI XML

Rispetto ai nomi di file originali di J. Ctibor, Paolo Monella il 27.06.2019 ha messo uno o due zeri prima dei nomi file inizianti con un numero di tre cifre, in modo da renderli tutti di 5 cifre. Esempio: ha cambiato `434_Terrisius-de-Atina_Preconia-Frederici.xml` in `00434_Terrisius-de-Atina_Preconia-Frederici.xml`.

Questo per facilitare l'ordinamento dei file (considerato che alcuni file avevano 3 cifre, altri 4, altri 5).

Ha fatto lo stesso per i file di log: `log_175-203.txt` è diventato `log_00175-00203.txt`.
