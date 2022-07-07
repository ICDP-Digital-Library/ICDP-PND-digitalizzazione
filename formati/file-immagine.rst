File immagine
=============

Il file master di output consiste in un pacchetto di file comprendente:

-  Il file TIFF 6.0 non compresso a 16 o 48 bit (**scala di grigi**\* o
   RGB), a seconda della cromia del bene;

-  Il file RAW non compresso, con allegato il file collaterale XMP.

Per la consegna dei file RAW è preferibile il formato DNG. La
risoluzione spaziale minima del file master dipende da molteplici
fattori quali, ad esempio, la tipologia del sensore della fotocamera o
dello scanner, la dimensione del bene, ecc. Per esigenze di
conservazione di positivi e negativi fotografici in **bianco e nero**\*
è necessario eseguire comunque la digitalizzazione in RGB a 48 bit.

Le specifiche tecniche dei pacchetti dei file master possono essere
adattate in base a documentate esigenze specifiche del progetto di
digitalizzazione. Alcuni fattori che possono condizionare la scelta del
numero dei file componenti il pacchetto “master” e la tipologia del
formato di ciascuno di questi file sono la tipologia dei materiali
analogici da digitalizzare, le caratteristiche dei macchinari e delle
tecniche di digitalizzazione più appropriate in relazione agli oggetti
analogici, il numero degli oggetti da digitalizzare nell’ambito del
progetto e i costi di storage connessi all’archiviazione digitale dei
file master.

.. _Linee guida per la redazione del piano di gestione dei dati: https://docs.italia.it/italia/icdp/icdp-pnd-dmp-docs/

Nel caso, ad esempio, della digitalizzazione bidimensionale di documenti
cartacei quali periodici a stampa come giornali e quotidiani, è
possibile richiedere come file master unicamente il file TIFF secondo le
specifiche sopra indicate. Infatti, il considerevole numero di oggetti
digitali prodotti nell’ambito del progetto di digitalizzazione di ambito
bibliotecario si traduce in un maggiore costo di storage del gran numero
di file RAW prodotti in fase di digitalizzazione. In ogni caso, la
scelta dei componenti del pacchetto dei file master, delle loro
caratteristiche e formati deve essere adeguatamente documentata e
argomentata nel piano di gestione dei dati (DMP, cfr. `Linee guida per la redazione del piano di gestione dei dati`_).

I file derivati da richiedere dipendono dalla specificità del progetto
di digitalizzazione: sono consigliabili file compressi in formato JPG
con lato lungo di almeno 3000 pixel, con qualità di **compressione*d**
non inferiore al 75%, aventi spazio colore sRGB o scala di grigi [1]_, a
seconda della tipologia di scansione effettuata. In alternativa al
“classico” JPG può essere richiesto il formato contenitore HEIF (*High
Efficiency Image Format*) o HEIC (*High Efficiency Image Coding*) [2]_.

