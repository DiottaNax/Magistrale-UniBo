# Iconsulting – Riepilogo Azienda e seminario

## Chi è Iconsulting

Iconsulting è una società di consulenza italiana fondata nel **2001**, nata dall'ambiente della ricerca universitaria. La sua missione è aiutare grandi aziende e organizzazioni a prendere decisioni migliori attraverso i dati, con il motto _"Ignite the right decision through human potential"_.

Ha sede principale a **Bologna** e uffici a Milano, Roma e Napoli. Conta oltre **450 professionisti**, ha lavorato con più di **200 clienti** su oltre **2.500 progetti**, con un Net Promoter Score del **95%**.

### Settori serviti

Automotive, Banking e Insurance, Consumer Goods, Fashion, Life Science & Healthcare, Manufacturing, Retail, Telco/Media/Energy, Pubblica Amministrazione (centrale e locale), Servizi.

Tra i clienti principali figurano realtà come UniCredit, Generali, Prada, Barilla, Vodafone, Poste Italiane, Ducati, Technogym, Coop Italia, vari Ministeri italiani e molti altri.

### Servizi offerti

Advisory, Business Analytics, Big Data Platform, Machine Learning, Data Governance, Performance Management, Customer Data Platform, Location Analytics, Blockchain, Application Maintenance.

### Prodotto proprietario

**Indyco** – una suite di _Collaborative Business Analytics_ che funge da "Google Maps dei dati aziendali", consentendo all'IT di progettare sistemi analitici complessi e agli utenti di business di navigare il patrimonio informativo e supportare la Data Governance.

### Partner tecnologici

Oltre 20 partner tra cui Oracle, AWS, Microsoft, Databricks, Snowflake, Tableau, SAP, Informatica, IBM, Google Cloud, Qlik, SAS, e altri.

---

## Il seminario – Analisi What-If per il calcolo della marginalità economica sui clienti B2B

Il seminario è stato tenuto da **Tomas Tassinari**, Manager in Iconsulting dal 2016 (laurea in Ingegneria e Scienze Informatiche a Cesena), con quasi 10 anni di esperienza in azienda su 17 clienti e 10 settori diversi.

### Il progetto: Marginalità POS e Simulatore

Il caso reale presentato riguarda un cliente B2B operante nel settore dei **terminali POS** (dispositivi per pagamenti elettronici). Il modello di business è il seguente: l'azienda noleggia POS ai negozi (es. supermercati), i quali pagano un canone e commissioni proporzionali al volume di transazioni ("transato") generato dai clienti finali.

**Il problema di business:** l'azienda non aveva visibilità chiara sulla marginalità economica per singolo punto vendita (PDV) e non poteva simulare scenari alternativi di pricing.

### Le fasi del progetto

1. **Analisi dei requisiti** – Interviste con gli utenti di business per raccogliere le fonti dati (commissioni bilaterali, tecniche, bancarie, costi risorsa, commissioni interbancarie, ecc.) e produrre specifiche funzionali e di interfaccia.

2. **Progettazione e architettura** – Soluzione a tre strati:
   - _Sistemi sorgente_ → _DataWarehouse_ (ETL con Informatica PowerCenter su Oracle DB) → _Business Intelligence_ (Oracle BI) + _Web Application Simulatore_ (React + Flask)

3. **Implementazione** – Gestione del team con approccio "dividi et impera" per colmare gap di competenze, con formazione interna.

4. **UAT e Rollout** – Test di accettazione utente e deploy automatizzato.

### Il risultato: il Simulatore What-If

Lo strumento finale permette di:

- Visualizzare la **marginalità attuale (AS-IS)** di ogni punto vendita, scomponendo ricavi da commissioni sul transato e canoni di gestione terminali.
- **Simulare scenari alternativi (TO-BE)**: modificando le commissioni applicate (Merchant Fee per tipologia di carta: Credito, Debito, Commercial), il sistema ricalcola in tempo reale il guadagno/perdita atteso.
- Usare il **Simulatore Prospect**: per clienti potenziali (non ancora acquisiti), stimare la marginalità attesa basandosi su clustering e similarità con clienti esistenti, inserendo parametri come categoria merceologica, CAP, acquirer, scontrino medio.

### Change Management

Il progetto ha richiesto un attento lavoro di accompagnamento al cambiamento, attraverso il coinvolgimento degli utenti fin dalla fase di analisi, una fase pilota e sessioni di formazione. La presentazione sottolinea come, in pratica, le organizzazioni siano resistenti al cambiamento e come sia necessario un approccio graduale.

Riguardo al machine learning, è stato evidenziato un approccio incrementale: prima algoritmi "comprensibili" per costruire fiducia negli utenti, poi progressivamente modelli più complessi.

### Risultati ottenuti

- Adozione da parte di **50-60 utenti** della direzione centrale, poi estesa a tutte le filiali della rete commerciale.
- Unicità dell'informazione centralizzata nel DataWarehouse.
- Investimenti continuati in evolutive e raffinamento dello strumento.
- Alta soddisfazione di utenti, referenti IT e consulenti.

