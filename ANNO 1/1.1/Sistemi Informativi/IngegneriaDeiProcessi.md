# Sistemi Informativi

**Prof. Matteo Golfarelli**  
_Alma Mater Studiorum - Università di Bologna_

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

## L'Innovazione nei SI

### Rincorrere l'Innovazione Tecnologica

#### La Legge di Martec (2013)

Nella maggior parte dei processi innovativi sono le **persone e i processi** a frenare l'innovazione a causa dell'avversione all'innovazione e alla **Legge di Martec**.

**Martec's Law**: La tecnologia cambia esponenzialmente (veloce), mentre le organizzazioni cambiano logaritmicamente (lento).

Questo fenomeno può determinare un **senso di inadeguatezza** con conseguente avversione all'innovazione tecnologica.

#### Origine della Legge di Martec

**Legge di Moore (1965)**: Il numero di transistor su un chip raddoppia circa ogni due anni, con conseguente crescita esponenziale della potenza di calcolo e diminuzione dei costi.

**Law of Accelerating Returns di Ray Kurzweil (2001)**:

- **Crescita Esponenziale**: il progresso tecnologico raddoppia a intervalli specifici
- **Sistemi Auto-Amplificanti**: ogni innovazione accelera lo sviluppo successivo
- **Convergenza delle Tecnologie**: interazione crescente tra diversi campi scientifici

#### Strategie per l'Innovazione

Le aziende devono:

- **Prioritizzare** le innovazioni da adottare
- **Diventare più agili** e abituarsi al cambiamento continuo
- **Adottare cambiamenti rivoluzionari**: revisione di sistemi, processi o strutture per allinearsi alla curva esponenziale dei progressi tecnologici

---

## Il Ciclo dell'Innovazione

### Modello di Deming

_"Nella storia di un'azienda non esistono momenti in cui non si discuta di come cambiare il modo di operare e interagire con il resto della società"_

Il **ciclo di Deming** sintetizza la logica per gestire il ciclo di innovazione:

1. **Pianificazione**
2. **Attuazione**
3. **Verifica**
4. **Intervento**

Il termine "ciclo" enfatizza la **ripetitività** delle fasi che si devono continuamente ripetere durante tutta la vita dell'azienda.

### Fase di Pianificazione

- **Formalizzazione delle strategie** in termini di servizio e utilizzo delle tecnologie
- **Scelta delle priorità** nell'attuazione degli interventi di automazione
- **Validazione dei progetti** da attivare basata su priorità e vincoli di bilancio
- **Definizione degli impegni** e delle risorse necessarie
- **Stesura del documento di piano** e definizione del budget e responsabilità

### Fase di Realizzazione

- **Elaborazione di studi di fattibilità** per progetti che necessitano approfondimento
- **Definizione di progetti esecutivi** e piani operativi
- **Acquisizione di prodotti e servizi** dal mercato
- **Realizzazione dei progetti**
- **Conduzione operativa** dei sistemi con erogazione servizi e manutenzione

### Fase di Verifica

- **Gestione dei progetti** nelle loro varie componenti
- **Raccolta di informazioni** sullo stato dei processi di servizio
- **Diagnosi di servizi e processi** per identificare problemi e cause
- **Raccolta informazioni** sui sistemi informativi automatizzati
- **Diagnosi della risorsa informazione** in termini di qualità delle basi informative
- **Diagnosi dei sistemi informatici** in termini funzionali, architetturali ed economici

### Fase di Intervento

- **Elaborazione degli interventi** di reingegnerizzazione dei processi di servizio
- **Individuazione di iniziative** di reingegnerizzazione dei sistemi informatici

---

## Definizione degli Obiettivi

### Piano di Informatizzazione

Per assicurare il raggiungimento degli obiettivi è necessario che questi vengano **individuati esattamente** e **formalizzati** stabilendo responsabilità, tempi e priorità.

#### Piano Strategico (3-5 anni)

- **Obiettivi strategici** dell'informatizzazione
- **Architetture tecnologiche e applicative** come quadro di riferimento
- **Progetti di grande rilievo** con elevati tempi di realizzazione

#### Piano Operativo (annuale)

- Definisce in dettaglio gli **interventi previsti** dal piano strategico per l'esercizio in corso

#### Aggiornamento dei Piani

- **Elementi correttivi** aggiunti a ogni piano operativo che incidono sul piano strategico
- **Piano strategico a scorrimento** prodotto annualmente (approccio delle PA)

