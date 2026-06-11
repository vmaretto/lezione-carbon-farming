# Tre schede tecniche per infografiche — Tecnologie digitali per il Carbon Farming

*Documento-fonte per NotebookLM. Contiene tre schede compatte: ogni infografica si genera da una scheda, indicandola nel prompt di personalizzazione.*

---

## SCHEDA 1 — La catena del dato IoT: dal suolo al verificatore

Il monitoraggio IoT nel carbon farming è una catena di sei anelli, in cui il dato nasce nel suolo e arriva al verificatore senza passaggi manuali.

Anello 1 — Il sensore nel suolo. Sonde interrate misurano umidità, temperatura e proxy del carbonio organico (spettroscopia NIR). Frequenza: una misura ogni ora. Costo crollato: da migliaia di euro a poche decine per sonda.

Anello 2 — Il nodo radio LoRaWAN. Trasmette i dati a chilometri di distanza con consumi minimi: una batteria dura fino a 10 anni. Nessun cablaggio, nessuna SIM costosa.

Anello 3 — Il gateway aziendale. Raccoglie i segnali di decine di sensori e li instrada verso internet. Un solo gateway copre un'intera azienda agricola.

Anello 4 — Il cloud. I dati grezzi vengono archiviati con coordinate e timestamp: nasce l'audit trail, la storia non modificabile di ogni misura.

Anello 5 — Il modello AI. I dati di campo calibrano i modelli che stimano il carbonio su tutta la superficie.

Anello 6 — Il report per il verificatore. La rendicontazione si genera automaticamente; il verificatore accede anche al dato grezzo.

I tre numeri da ricordare: una misura ogni ora contro un campionamento ogni 1-5 anni del metodo tradizionale; 10 anni di autonomia di batteria; chilometri di portata radio con pochi milliwatt.

Il messaggio chiave: il sensore a terra è la "verità di campo" che rende credibile tutto il resto — satellite e AI senza dato a terra sono stime cieche.

---

## SCHEDA 2 — La fabbrica della stima: come l'AI mappa il carbonio

Il problema: misurare il carbonio in ogni punto di un'azienda da 250 ettari richiederebbe migliaia di campionamenti. Impossibile economicamente.

La soluzione AI funziona come una catena di montaggio in quattro stazioni.

Stazione 1 — Gli ingredienti (input). Poche centinaia di campioni di suolo georeferenziati e analizzati in laboratorio; immagini satellitari multispettrali (Sentinel-2, ogni 5 giorni); dati meteo e mappe pedologiche; il registro digitale delle pratiche (cover crops, lavorazioni).

Stazione 2 — L'apprendimento. Il modello di machine learning impara la relazione tra ciò che il satellite vede e ciò che il laboratorio ha misurato nei punti campionati. I modelli di processo (RothC, DayCent) aggiungono la dinamica temporale: come evolve il carbonio negli anni con quelle pratiche e quel clima.

Stazione 3 — La mappa (output). Il modello stima il carbonio organico ettaro per ettaro, anche dove nessuno ha mai campionato: da 300 punti misurati a 250 ettari mappati.

Stazione 4 — L'incertezza dichiarata. Ogni stima esce con il suo margine di errore (esempio: ±15%). Questo numero è denaro: il verificatore trattiene un buffer proporzionale all'incertezza. Con incertezza ±35% su 200 tonnellate si emettono circa 150 crediti; con ±15% se ne emettono 180. Ridurre l'incertezza di 20 punti vale 30 crediti in più, ogni anno.

Il messaggio chiave: l'AI non sostituisce la misura — la moltiplica. E l'incertezza dichiarata è il numero che trasforma una stima scientifica in un valore economico.

---

## SCHEDA 3 — Il registro che non si può riscrivere: la vita di un credito-token

La vita di un credito di carbonio tokenizzato in cinque tappe.

Tappa 1 — Emissione. Solo dopo la verifica indipendente: il verificatore firma, il credito nasce con un numero di serie unico. Una tonnellata di CO2, un token, una sola volta.

Tappa 2 — Registrazione. Il token entra nel registro distribuito: ogni blocco contiene l'impronta digitale (hash) del precedente. Modificare un blocco passato romperebbe visibilmente tutta la catena.

Tappa 3 — Scambio. Ogni passaggio di proprietà è tracciato pubblicamente: chiunque può ricostruire la storia del credito dal campo al compratore.

Tappa 4 — Retirement (ritiro). Il compratore "ritira" il credito per compensare le proprie emissioni: il token viene marcato come consumato, per sempre. Nessuno potrà rivenderlo o conteggiarlo due volte. Il ritiro è pubblico e verificabile da chiunque, anche da un giornalista.

Tappa 5 — Pagamento automatico. Lo smart contract può liberare il pagamento all'agricoltore nel momento esatto in cui la verifica si chiude: da 60-90 giorni di attesa a pochi minuti.

Confronto tra i due mondi. Registro tradizionale: consultazione su richiesta, fiducia basata sull'ente che lo gestisce, pagamenti lenti, rischio di doppio conteggio tra registri diversi. Registro tokenizzato: consultazione pubblica e permanente, fiducia basata sulla matematica della catena, pagamenti automatici, doppio conteggio impossibile all'interno del registro.

Il limite onesto (problema dell'oracolo): la blockchain garantisce che il dato registrato non venga alterato, non che sia vero. Se entra un dato sbagliato, resta sbagliato — immutabilmente. Per questo la qualità della misura a monte (sensori, AI, verifica) resta la vera fondazione della fiducia.

Il messaggio chiave: la blockchain non crea fiducia — la trasporta e la custodisce.
