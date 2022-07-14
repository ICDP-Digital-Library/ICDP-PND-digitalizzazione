Lo standard METS
================

Fatta salva la possibilità da parte degli istituti culturali di produrre
metadati secondo standard necessari per la gestione delle risorse
all’interno dei propri sistemi, nelle presenti Linee guida viene
descritto il METS (Metadata Encoding and Transmission Standard) [15]_,
standard di metadatazione ampiamente utilizzato a livello internazionale
che occorre utilizzare a livello nazionale per la descrizione e la
gestione degli oggetti digitali nei progetti di digitalizzazione. Lo
standard METS costituisce il linguaggio di interscambio tra i sistemi
afferenti e l’Istituto centrale per la digitalizzazione del patrimonio
culturale – Digital Library. Il METS serve per codificare metadati
descrittivi, amministrativi e strutturali riguardanti le risorse
digitali.

La generazione di metadati METS viene realizzata per mezzo dello
sviluppo di specifici software appositamente customizzati a seconda
delle necessità del singolo progetto di digitalizzazione. Salvo casi
particolari, questa attività viene svolta dai fornitori dei servizi di
digitalizzazione.

Un documento METS è costituito da sette sezioni principali:

1. **<metsHdr>** Intestazione METS: contiene i metadati che descrivono
   il documento METS stesso, includendo alcune informazioni quali
   autore, editore, ecc.;

2. **<dmdSec>** Metadati descrittivi: contiene al suo interno i metadati
   descrittivi, o punta a metadati esterni specifici per ciascun
   dominio;

3. **<amdSec>** Metadati amministrativi: contiene sia informazioni sui
   file creati, che conservano anche i diritti di proprietà
   intellettuale, sia metadati riguardanti l'oggetto di origine da cui
   deriva l'oggetto digitale, sia informazioni sulla provenienza dei
   file e sulle relazioni degli oggetti digitali;

4. **<fileSec>** Sezione file: è una lista di tutti i file contenente le
   versioni elettroniche dell'oggetto digitale;

5. **<structMap>** Mappa strutturale: descrive la struttura gerarchica,
   fisica o logica, dell'oggetto digitale e collega i file e i metadati
   loro associati;

6. **<structLInk>** Link strutturali: permette di gestire collegamenti
   ipertestuali tra nodi nella gerarchia definita nella Mappa
   strutturale;

7. **<behaviour>** Comportamento: può essere usato per associare
   comportamenti (per esempio, la visualizzazione) con il contenuto
   dell'oggetto METS.

.. [15] https://www.loc.gov/standards/mets/
