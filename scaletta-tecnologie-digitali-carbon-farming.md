# Tecnologie digitali per il Carbon Farming
## Scaletta lezione — 3 ore (Modulo: Carbon Farming e tecniche MRV)

**Filo conduttore:** dal generale al particolare. Le tecnologie digitali nascono per altri scopi, diventano abilitanti per la sostenibilità e infine indispensabili per il carbon farming: senza digitale non esiste MRV credibile e scalabile.

---

## PARTE 1 — Premessa: le tecnologie digitali, una breve storia (30 min)

**Obiettivo:** dare contesto e linguaggio comune; non tutti gli studenti hanno background tecnologico.

1. **Cos'è una tecnologia digitale** (5 min)
   - Dato → informazione → conoscenza → decisione. Il digitale come capacità di misurare, trasmettere, elaborare e automatizzare.

2. **Le cinque ondate** (15 min)
   - Anni '50–'70: il calcolo (mainframe, primi modelli di simulazione — anche climatici!)
   - Anni '80–'90: il personal computing e il GIS (nasce la cartografia digitale, fondamentale per l'agricoltura)
   - Anni '90–2000: Internet e il GPS aperto al civile (2000) → nasce l'agricoltura di precisione
   - 2007–2015: smartphone, cloud, big data → il sensore in tasca di ogni agricoltore
   - 2015–oggi: IoT, AI/machine learning, costellazioni satellitari low-cost, blockchain → la convergenza che rende possibile il dMRV

3. **Il concetto di tecnologia emergente** (7 min)
   - Definizione: tecnologia con novità radicale, crescita rapida, impatto potenziale ampio ma **incertezza elevata** su tempi e applicazioni (Rotolo, Hicks & Martin, 2015)
   - Lo Hype Cycle di Gartner come mappa: picco delle aspettative → disillusione → produttività. Posizionare insieme agli studenti AI, IoT, blockchain sul ciclo
   - Implicazione pratica: chi lavora nel carbon farming deve saper distinguere tecnologie *mature* (GPS, GIS), *in consolidamento* (IoT, AI) ed *emergenti/incerte* (blockchain) — perché su questa distinzione si gioca il rischio di un progetto

4. **Concetto chiave da fissare** (8 min)
   - Ogni ondata ha abbattuto un costo: del calcolo, della comunicazione, del posizionamento, del sensore, della previsione. Il carbon farming è economicamente sostenibile solo perché questi costi sono crollati.
   - *Esempio efficace:* il costo di un sensore di umidità del suolo connesso — da migliaia di € a poche decine; o un'immagine satellitare, da migliaia di € (Landsat anni '80) a gratis (Sentinel-2 dal 2015).

> **Suggerimento didattico:** apri con una domanda interattiva — "quante tecnologie digitali avete usato per arrivare qui stamattina?" — per ancorare il concetto al quotidiano.

---

## PARTE 2 — I trend (50 min)

### 2.1 Trend generali del digitale (15 min)
- **AI generativa e predittiva**: da strumento di nicchia a infrastruttura generale
- **IoT ed edge computing**: l'intelligenza si sposta verso il campo (il sensore elabora, non solo misura)
- **Spazio "democratizzato"**: microsatelliti e costellazioni commerciali (Planet, ICEYE) + programmi pubblici (Copernicus)
- **Digital twin**: repliche digitali di sistemi fisici (fabbriche → bacini idrici → aziende agricole)
- **Interoperabilità e dati aperti**: API, standard, data spaces europei

### 2.2 Digitale per la sostenibilità (15 min)
- **Twin transition**: la UE lega esplicitamente transizione verde e digitale
- **ESG e rendicontazione**: CSRD e dintorni → la sostenibilità va *misurata*, non dichiarata → esplode la domanda di dati verificabili
- **Monitoraggio ambientale**: Copernicus come "termometro del pianeta" (deforestazione, emissioni, uso del suolo)
- **Tracciabilità delle filiere**: EUDR (regolamento deforestazione) impone geolocalizzazione delle materie prime
- **Il problema di fondo**: greenwashing → la tecnologia come risposta alla crisi di fiducia

### 2.3 Digitale per il carbon farming (20 min)
- **Perché l'MRV è il collo di bottiglia**: misurare il carbonio nel suolo è costoso, lento e variabile → l'MRV tradizionale (campionamenti + audit) può mangiarsi gran parte del valore del credito
- **Il passaggio da MRV a dMRV** (digital MRV): misura continua, remota, automatizzata, verificabile da terzi
- **Mappa delle tecnologie sul ciclo del credito:**
  | Fase | Tecnologie |
  |---|---|
  | Baseline e progetto | GIS, remote sensing, modelli di simulazione (es. RothC, DayCent) |
  | Pratiche in campo | agricoltura di precisione, guida satellitare, rateo variabile |
  | Monitoraggio | satelliti, droni, sensori IoT, spettroscopia del suolo |
  | Reporting | piattaforme cloud, AI per stima e gap-filling |
  | Verifica | dMRV, audit remoti |
  | Emissione e scambio crediti | registri digitali, blockchain |
- **Contesto normativo**: il CRCF (Carbon Removal and Carbon Farming certification framework, Reg. UE 2024/3012) richiede esplicitamente quantificazione robusta → spinta regolatoria al dMRV

> **Pausa: 10 min** (collocarla qui, a metà lezione)

---

## PARTE 3 — Focus su tre tecnologie (75 min, ~25 min ciascuna)

**Struttura identica per ciascuna:** come funziona → cosa fa per il carbon farming → limiti → caso reale.