### Approcci Top-Down vs Bottom-Up

#### Top-Down

**Caratteristiche:**

- Parte dagli **obiettivi strategici** dell'organizzazione
- Maggiormente **innovativo e discontinuo**
- Permette **mutamenti radicali**
- Causa **maggiori tensioni** e rischi organizzativi

#### Bottom-Up

**Caratteristiche:**

- Parte dalle **indicazioni delle unità organizzative**
- Maggiormente **conservativo**
- Difficilmente produce **innovazione radicale**
- **Scarsi rischi** realizzativi

#### Approccio Misto (Pratica Comune)

1. Individuazione e diffusione delle **strategie generali**
2. Richiesta alle unità di elaborare **proposte specifiche** coerenti
3. **Integrazione delle proposte** con verifica coerenza globale
4. Definizione **interventi infrastrutturali** e piano finale

---

## Il Percorso di Adozione nei Sistemi Informativi

### Principi Fondamentali

Il percorso di digitalizzazione è **incrementale** e raramente permette di saltare dei passaggi.

È **rischioso, costoso e inutile** adottare soluzioni avanzate senza aver completamente sfruttato quelle semplici.

#### Ostacoli Comuni

**I manager non sono pronti:**

- Non hanno il mindset giusto

**I dati non sono pronti:**

- Non sono di qualità sufficiente

**I processi non sono pronti:**

- Non sono definiti per appoggiarsi ai dati e reagire a essi

> _Dubitate dei consulenti che offrono analisi avanzate se la vostra azienda sfrutta a malapena un foglio Excel_

### Creare Aziende Data-Driven

Il termine **aziende data-driven** si riferisce ad aziende in cui le decisioni e i processi sono supportati dai dati:

- Le **decisioni si basano** su conoscenze quantitative piuttosto che qualitative
- I **processi e le conoscenze** sono una risorsa dell'azienda e non vanno persi se i manager cambiano

> _La differenza tra una decisione basata sui dati e una buona decisione è un buon manager_

#### Requisiti per la Trasformazione

L'adozione di una mentalità basata sui dati comporta:

- **Creare una cultura** dei dati
- **Cambiare la mentalità** dei manager
- **Cambiare i processi**
- **Migliorare la qualità** di tutti i dati

#### Le Tre Dimensioni della Digitalizzazione

Il percorso coinvolge tre dimensioni principali con obiettivi intermedi raggiungibili:

**Digital Culture:**
_Abbiamo le persone giuste per guidare i processi e sfruttare i risultati?_

**Data Quality & Quantity:**
_I processi sono completamente digitalizzati e producono dati affidabili?_

**Technological Infrastructure:**
_L'infrastruttura tecnologica è appropriata per supportare raccolta e analisi dei dati?_

---

## Approcci al Miglioramento

### Miglioramento Incrementale: Occidentale vs Giapponese

#### Approccio Occidentale

- **Miglioramento discontinuo**
- Si ripete ogni anno con salti in avanti
- Incrementale: grandi cambiamenti periodici

#### Approccio Giapponese

- **Miglioramento continuo (Kaizen)**
- Lavoro costante sull'innovazione, approccio settimanale
- Crescita lineare e costante

### Perché il Miglioramento Incrementale Non Basta

Il gap tra **azienda leader** e la **vostra azienda** può continuare ad ampliarsi nonostante gli sforzi di miglioramento continuo.

La **percezione del valore da parte del cliente** cresce più velocemente di quanto l'azienda riesca a migliorare, rendendo necessari **salti qualitativi** oltre al miglioramento incrementale.

---

## Considerazioni Finali

### Industria 4.0 vs Industria 0.4

Nonostante le promesse dell'Industria 4.0, spesso esiste un gap tra aspirazioni tecnologiche e realtà implementativa. Molte aziende possono ottenere valore significativo anche con sistemi di Business Intelligence descrittiva:

- Calcolo OEE (Overall Equipment Effectiveness)
- Analisi funzionamento macchinari
- Analisi consumo tool

La distanza tra la **forma mentis** di un responsabile di fabbrica e di un **analista dati** rimane una sfida importante nell'implementazione di soluzioni avanzate.

# Business Process Reengineering (BPR)

## Definizione e Origini

Il Business Process Reengineering (BPR) nasce come **completo ripensamento e radicale ridisegno dei fondamentali processi di un'organizzazione** alla luce delle potenzialità offerte dai nuovi strumenti informatici.

### Caratteristiche Principali

