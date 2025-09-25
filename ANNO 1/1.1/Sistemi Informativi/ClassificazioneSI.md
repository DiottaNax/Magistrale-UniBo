# Sistemi Informativi

## Classificazione dei Sistemi Informativi

### SI e Aziende

Un'azienda è una **struttura di comando** che governa processi operativi finalizzati al raggiungimento di uno o più obiettivi predefiniti.

I SI supportano sia i **processi di governo** (SI direzionali e analitici), sia i **processi operativi** (SI operativi).

#### Catena del Valore di Porter

La catena del valore identifica le attività primarie e di supporto:

**Attività Primarie:**

- Gestione materie prime
- Trasformazione
- Marketing e vendita
- Distribuzione
- Postvendita

**Attività di Supporto:**

- Approvvigionamenti
- Sviluppo delle tecnologie
- Gestione delle risorse
- Infrastruttura

---

## Tipologie di Sistemi Informativi

### SI Operativi

Informatizzano processi volti all'**esecuzione** di attività o alla loro **programmazione**:

- Programmazione della fabbricazione e Fabbricazione
- Programmazione della distribuzione e Distribuzione
- Amministrazione
- Gestione del personale

#### Intensità Informativa

L'importanza dei SI operativi dipende dall'**intensità informativa** del settore:

- **Tecnologia di produzione**: settori che "vendono" informazioni (banche, assicurazioni, telecomunicazioni)
- **Tecnologia di processo**: quando il prodotto è materiale (aziende manifatturiere)

**Investimenti in tecnologia**: variano dall'1% del fatturato nelle manifatture semplici al 7% nelle aziende di telecomunicazioni.

**Matrice Intensità Informativa:**

|                              | **Bassa Intensità Processo**                    | **Alta Intensità Processo**                                                                      |
| ---------------------------- | ----------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| **Alta Intensità Prodotto**  | Aziende editoriali                              | Università e scuole<br>Banche e assicurazioni<br>Aziende telefoniche<br>Pubblica amministrazione |
| **Bassa Intensità Prodotto** | Industria del tabacco<br>Aziende manifatturiere | Aziende gas, elettricità<br>Grande distribuzione                                                 |

### SI Direzionali

Supportano il **processo decisionale** fornendo informazioni ai manager per aiutarli a decidere.

**Modello del Ciclo di Controllo:**

1. Definizione degli obiettivi
2. Attività operative
3. Controllo dei risultati
4. Definizione azioni correttive

**Caratteristiche distintive:**

- Si basano su **indici** (informazioni aggregate e riassuntive)
- Elaborazione **periodica** (non continua)
- Costruiti sopra i SI operativi da cui estraggono le informazioni di base

### SI Analitici

Supportano la **comprensione dei fenomeni di business**.

**Focus:**

- Prodotti
- Clienti
- Processi

**Funzionalità:**

- Profilazione clienti (abitudini e comportamenti)
- Storia del prodotto e monitoraggio affidabilità
- Utilizzo per beni durevoli

**Differenza con SI Direzionali:**

- **SI Direzionali**: fenomeni "interni" all'azienda
- **SI Analitici**: fenomeni "esterni" all'azienda

#### SI Analitici per Settori

| **Settore**              | **Numerosità Clienti**  | **Finalità di Analisi**                                                  |
| ------------------------ | ----------------------- | ------------------------------------------------------------------------ |
| Telefonia                | Oltre 10 milioni        | Profittabilità<br>Comportamento/preferenze                               |
| Grandi banche            | Oltre 1 milione         | Profittabilità                                                           |
| Aziende elettriche e gas | Da 100 mila a 1 milione | Profittabilità<br>Comportamento/preferenze                               |
| Pubblica amministrazione | Oltre 10 milioni        | Studi di settore<br>Segmentazione contribuenti<br>Individuazione evasori |
| Grande distribuzione     | Da 100 mila a 1 milione | Comportamento/preferenze                                                 |

---

## La Mappa dei SI

### Concetto di Modulo

Un **modulo** rappresenta un blocco di funzionalità software che supportano una fase di un processo aziendale, omogeneo per frequenza, attore e profilo di casi d'uso.

**Tipologie di Moduli:**