### 3.1 IoT e sensoristica di campo (25 min)
- **Come funziona**: la catena sensore → connettività → cloud. Sensori di suolo (umidità, temperatura, CO₂, spettroscopia NIR per il SOC), stazioni meteo, camere di flusso; reti LPWAN (LoRaWAN, NB-IoT) pensate per il campo: basso consumo, lungo raggio, basso costo; edge computing (il sensore pre-elabora il dato)
- **Cosa fa per il carbon farming**:
  - Genera il **dato a terra** continuo e georeferenziato — la "ground truth" che calibra modelli e satelliti: senza IoT, niente dMRV credibile
  - Misura diretta dei flussi (camere automatiche per CO₂/N₂O) e dei proxy del SOC (sonde spettroscopiche) → riduce i campionamenti manuali, il costo n.1 dell'MRV
  - Verifica oggettiva delle pratiche: il sensore documenta *quando* e *come* (irrigazione, lavorazioni) senza autodichiarazioni
- **Limiti**: manutenzione e calibrazione in ambiente ostile (fango, animali, furti); copertura di rete nelle aree rurali; rappresentatività spaziale (un sensore misura un punto, il campo è variabile); costo per ettaro ancora rilevante per le misure di flusso
- **Caso da citare**: reti di monitoraggio del suolo in progetti carbon europei; confronto costi campionamento tradizionale vs. sonda spettroscopica in continuo

> *Nota:* il remote sensing satellitare resta nella lezione come contesto (Parte 2) e rientra qui come "partner" dell'IoT: il satellite dà la copertura, il sensore a terra dà la verità di campo.

### 3.2 AI e piattaforme dMRV (25 min)
- **Come funziona**: machine learning addestrato su campionamenti a terra + dati satellitari + dati meteo/suolo → modelli che *stimano* il SOC e le emissioni dove non si campiona
- **Cosa fa per il carbon farming**:
  - Riduce drasticamente i campionamenti necessari (il costo n.1 dell'MRV)
  - Quantifica l'incertezza (fondamentale: i crediti vengono scontati in base all'incertezza della stima)
  - Piattaforme integrate: ingestione dati, modellazione, reporting automatico verso lo standard (Verra VM0042, Label Bas Carbone, futuro CRCF)
- **Limiti**: "garbage in, garbage out" — i modelli valgono quanto i dati di calibrazione; trasferibilità tra pedoclimi diversi; scatola nera vs. esigenza di verificabilità (qui si aggancia il tema della trasparenza → ponte verso la blockchain)
- **Caso da citare**: ecosistema europeo di piattaforme dMRV per il carbonio agricolo (es. Agreena, Soil Capital, eAgronom) — confrontare l'approccio di 2 piattaforme

### 3.3 Blockchain e registri digitali per i crediti di carbonio (25 min)
- **Come funziona** (senza tecnicismi eccessivi): registro distribuito, immutabilità, smart contract, token. Spiegarla come "notaio digitale condiviso"
- **Il problema che risolve**: il mercato volontario dei crediti soffre di doppio conteggio, scarsa tracciabilità, crediti "fantasma" → crisi di fiducia (citare le inchieste 2023 sui crediti REDD+)
- **Cosa fa per il carbon farming**:
  - Tokenizzazione del credito: ogni credito ha identità unica, storia tracciabile, ritiro (retirement) pubblico e verificabile
  - Smart contract: pagamento automatico all'agricoltore al verificarsi delle condizioni misurate dal dMRV → **qui chiudere il cerchio: il sensore misura → l'AI stima → la blockchain certifica e paga**
  - Trasparenza di filiera: chi compra il credito vede l'intera catena fino al campo
- **Limiti e onestà intellettuale**: la blockchain garantisce l'integrità del *dato registrato*, non la sua *veridicità* (problema dell'oracolo); consumo energetico (ormai marginale con proof-of-stake); rischio "blockchain-washing"; volatilità del mondo crypto vs. serietà del registro
- **Caso da citare**: registri tokenizzati (Toucan, Flowcarbon) e la reazione di Verra; in alternativa registri digitali "tradizionali" evoluti

---

## PARTE 4 — Chiusura e discussione (15 min)

1. **Sintesi visiva** (5 min): un'unica slide con la catena del valore digitale del carbon farming — *campo → sensore/satellite → AI → piattaforma dMRV → registro/blockchain → mercato*
2. **Messaggio finale** (5 min): la tecnologia non sostituisce l'agronomia né la fiducia — le rende scalabili. Il fattore limitante resta la qualità del dato a terra.
3. **Discussione/domande** (5 min). Domanda stimolo: "Vi fidereste di più di un credito verificato da un auditor umano o da un sistema dMRV automatizzato? Perché?"

---

## Riepilogo tempi

| Blocco | Durata |
|---|---|
| 1. Premessa e storia | 30 min |
| 2. Trend (generali → sostenibilità → carbon farming) | 50 min |
| Pausa | 10 min |
| 3. Focus tre tecnologie | 75 min |
| 4. Chiusura e discussione | 15 min |
| **Totale** | **180 min** |

## Note didattiche trasversali
- Ogni blocco apre con una domanda e chiude con un "take-away" di una frase.
- Mostrare dati e immagini reali: una scena Sentinel-2 della zona dove si tiene il corso vale più di dieci slide teoriche (EO Browser di Sentinel Hub è gratuito e usabile live in aula).
- Tenere un "parcheggio domande" per i temi blockchain/crypto, che tendono a far deragliare la discussione.