- L'accento è sulla **discontinuità**
- Punta al **salto nelle prestazioni**
- Si basa sulla **completa assenza di vincoli di riprogettazione**

### Origini Storiche

Il concetto di BPR nasce agli inizi degli anni '90 per impulso di **Michael Hammer**, professore di informatica del MIT, che affermava:

> "It is time to stop paving the cow paths. Instead of embedding outdated processes in silicon and software, we should obliterate them and start over. We should 'reengineer' our businesses: use the power of modern information technology to radically redesign our business processes in order to achieve dramatic improvements in their performance."

## I Processi Aziendali

### Definizione di Processo

Un **processo** è un insieme delle attività tra loro interrelate, finalizzate alla realizzazione di un risultato definito e misurabile che contribuisce al raggiungimento della missione dell'azienda.

**Input** → **Processo** → **Output** → **Cliente**

### Il Cliente

Il **cliente** è la persona o gruppo che richiede o usa un prodotto o servizio realizzato tramite il processo. Il cliente può essere:

- **Interno** all'azienda
- **Esterno** all'azienda

Ogni output può avere molti clienti e viceversa.

### Elementi Centrali

- Il processo e la sua "manutenzione" diventano gli elementi centrali del ciclo di innovazione dei SI
- Primo compito del progettista è descrivere e classificare i processi
- Particolare rilevanza hanno le **classificazioni normative** (best practices)

## Cos'è il Business Process Re-engineering

Il BPR è la **completa revisione dei processi aziendali** al fine di massimizzarne il valore derivante dalle singole componenti, attraverso interventi sia di:

- **Riduzione dei costi**
- **Massimizzazione dell'efficacia**

Il BPR può essere innescato da un **aggiornamento tecnologico**.

### Obiettivi del BPR

1. **Rapidità dei tempi di ciclo**
2. **Zero difetti**
3. **Eccellenza nel servizio**
4. **Produttività World-Class**

## Gli Approcci di Miglioramento

Il Business Process Reengineering permette di realizzare **"il salto di qualità" (Breakthrough)**, distinguendosi da:

- **Miglioramento continuo**: Progressi incrementali graduali
- **Miglioramento discontinuo**: Salti qualitativi periodici
- **BPR**: Salti qualitativi drastici e radicali

## Le Varie Modalità di Reingegnerizzazione

Le modalità variano in funzione dello **scopo** e dell'**ampiezza del cambiamento**:

### 1. Streamlining (Approccio Incrementale)

- **Ambito**: Processo/Funzione
- **Obiettivo**: Riduzione costi/Semplificazione
- **Focus**: Pianificare il presente

**Caratteristiche**:

- Modifica delle sequenze
- Semplificazione delle attività
- Automatizzazione delle attività
- Ridefinizione di input ed output
- Bilanciamento dei carichi di lavoro

### 2. Business Process Reengineering (Approccio Radicale sui Processi)

- **Ambito**: Business Unit/Prodotto/mercato
- **Obiettivo**: Miglioramento Servizi
- **Focus**: Pianificare il futuro a parità di business

**Caratteristiche**:

- Eliminare e combinare con altri processi
- Ricostruire da zero
- Introdurre competenze completamente nuove
- Implementare tecnologie avanzate
- Ridisegnare il sistema premiante

### 3. Enterprise Transformation (Approccio Radicale sul Business)

- **Ambito**: Azienda/Gruppo settore
- **Obiettivo**: Riposizionamento strategico/Nuove linee di business
- **Focus**: Pianificare il business

**Caratteristiche**:

- Eliminare/sviluppare combinazioni prodotto/mercato
- Sviluppare alleanze strategiche
- Ribilanciare il portafoglio di business
- Riallineare i processi di supporto

## Fasi del BPR

### 1. Identificazione dei processi da reingegnerizzare

- **Descrivere i processi**
- Identificazione del breakthrough
- Analisi dei tempi di ciclo
- Analisi della creazione del valore

### 2. Definizione delle priorità di intervento

- Analisi di Pareto (sulla base del loro impatto)

### 3. Reingegnerizzazione dei processi

- Rimuovere le barriere alla performance

### 4. Implementazione del cambiamento

### 5. Istituzionalizzazione delle misure

- Per il miglioramento continuo

## Descrivere i Processi

### Scomposizione Gerarchica

La scomposizione dei processi avviene per successivi livelli di approfondimento:

1. **Macroprocesso**: Catena del valore di Porter

   - Utile nelle fasi iniziali per strutturare l'analisi

