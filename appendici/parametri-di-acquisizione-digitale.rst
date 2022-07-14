Parametri di acquisizione digitale
==================================

Di seguito si forniscono alcune specifiche tecniche significative sulle
modalità di acquisizione di diverse tipologie di beni culturali. I
parametri per l'acquisizione digitale variano, generalmente, a seconda
della dimensione dei beni, con delle ulteriori distinzioni riferite alle
loro specificità materiali e compositive.

+-----------------------------------+-----------------------------------+
| **FOTOGRAFIA DIGITALE - 2D**      |                                   |
+-----------------------------------+-----------------------------------+
| **Tipologia di bene**             | **Range risoluzione spaziale**    |
+-----------------------------------+-----------------------------------+
| Beni della dimensione fino a      | 4000 ppi                          |
| circa 5 cm lato lungo             |                                   |
+-----------------------------------+-----------------------------------+
| Beni della dimensione fino a      | 2400-2800 ppi                     |
| circa 10 cm lato lungo            |                                   |
+-----------------------------------+-----------------------------------+
| Beni della dimensione fino a 15   | 1600-1400 ppi                     |
| cm lato lungo                     |                                   |
+-----------------------------------+-----------------------------------+
| Beni della dimensione fino a 20   | 1400-1200 ppi                     |
| cm lato lungo                     |                                   |
+-----------------------------------+-----------------------------------+
| Beni della dimensione fino a 30   | 600 ppi                           |
| cm lato lungo                     |                                   |
+-----------------------------------+-----------------------------------+
| Beni della dimensione fino a 60   | 400 ppi                           |
| cm lato lungo                     |                                   |
+-----------------------------------+-----------------------------------+
| Beni della dimensione fino a 100  | 300 ppi                           |
| cm lato lungo                     |                                   |
+-----------------------------------+-----------------------------------+
| Beni della dimensione oltre i 100 | Variabile a seconda della         |
| cm lato lungo                     | destinazione finale modellare     |
|                                   | immagine                          |
+-----------------------------------+-----------------------------------+

La tabella riporta, per le varie tipologie di beni di differenti
dimensioni, indicazioni relative alla risoluzione spaziale.

Per ogni acquisizione digitale la profondità di colore è, in modalità
RGB, di 48 bit.

È opportuno calcolare le dimensioni finali delle acquisizioni digitali
usando o un foglio di calcolo o delle applicazioni disponibili online.

Per finalità di pubblicazione in rete si raccomanda di produrre file
JPEG a 300 ppi, con valore di compressione 85%, con profondità di colore
a 24 bit RGB, con ricampionamento (*resampling*) delle immagini, metodo
tramite il quale il “print size” (DPI) del file JPG risulterà identico a
quello del file TIFF.

Nel caso di documenti di dimensioni molto piccole, di cui una inferiore
ai 10 cm, mantenendo il JPEG 300 ppi, può essere opportuno applicare il
parametro relativo alle dimensioni in pixel della risorsa digitale,
definendo di default il valore per il lato lungo: 3000 pixel. Tuttavia,
una valutazione sull'utilizzo di questa modalità deve essere oggetto
delle analisi, da parte di tutte le parti interessate, nella fase
pre-prototipale.

+------------------------+--------------------------------+
| **SCANSIONE LASER**    |                                |
+------------------------+--------------------------------+
| **Livelli di fedeltà** | **Errore massimo accettabile** |
+------------------------+--------------------------------+
| Beni mobili            | (Errore minore di 5 mm)        |
|                        |                                |
|                        | Dato colore                    |
+------------------------+--------------------------------+
| Beni immobili          | (Errore minore di 10 mm)       |
|                        |                                |
|                        | Dato colore                    |
+------------------------+--------------------------------+