- **Orizzontali**: non variano al variare della tipologia aziendale
- **Verticali**: utilizzati in specifici settori produttivi (bancario, manifatturiero, chimico)

### Il Portafoglio Applicativo Aziendale

Rappresenta una mappa dei SI aziendali ottenuta incrociando:

- **Fasi del ciclo di trasformazione**
- **Tipologia delle attività** (pianificazione ed esecuzione)

#### Livelli di Pianificazione

**Analisi Strategica:**

- Previsione di mercato
- Monitoraggio trend tecnologici
- Informazioni esterne
- Processo variabile e destrutturato

**Pianificazione Annuale:**

- Dimensionamento volumi e attività
- Coordinamento operazioni
- Informazioni interne strutturate
- Flusso interfunzionale

**Programmazione Operativa:**

- Calcolo programmi di attività
- Controllo avanzamento
- Granularità: settimana-giorno, reparto-ordine

#### Attività di Esecuzione

**Flusso degli Ordini:**

- Elaborazione transazioni
- Automazione della manualità
- Grandi volumi di transazioni
- Tracciamento dell'ordine

**Flusso dei Materiali:**

- Registrazione eventi
- Guida movimentazione scorte
- Medi volumi di transazioni
- Tracciamento del materiale

**Flusso delle Operazioni:**

- Registrazione eventi
- Guida esecuzione operazioni
- Raccolta dati in tempo reale

#### Portafoglio Applicativo per Settore

**Aziende Chimiche e Siderurgiche:**

- Enfasi su manutenzione e supervisione controllo
- E-procurement per ricambi
- Supply chain management per coordinamento

**Aziende Telefoniche:**

- Importanza contatto cliente (CRM)
- Gestione rete complessa
- Processi: sviluppo prodotti → vendita → attivazione → fatturazione → post-vendita

---

## Smart Manufacturing (Industria 4.0)

### Architettura CIM (Computer Integrated Manufacturing)

Architettura multilivello a **5 livelli**:

1. **Sensors & Signals** - Processo produttivo
2. **PLC, CNC, RTU** - Sensing & Manipulating
3. **SCADA/HMI** - Monitoring
4. **MES** - Operation Management
5. **ERP** - Business Planning

**Benefici:**

- Riduzione scorte
- Riduzione tempo commercializzazione
- Aumento qualità prodotto
- Riduzione costi per maggiore efficienza

### Sistemi SCADA

**SCADA** (Supervisory Control and Data Acquisition) sono sistemi per monitorare e controllare grandi impianti industriali.

**Ambiti di Applicazione:**

- Grandi impianti industriali
- Telecomunicazioni
- Sistemi gestione acqua/energia (HERA)
- Sistemi produzione energia
- Raffinerie
- Trasporti e centri ricerca

#### Architettura SCADA

**Componenti:**

**Sensori e Attuatori:**

- Pressione, velocità, luminosità, umidità, temperatura, livello, distanza
- Valvole, pompe, motori

**Controllori:**

- **PLC** (Programmable Logic Controller): dispositivo programmabile che risolve logiche algoritmiche
- **RTU** (Remote Terminal Unit): unità terminale che esegue ordini, ripetitore intelligente

**Gateway:** raccolgono informazioni da PLC/RTU e le trasferiscono al sistema centralizzato

**Server:**

- **Front-end Server**: traducono dati in formato utilizzabile
- **SCADA Server**: funzionalità monitoraggio e gestione allarmi in tempo reale
- **Data Server**: memorizzazione storica dati per analisi

### Evoluzione verso Industria 4.0

**Tecnologie Chiave:**

- **Big Data e Analytics**
- **Autonomous Robots**
- **Simulation**
- **Horizontal and Vertical System Integration**
- **Industrial Internet of Things**
- **Cybersecurity**
- **Cloud Computing**
- **Additive Manufacturing**
- **Augmented Reality**

#### Internet of Things (IoT)

Connessioni digitali tra oggetti che diventano intelligenti comunicando dati su se stessi e accedendo a informazioni aggregate.

**Applicazioni:** domotica, medicina, energy, intrattenimento

#### Manufacturing Execution Systems (MES)

Gestiscono la fabbrica ricevendo ordini dall'ERP, raccogliendo informazioni dallo SCADA.