Si segnala anche il formato standard FITS, definito dallo *IAU FITS
Working Group, Commission B2 Data and Documentation* (Definition of the
Flexible Image Transport System (FITS)). Il formato FITS è alla base
della norma UNI 11845 2022 (*Processi di gestione della conservazione a
lungo termine di immagini digitali con l'uso del formato FITS*),
pubblicata nel catalogo nazionale UNI il 20 gennaio 2022, che definisce
caratteristiche e requisiti funzionali che un archivio basato sull’uso
del formato FITS deve soddisfare per l’idoneità a lungo termine della
conservazione delle immagini digitali.

Master RAW
----------

La scelta di conservare il file in formato RAW ha due principali
motivazioni:

1. Rendere il processo di digitalizzazione reversibile, permettendo di
   risalire al file nativo *pre-editing*. Nonostante il file TIFF
   (seppur prodotto a regola d’arte) rappresenti un prodotto di qualità,
   questo potrebbe non soddisfare esigenze estetiche da parte
   dell’utente finale (esempi: eliminazione di maschere di contrasto,
   selezioni dei soggetti, profili colore *output*, ecc.);

2. Il file RAW è un file aperto che ci consente di operare sull’immagine
   acquisita partendo dalla sua genesi fotografica.

Considerando quest’ultima caratteristica, il file RAW consente di
risalire a informazioni in merito alle scelte di ripresa fotografica che
possono risultare utili in campo di ricerca e studio (per esempio nello
studio degli archivi digitali).

Caratteristiche di un file RAW
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

1. Profondità di bit. Un file RAW, demosaicizzato in un programma di
   conversione RAW quando viene salvato in un altro formato (per esempio
   TIFF) può essere esportato anche a 16 bit per canale. Se invece si
   decide di generare con lo scatto un file in formato JPEG, questo sarà
   creato automaticamente dal software della macchina (partendo sempre
   da una cattura RAW) a 8 bit di profondità, ossia a 256 livelli di
   luminosità per canale, cioè poco più di 16,7 milioni di colori. Avere
   a disposizione un file ricco di informazioni (quindi con una maggiore
   profondità di bit) è molto utile quando l’immagine richiede
   regolazioni particolarmente profonde e complesse. Una grande
   profondità in bit permette di intervenire notevolmente sull’immagine
   senza incappare nella posterizzazione, ossia nella mancanza di una
   transizione morbida di colori e toni che compromette la qualità
   complessiva dell’immagine.

2. Imparzialità del contenuto. RAW in inglese significa "allo stato
   grezzo": il RAW contiene tutti i dati provenienti dal sensore, senza
   esclusioni, senza cioè nessuna compressione. Il file RAW racchiude
   anche le impostazioni della macchina (ad esempio contrasto,
   saturazione, temperatura colore, nitidezza, ecc.): per ogni RAW,
   infatti, la fotocamera crea un file di intestazione contenente le
   impostazioni della macchina. Questi parametri non cambiano
   l’immagine, essendo delle pure istruzioni allegate ai dati del file
   grezzo. Con lo stesso principio vengono salvati anche i metadati,
   ossia i dati **EXIF**\* relativi alle impostazioni di scatto (ad
   esempio l’apertura del diaframma utilizzata, la **lunghezza
   focale**\*, eccetera). Per questo motivo sono in molti a vedere nei
   file RAW un’analogia con il negativo della fotografia analogica, dal
   momento che le informazioni raccolte vengono riproposte esattamente
   come tali.

3. Flessibilità e controllo delle regolazioni. Il fatto che le
   impostazioni della macchina non vengano direttamente applicate
   all’immagine generata (proprio perché non esiste ancora un’immagine
   ma solamente un insieme di dati) presuppone che ciò avvenga in un
   secondo momento e apre un mondo di possibilità. In pratica il file
   grezzo richiede uno "sviluppo", ossia la sua conversione. E lo
   sviluppo consiste proprio nell’applicare, successivamente allo
   scatto, tutta una serie di impostazioni senza minimamente inficiare
   il risultato che si sarebbe ottenuto applicandole al momento stesso
   dello scatto. Così, durante il processo di sviluppo è possibile
   applicare ad esempio le regolazioni della temperatura del colore
   senza pregiudicare la qualità dell’immagine (la modifica della
   temperatura colore durante la conversione RAW dà esattamente gli
   stessi risultati di uno scatto impostato con una diversa temperatura
   del colore). Naturalmente questo vale anche per gli altri parametri
   fondamentali, come ad esempio il controllo della saturazione, del
   contrasto, della nitidezza e dell’esposizione. In generale quindi è
   possibile, scattando in RAW, avere un notevole controllo su tutti i
   parametri di scatto non meccanici (intendendo questi il diaframma,
   l’otturatore, ecc.) che influiscono sulla resa dell’immagine finale.

.. [1] Nel caso dei file derivati in formato JPEG è sufficiente l’utilizzo
   dello spazio colore sRGB in quanto le modalità di fruizione
   dell’immagine digitale, mediata da un monitor o comunque da un altro
   dispositivo non professionale, non rendono necessario l’utilizzo di
   specifiche più performanti.

.. [2] Si segnala che sono in corso iniziative per la standardizzazione di
   formati immagine, come ad esempio JPG XL o il JBIG2; in questo
   documento ci si limita a segnalare la loro esistenza in attesa di
   verificarne il livello di diffusione e di standardizzazione.