+-----------------------+-----------------------+-----------------------+
| **FOTOGRAMMETRIA**    |                       |                       |
+-----------------------+-----------------------+-----------------------+
| **Tipologia           | **Peculiarità**       | **Risoluzione         |
| superficie**          |                       | minima**              |
+-----------------------+-----------------------+-----------------------+
| Superfici murarie     | Omogenee / marmo /    | 2 mm/px               |
| piane                 | meccate o dorate      |                       |
+-----------------------+-----------------------+-----------------------+
|                       | Affrescate            | 1 mm/px               |
+-----------------------+-----------------------+-----------------------+
| Superfici murarie     | Omogenee / marmo /    | 2 mm/px               |
| curve - volte         | dorate                |                       |
+-----------------------+-----------------------+-----------------------+
|                       | Affrescate            | 1 mm/px               |
+-----------------------+-----------------------+-----------------------+
| Colonne, bassorilievi | Intonaco o stucco /   | 5 mm/px               |
|                       | meccate o dorate      |                       |
+-----------------------+-----------------------+-----------------------+
|                       | Pietra non lucidata / | 2 mm/px               |
|                       | marmo / policrome /   |                       |
+-----------------------+-----------------------+-----------------------+
| Pavimenti             | Cotto o gres / pietra | 2 mm/px               |
|                       | grezza / marmo /      |                       |
|                       | mosaico               |                       |
+-----------------------+-----------------------+-----------------------+

+-----------------+-------------------+-------------------+-------------------+
| **AUDIO         |                   |                   |                   |
| (supporti       |                   |                   |                   |
| analogici e     |                   |                   |                   |
| digitali)**     |                   |                   |                   |
+-----------------+-------------------+-------------------+-------------------+
| **Tipologia di  | **Formato         | **Metadati        | **Altri           |
| supporto        | dell’informazione | tecnici**         | documenti         |
| originale**     | digitale          |                   | allegati**        |
|                 | master**          |                   |                   |
+-----------------+-------------------+-------------------+-------------------+
| **Supporti      | File PCM (Pulse   | Dati relativi     | Per ognuno dei    |
| analogici**     | Code              | alla specifica    | supporti          |
|                 | Modulation) 24    | catena di         | oggetto della     |
| **Incisione     | bit/96 kHz nel    | digitalizzazione: | digitalizzazione  |
| meccanica:**    | formato wave      |                   |                   |
|                 | oppure BWF. Non   | marca e tipo di   | dovranno essere   |
| cilindri        | sono              | lettore           | eseguite la       |
| fonografici     | ammissibili       | utilizzato        | scansione (o la   |
|                 | formati           | (specificando     | ripresa           |
| dischi macro    | “proprietari”     | le                | fotografica)      |
| solco (78 giri, | non aperti.       | caratteristiche   |   del supporto    |
| ecc.)           |                   | geometriche e     | stesso e di       |
|                 |                   | dimensionali      | ogni altro        |
| dischi          |                   | del pick-up       | documento o       |
| microsolco (Lp, |                   | utilizzato,       | materiale         |
| 45 giri, ecc.)  |                   | velocità di       | pertinente al     |
|                 |                   | lettura,          | supporto          |
| **Supporti      |                   | configurazione    | (buste,           |
| magnetici:**    |                   | delle tracce      | contenitori,      |
| (fili           |                   | -MONO/STEREO),    |   fogli di        |
| metallici,      |                   | applicazione o    | lavorazione,      |
| nastri          |                   | meno di curve     | libretti, ecc.)   |
| magnetici a     |                   | di                |                   |
| bobina aperta,  |                   | equalizzazione,   |                   |
| audio cassette. |                   | marca e tipo di   |                   |
| ecc.)           |                   | convertitore      |                   |
|                 |                   | A/D, ecc.         |                   |
+-----------------+-------------------+-------------------+-------------------+
| **Supporti      | Nel caso di       | Dati relativi     | Per ognuno dei    |
| digitali**      | supporti che      | alla specifica    | supporti          |
|                 | contengono dati   | catena di         | oggetto della     |
| **Dischi ottici | digitali o        | digitalizzazione: | digitalizzazione  |
| e               | flussi di dati    |                   |                   |
| magneto-ottici: | binari (CD-A,     | marca e tipo di   | dovranno essere   |
| **              | R-DAT. ecc.)      | lettore           | eseguite la       |
|                 | riferiti ad uno   | utilizzato.       | scansione (o la   |
| Cd, Dvd,        | specifico         |                   | ripresa           |
| Minidisc, ecc.  | formato           | Tipo di           | fotografica)      |
|                 | digitale, deve    | interfaccia di    | del supporto      |
| **Nastri        | essere            | out utilizzata    | stesso e di       |
| magnetici       | rispettato il     | (SPDIF, ripping   | ogni altro        |
| digitali:**     | formato di        | via software,     | documento o       |
|                 | partenza (CD-A    | AES/EBU,          | materiale         |
| R-DAT, ADAT,    | = file wave 16    | ottica, ecc.),    | pertinente al     |
| ecc.            | bit 44,1 kHz;     | marca e tipo di   | supporto          |
|                 | R-DAT = 16 bit    | convertitore      | (buste,           |
|                 | 44,1 op. 48       | A/D, ecc.         | contenitori,      |
|                 | kHz, ecc.).       |                   | fogli di          |
|                 |                   |                   | lavorazione,      |
|                 | Non sono          |                   | libretti, ecc.)   |
|                 | consentiti        |                   |                   |
|                 | interventi di     |                   |                   |
|                 | ricampionamento   |                   |                   |
|                 | dei dati          |                   |                   |
|                 | originali.        |                   |                   |
+-----------------+-------------------+-------------------+-------------------+