---

_Presentazione tenuta il 29 Ottobre 2025 presso l'Università di Bologna – Campus di Cesena._

---

# Trevi Group – Riepilogo seminario Digital 360°

## Chi è Trevi Group

Trevi Group è una società quotata alla Borsa di Milano dal 1999, specializzata nell'**ingegneria del sottosuolo**. Opera in circa 90 paesi attraverso 59 società e conta oltre 3.000 dipendenti, con ricavi totali di circa 663 milioni di euro (dati al 31.12.2024).

Il Gruppo si articola in due divisioni principali:

- **TREVI** – specialista in fondazioni profonde e lavori geotecnici (costruzioni e infrastrutture)
- **Soilmec** – attrezzature e servizi per fondazioni speciali

Il modello di business si basa su una sinergia continua tra le due divisioni: le esigenze cantieristiche di Trevi alimentano l'innovazione tecnologica di Soilmec, e viceversa, creando un vantaggio competitivo difficilmente replicabile.

---

## Il Dipartimento Digital Innovation & Technology

Il dipartimento IT è guidato dal CIO Paolo Calzi e si struttura in quattro aree applicative principali:

- HR Applications & IT Compliance
- AFC Applications (Finance)
- Supply Chain & Production Applications
- CRM & Special Applications

Il processo di lavoro segue un ciclo **Plan → Build → Run**, supportato da funzioni trasversali di consulenza, formazione, comunicazione e procurement.

---

## Oggetto del seminario

Il seminario, dal titolo **"Digital 360°: il nostro percorso di trasformazione digitale"**, ha trattato due temi principali:

### 1. Metodologia di trasformazione digitale

Trevi ha condiviso il proprio approccio alla gestione dei progetti IT, che comprende:

- **Selezione software e partner** tramite un processo strutturato (scouting → SW selection → approfondimenti → final report)
- **Governance di progetto** con SAL mensili e Steering Committee periodici
- **Metodologia di implementazione** in fasi: Analisi & Design → Configuration & Integration → Test & UAT → Transition (Go Live)
- **Formazione** con approccio "train the trainer" per i key user e corner online per gli utenti finali
- **Post-live** gestito tramite war room Teams e sistema di ticketing

L'architettura applicativa del Gruppo è evoluta da sistemi locali eterogenei verso un ecosistema integrato basato su **SAP S/4 HANA**, **Oracle HCM**, **MS Dynamics**, **Archiflow**, **ServiceNow** e altri sistemi collegati via API e webservice.

---

### 2. AI in Trevi Group – Due casi concreti

#### Caso A: AI Business Opportunities Validator (BOV.25)

Progetto di **innovazione del processo di Business Development**, presentato da Andrea Dellamore (AI Ambassador).

**Il problema:** il settore construction genera centinaia di annunci al giorno su progetti con tempi di maturazione pluriennali. Trevi doveva trovare un modo per identificare automaticamente le opportunità rilevanti per il proprio business geotecnico.

**La soluzione:** un sistema AI basato su LLM (OpenAI GPT-4.1o) arricchito con **RAG** (Retrieval-Augmented Generation) su un corpus tassonomico e ontologico delle tecnologie Trevi. Questo permette al modello di classificare i progetti e inferire la presenza di potenziali scopi geotecnici in modo molto più preciso rispetto a un LLM neutro (correlazione geotecnica passata dal 10-50% al 20-65% nelle categorie rilevanti).

**Il flusso risultante (AI-doped):**
`Announcement → AI filtering → Human review → Tender → Quote`

Il sistema è integrato in **RPA** e alimenta il **CRM** con una shortlist dinamica giornaliera. Il team umano esamina solo i progetti pre-candidati (approccio Human-in-the-Loop / HITL), classificandoli come _discarded_, _watchlisted_ o _circulated_ alle business unit.

**Sviluppi futuri:** stima della geologia del sito tramite open data NASA+Geostrat, e arricchimento con _situational awareness_ geopolitica sugli stakeholder coinvolti.

---

#### Caso B: Digitalizzazione del Ciclo Passivo con l'AI

Progetto per ottimizzare il processo di **gestione delle fatture passive**, rallentato dai ritardi nella registrazione dell'entrata merci nei cantieri.

**Il problema (As-Is):** il personale di cantiere genera ordini d'acquisto → il fornitore spedisce merce con DDT → il cantiere deve registrare manualmente l'entrata merci in SAP → solo allora l'amministrazione può abbinare e registrare la fattura. I ritardi nella registrazione generano un significativo backlog di fatture.

**La soluzione proposta (To-Be):** introduzione dell'AI nel processo per:

- **Estrarre automaticamente** i dati dai DDT dei fornitori e abbinarli all'ordine d'acquisto corrispondente
- **Generare workflow automatici** di pre-approvazione del ricevimento indirizzati al capo cantiere responsabile della WBS
- **Automatizzare la creazione** dell'inbound delivery e la registrazione dell'entrata merce in SAP dopo l'approvazione
- **Automatizzare la registrazione** della fattura passiva tramite abbinamento automatico con il ricevimento