**Funzionalità:**

- Assegnazione risorse e stato
- Pianificazione operazioni
- Gestione qualità
- Analisi prestazioni
- Tracciamento prodotto

---

## Sistemi ERP

### Definizione

**ERP** (Enterprise Resource Planning): suite di moduli applicativi che supportano l'intera gamma dei processi aziendali.

**Moduli Core:**

- **Logistica**: gestione dati prodotti, pianificazione produzione, gestione materiali
- **Gestione Finanze**: gestione capitali, investimenti, controllo flussi economici
- **Gestione Risorse Umane**: personale, organigramma, tempo, paghe

### Paradigmi ERP

#### 1. Unicità dell'Informazione

**Vantaggi:**

- **Sincronizzazione dei dati** e dei processi
- **Assenza di ridondanza**
- **Tracciabilità aggiornamenti**
- **Affidabilità informazione aziendale**

#### 2. Estensione e Modularità

**Strategie di Implementazione:**

- **Incrementale**: acquisto progressivo moduli
- **One Stop Shopping**: un solo vendor
- **Best of Breed**: moduli di diversi vendor per diverse funzioni

#### 3. Prescrittività

I sistemi ERP incorporano la logica del processo gestionale. È necessario adattare i processi aziendali a quelli definiti nell'ERP.

**Vantaggi:**

- Processi basati su best practices
- Standardizzazione operazioni
- Razionalizzazione processi (BPR)

### ERP Allargati

**Moduli Aggiuntivi:**

- **PLM** (Product Lifecycle Management)
- **SCM** (Supply Chain Management)
- **CRM** (Customer Relationship Management)
- **E-procurement**

### Architettura ERP

Evoluzione da architetture client-server verso thin-client web enabled:

- **Presentation Server**: interfaccia utente
- **Application Server**: elaborazione applicazioni
- **Database Server**: gestione dati integrata

---

## Sistemi CRM

### Definizione

**CRM** (Customer Relationship Management): processo integrato per la gestione della relazione con la clientela, finalizzato a costruire relazioni personalizzate di lungo periodo.

**Il cliente diventa il focus centrale** della strategia commerciale.

### Tipologie CRM

#### CRM Operativo

Informatizza i canali di contatto con il cliente:

- **Presenza** (Sales Force Automation)
- **Voce** (Call Center)
- **Web** (Commercio Elettronico)
- **Corrispondenza** (E-mail)

#### CRM Analitico

Informatizza l'analisi della clientela per definire politiche di promozione e contatto.

#### CRM Direzionale

Permette al management di valutare la performance dell'azienda verso il cliente.

### Rilevanza CRM per Settore

**Fattori Determinanti:**

- **Numerosità della clientela**
- **Continuità e frequenza della relazione**

**Settori ad Alta Rilevanza:**

- Banche
- Compagnie telefoniche
- Poste
- Trasporti-Turismo

### Canali CRM

#### Presenza (SFA)

- Computer portatili per venditori
- Supporto ciclo vendita completo
- Raccolta ordini e informazioni visite

#### Voce e Corrispondenza

**Call Center:**

- Smistamento chiamate
- Servizi automatici self-service
- Multilocalizzazione trasparente
- Supporto operatori

#### Web

- **B2C**: Business-to-Customer (utenti finali)
- **B2B**: Business-to-Business (aziende partner)
- Vendita self-service 24/7
- Personalizzazione utente
- Click stream analysis

### Paradigma CRM

**Caratteristiche Distintive:**

- **Multicanalità**: cliente sceglie canale più conveniente
- **Completezza e unicità dati**: base dati comune
- **Catene di servizio**: integrazione front-end e back-end

---

## Considerazioni Finali

### Industria 4.0 vs Industria 0.4

Nonostante le promesse dell'Industria 4.0, spesso esiste un gap tra aspirazioni tecnologiche e realtà implementativa. Molte aziende possono ottenere valore significativo anche con sistemi di Business Intelligence descrittiva:

- Calcolo OEE (Overall Equipment Effectiveness)
- Analisi funzionamento macchinari
- Analisi consumo tool

La distanza tra la **forma mentis** di un responsabile di fabbrica e di un **analista dati** rimane una sfida importante nell'implementazione di soluzioni avanzate.