+-----------------+-------------------+-------------------+-------------------+
| **VIDEO         |                   |                   |                   |
| (supporti       |                   |                   |                   |
| analogici e     |                   |                   |                   |
| digitali)**     |                   |                   |                   |
+-----------------+-------------------+-------------------+-------------------+
| **Tipologia di  | **Formato         | **Metadati        | **Altri           |
| supporto        | dell’informazione | tecnici**         | documenti         |
| originale**     |                   |                   | allegati**        |
|                 | digitale          |                   |                   |
|                 | master**          |                   |                   |
+-----------------+-------------------+-------------------+-------------------+
| **Supporti      | Esistono          | Dati relativi     | Per ognuno dei    |
| analogici:**    | attualmente       | alla specifica    | supporti          |
|                 | diversi formati   | catena di         | oggetto della     |
| **U-matic**     | digitali master   | digitalizzazione: | digitalizzazione  |
|                 | di                |                   |                   |
| **Betacam**     | archiviazione,    | marca e tipo di   | dovranno essere   |
|                 | la scelta del     | lettore           | eseguite la       |
| **Betacam SP**  | formato           | utilizzato.       | scansione (o la   |
|                 | migliore          |                   | ripresa           |
| **8mm, Hi8**    | dipende dalle     | Marca e tipo di   | fotografica)      |
|                 | caratteristiche   | convertitore      | del supporto      |
| **VHS**         | del supporto      | A/D, ecc.         | stesso e di       |
|                 | originale. Per    |                   | ogni altro        |
| **S-VHS**       | indicazione di    |                   | documento o       |
|                 | dettaglio si      |                   | materiale         |
| **Ecc.**        | rimanda a IASA    |                   | pertinente al     |
|                 | TC-06             |                   | supporto          |
|                 |                   |                   | (buste,           |
|                 |                   |                   | contenitori,      |
|                 |                   |                   | fogli di          |
|                 |                   |                   | lavorazione,      |
|                 |                   |                   | libretti,         |
|                 |                   |                   | ecc.).            |
+-----------------+-------------------+-------------------+-------------------+
| **Supporti      | Le                | Dati relativi     | Per ognuno dei    |
| digitali:**     | registrazioni     | alla specifica    | supporti          |
|                 | digitali native   | catena di         | oggetto della     |
| **BetacamSX**   | possono           | digitalizzazione: | digitalizzazione  |
|                 | richiedere il     |                   |                   |
| **Digital-S     | *rewrapping* in   | Marca e tipo di   | dovranno essere   |
| Component**     | un nuovo          | lettore           | eseguite la       |
|                 | "*wrapper*" di    | utilizzato.       | scansione (o la   |
| **DVCAM**       | file o una        |                   | ripresa           |
|                 | combinazione di   | Tipo di           | fotografica)      |
| **DVC**         | transcodifica     | interfaccia di    | del supporto      |
|                 | digitale e        | out utilizzata    | stesso e di       |
| **DVCPRO**      | *rewrapping*.     |                   | ogni altro        |
|                 | Per indicazione   |                   | documento o       |
| **DVD**         | di dettaglio si   |                   | materiale         |
|                 | rimanda a IASA    |                   | pertinente al     |
| **BLU-RAY**     | TC-06.            |                   | supporto          |
|                 |                   |                   | (buste,           |
|                 |                   |                   | contenitori,      |
|                 |                   |                   | fogli di          |
|                 |                   |                   | lavorazione,      |
|                 |                   |                   | libretti,         |
|                 |                   |                   | ecc.).            |
+-----------------+-------------------+-------------------+-------------------+
