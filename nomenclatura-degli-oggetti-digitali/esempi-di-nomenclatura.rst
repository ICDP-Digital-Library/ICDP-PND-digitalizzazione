Esempi di nomenclatura
======================

Un esempio di ambito archivistico può essere il seguente:

-  Codice Istituto = **IT-MC0238** [50]_

-  Codice Oggetto = **00000213**

-  Numero Progressivo = **00001**

-  Estensione del file = **.jpg**

Pertanto, il nome risultante sarà: IT-MC0238+00000213+00001.jpg

Il codice oggetto in questo caso è un codice progressivo che è stato
assegnato dal software di descrizione.

Un altro esempio, con *encoding* del codice oggetto, può essere il
seguente:

-  Codice Istituto = **IT-MC0238**

-  Codice Oggetto = **Anagrafe_Registri_00000213** [51]_

-  Numero Progressivo = **00001**

-  Estensione del file= **.jpg**

Pertanto, il nome risultante è:
IT-MC0238+Anagrafe_Registri_00000213+00001.jpg

In questo caso il Codice oggetto è una segnatura che è stata indicata
per l’oggetto.

Un esempio per gli oggetti digitali collegati a descrizioni
bibliografiche può essere il seguente:

-  Codice Istituto = **IT-MI0185** [52]_

-  Codice Oggetto = **BVEE022376** [53]_

-  Numero Progressivo = **00001**

-  Estensione del file = **.jpg**

Pertanto, il nome risultante è: IT-MI0185-BVEE022376+00001.jpg

Nel caso di un periodico, nel codice oggetto trovano spazio una serie di
informazioni che devono essere segmentate per rendere univoca ed
esplicita la nomenclatura del file.

Un possibile esempio di composizione del codice oggetto può risultare
dalla giustapposizione del codice BID della testata, dei dati
cronologici del fascicolo, del numero del fascicolo, e di eventuali
informazioni aggiuntive del fascicolo, separati da “_” (underscore).

Un esempio può essere il seguente:

-  Codice Istituto = **IT-MI0185**

-  Codice Oggetto = **TO00199240_18690503_01** [54]_

-  Numero Progressivo = **00001**

-  Estensione del file = **.jpg**

Il nome risultante è: IT-MI0185+TO00199240_18690503_01+0001.jpg

Nel caso dei file multimediali allegati ad una scheda di catalogo, un
esempio può essere il seguente:

-  Codice Istituto = **S29** (codice assegnato in SIGECweb)

-  Codice Oggetto = **12345678** (codice univoco catalografico
   dell’entità catalogata nel sistema nazionale)

-  Numero progressivo = **00001**

-  Estensione del file = **.tiff**

Il nome risultante è: S29+12345678+00001.tiff

Nel caso di file sonori, ad esempio di un vinile, un esempio può essere
il seguente:

-  Codice Istituto = **IT-RM0200** (codice ISIL dell’ICBSA)

-  Codice Oggetto= **DDS0253686** (corrisponde al BID)

-  Numero Progressivo = **00001** (per il lato A) o **00002** (per il
   lato B)

-  Estensione del file = **.wav**

Il nome risultante è: IT-RM0200+DDS0253686+0001.wav

Per una migliore organizzazione dei contenuti, la struttura gerarchica
del *file system* deve essere coerente con la struttura della
nomenclatura dei file. Con la medesima finalità, nel progetto di
digitalizzazione si possono rendere esplicite ulteriori regole di
articolazione del *file system*.

Di seguito si riporta un esempio basato su codice istituto e codice
oggetto:

-  **Codice istituto**

   -  **Codice oggetto** (dentro la cartella trovano spazio,
      indifferentemente, tutti i file digitali prodotti nelle diverse
      estensioni)

Un altro possibile livello comprende anche l’estensione dei file:

-  **Codice istituto**

   -  **Codice oggetto**

      -  **Estensione file** (dentro le sottocartelle trovano spazio i
         file digitali prodotti in una particolare estensione, per
         esempio cartella “tiff”, cartella “jpg” ecc.)

Le regole seguite per la nomenclatura, in particolare in riferimento a
come è strutturato il codice oggetto, vanno rese esplicite e descritte
nella documentazione di progettazione, e inserite nei supporti di
consegna.

.. [50] Codice ISIL dell’Archivio di Stato di Macerata.

.. [51] Segnatura dell’unità modificata per essere *URI compliant* in cui lo
   spazio è sostituito dal carattere “_” [underscore].

.. [52] Codice ISIL della Biblioteca nazionale Braidense.

.. [53] In questo caso il codice oggetto è un BID SBN
   (http://id.sbn.it/bid/BVEE022376).

.. [54] Dove TO00199240 rappresenta il BID dell’unità nel catalogo
   nazionale; 18690503_01 rappresenta i Dati cronologici del fascicolo.