I fornitori inviano il DDT a una distribution list; l'AI analizza il documento, precompila le informazioni essenziali e avvia il workflow verso il cantiere corretto, riducendo drasticamente il carico manuale e i tempi di elaborazione.

---

# Salesforce – Introduzione e Webinar Università di Bologna (2025)

**Data:** 13 novembre 2025  
**Relatori:** Danilo Pede (Senior Director, Professional Services), Gabriele Morrone (Lead Solution Engineer), Gianluca Squillace (Business Architect Director)

---

## Chi è Salesforce

Salesforce è la principale azienda al mondo nel campo del **CRM (Customer Relationship Management)**, fondata nel 1999. La sua missione è connettere le aziende con i propri clienti in un modo completamente nuovo, attraverso un'unica piattaforma integrata che serve marketing, vendite, commerce e servizio clienti con una visione condivisa del cliente.

**Alcuni numeri chiave:**

- Il 97% delle aziende Fortune 100 usa Salesforce
- Fatturato previsto FY26: ~41,3 miliardi di dollari
- Margine operativo non-GAAP FY26: 34,1%
- Oltre 62.700 clienti no-profit e istruzione superiore
- Donazioni complessive: 841 milioni di dollari; 10 milioni di ore di volontariato

**Impegni ESG:** Salesforce aderisce al modello "1% equity, 1% tempo, 1% prodotto" (Pledge 1%) e ha raggiunto la neutralità carbonica con il programma Agentforce Net Zero.

---

## Il prodotto principale: la Piattaforma Salesforce

La piattaforma è costruita su un'architettura **multi-tenant** e si articola in quattro strati principali:

1. **Data Model** – fondamenta dell'intero CRM: oggetti standard e custom, relazioni tra entità, gestione della sicurezza e degli utenti.
2. **Logic** – automazione dei processi tramite Flow Builder, Business Rules Engine e OmniStudio.
3. **Intelligence** – AI predittiva (scoring lead, previsioni, raccomandazioni) e AI generativa (email di vendita, riassunti di chiamate, risposte al servizio clienti, articoli di knowledge base).
4. **User Interface** – app configurabili per ruolo, dashboard e report, ottimizzati anche per mobile.

### Agentforce

La novità centrale del 2025 è **Agentforce**, la piattaforma di Salesforce per l'IA agentiva: agenti autonomi che operano in vendita, marketing, service, commerce, HR, IT e supply chain, orchestrati tramite MuleSoft Agent Fabric e integrati con Slack e Teams.

### Einstein Trust Layer

Il livello di sicurezza per l'IA include: recupero sicuro dei dati, mascheramento dei dati sensibili (PII, PCI), prompt defense, zero data retention sugli LLM esterni, rilevamento della tossicità e audit trail completo.

---

## Argomenti del Webinar

Il webinar si è articolato nelle seguenti sezioni principali:

### 1. Salesforce in action

Dimostrazione pratica della piattaforma e dei prodotti Agentforce in diversi contesti aziendali.

### 2. La piattaforma Salesforce – sotto il cofano

Approfondimento tecnico su multitenancy, data layer, automazione, intelligenza artificiale (predittiva e generativa) e sicurezza.

### 3. Come si affronta un progetto di trasformazione

Analisi degli attori e degli stakeholder coinvolti (IT, Marketing, Sales, Service), progettazione del data model, gestione dell'identità, integrazione con sistemi esterni (ERP, e-commerce, DWH), ciclo di vita dello sviluppo (ALM) e governance del progetto.

### 4. AI per il CRM – Trend di mercato

Panoramica sull'evoluzione dell'IA generativa (da ChatGPT nel 2022 agli agenti autonomi nel 2025), impatto sui modelli di business, cambiamento del ciclo di sviluppo software (Agentic SDLC), e sfide delle organizzazioni nell'adozione dell'IA. Citati dati da BCG, McKinsey, Stanford HAI e Gartner.

**Messaggi chiave su AI e lavoro:**

- Il 60% dei lavoratori prevede che l'IA cambierà il proprio lavoro nei prossimi 5 anni.
- I lavoratori con AI sostituiranno quelli senza AI, non l'AI stessa sostituirà gli umani.
- I ruoli si trasformeranno verso system thinking, business architecture, orchestrazione e prompt engineering.
- Le soft skill (pensiero critico, comunicazione, adattabilità) diventano sempre più strategiche.

### 5. Be a Trailblazer – Opportunità di carriera

Presentazione dell'ecosistema Salesforce per lo sviluppo professionale: la piattaforma **Trailhead** (oltre 5 milioni di learner), i percorsi di carriera (Administrator, Developer, Architect, Consultant, Designer, Data Analyst, ecc.) e le certificazioni riconosciute dal mercato.

---

## In sintesi

Il webinar ha offerto agli studenti dell'Università di Bologna una panoramica completa su cosa fa Salesforce, come funziona tecnicamente la piattaforma, come si gestisce un progetto di trasformazione digitale e quali sono le implicazioni dell'IA generativa per le aziende e per le carriere future nel settore tech.