2. **Processo**: Operazioni svolte dall'azienda a livello dettagliato

   - Es: "Sviluppo prodotti" → "Concept", "Pianificazione", "Progettazione", "Prototipazione", "Test", "Ingegnerizzazione"

3. **Fase**: Modo in cui un processo è implementato

   - Es: "Progettazione" → "Sviluppo specifiche", "Gestione concurrent engineering", "Realizzazione value engineering"

4. **Attività**: Livello adottato nello studio dei processi
   - Determinate scomponendo le fasi secondo logica sequenziale

### Variabili di Progettazione dei Processi

1. **Flusso delle attività**

   - Sequenza attraverso cui il processo è svolto
   - Modellabile con Activity Diagram (UML)

2. **Organizzazione del processo**

   - Suddivisione operativa del lavoro
   - Struttura di coordinamento e controllo
   - Modellabile con Linear Responsibility Charting (LRC)

3. **Competenze delle risorse umane**

   - Condizione fondamentale per la trasformazione tecnologica

4. **Sistema di misurazione e controllo delle prestazioni**
   - Key Performance Indicator (KPI)
   - Balanced Scorecard

## Linear Responsibility Charting (LRC)

Determina una **visione tabellare della responsabilità organizzativa** che integra l'organigramma specificando il ruolo delle varie strutture nel processo.

### Etichette di Ruolo

- **D** = Decide, autorizza, ratifica
- **E** = Esegue
- **A** = Partecipa a tempo parziale, fornisce assistenza
- **I** = È sistematicamente informato

## Le Risorse Umane

### Sfide Principali

- Le risorse umane determinano la differenza tra risultato effettivo e massimo teoricamente possibile
- Le tecnologie innovative richiedono figure professionali spesso non esistenti in azienda
- Il reperimento può essere costoso e complesso

### Problemi della Formazione

- Gli utenti devono superare l'avversione al cambiamento
- I vantaggi non sono subito evidenti
- Rischio di introdurre cambiamenti superiori alle capacità di adattamento

## Key Performance Indicator (KPI)

### Definizione

Un KPI è un **indicatore quantificabile dell'efficacia e/o dell'efficienza** di un processo o sottoprocesso.

### Caratteristiche dei KPI

- **Quantificabile**
- **Rilevabile**
- **Correlato con l'obiettivo di business interno di processo**

### Proprietà dei KPI

1. **Significatività**: Collegamento con gli obiettivi strategici
2. **Controllabilità**: Misurazione di risultati influenzabili
3. **Semplicità**: Facilità concettuale, pochi indicatori
4. **Misurabilità**: Disponibilità e affidabilità dei dati
5. **Equilibrio**: Collegamento tra indicatori tecnici (ex-ante) e di risultato (ex-post)

### Tipi di Indicatori

- **Indicatori di risultato**: Misurano la performance a un momento dato
- **Indicatori tecnici**: Misurano attività che influenzano la performance

### Mappa degli Indicatori

Per ogni processo deve essere definita una mappa che specifichi:

- **Fenomeno da misurare**
- **Obiettivi**
- **Misure**
- **Stakeholder**
- **Sorgente dati**
- **Formulazione**

## Overall Equipment Effectiveness (OEE)

L'OEE è il **principale KPI per misurare la capacità di produzione** di un'azienda manifatturiera, molto usato nella Lean Manufacturing.

### Formula

**OEE = Availability × Performance × Quality**

### Componenti

- **Availability [0;1]**: Percentuale di tempo lavorato rispetto al tempo disponibile
- **Performance [0;1]**: Percentuale di pezzi effettivamente lavorati rispetto ai pezzi teoricamente lavorabili
- **Quality [0;1]**: Rapporto percentuale dei pezzi conformi sul totale dei pezzi prodotti

### Requisiti per il Calcolo

Il calcolo dettagliato/automatico dell'OEE richiede sistemi **SCADA** e **MES**.

## Visualizzazione di KPI

### Tecniche di Visualizzazione

- **Tabelle con codici colore**: Per confronti rapidi tra performance
- **Scatter plot**: Per evidenziare trend di miglioramento/peggioramento
- **Bersaglio**: Per performance su gruppi omogenei/disomogenei di KPI
- **Pentagramma**: Per performance di processo nel tempo

### Esempio: Indicatori di Sant'Anna

Sistema di valutazione delle performance della sanità pubblica con centinaia di indicatori organizzati in categorie, nato nel 2005 in Toscana ed esteso ad altre Regioni nel 2008.
