# Linguaggi, Compilatori e Modelli Computazionali

**Anno accademico 2025-2026**

**Docente:** Prof. Mario Bravetti  
**E-mail:** mario.bravetti@unibo.it

**Assistente:** Dott. Lorenzo Bacchiani  
**E-mail:** lorenzo.bacchiani2@unibo.it

## Orario lezioni

- **Martedì** 9 – 12, Aula 2.8
- **Mercoledì** 9 – 12, Aula 2.4
- **Giovedì** 13 – 17, Laboratorio 3.3 (inizio effettivo ore 13)

# Motivazione

## Linguaggio di programmazione

Strumento per descrivere in modo rigoroso come risolvere "problemi", in modo tale che questi possano poi essere risolti da un esecutore automatico.

Un linguaggio di programmazione non si discosta dal linguaggio naturale che serve per la comunicazione di concetti ad altre persone che possono capirli.

Uguale il lingiaggio di programmazione comunica con il computer attraverso specifici:

- Lessico: parole
- Sintassi: frasi
- Semantica

Ma...

- Cos'è un esecutore automatico? Il PC ha un esecutore automatico che consente di elaborare il linguaggio, potrebbe essere CPU+chiamate a OS oppure una JVM nel caso di Java.

Un personaggio che verrà nominato a riguardo è Noam Chomsky che fece teoremi matematici per la creazione di generazioni di compilatori automatici dando delle regole di sintassi e lessico.

## Perché studiare queste cose?

- Non rimanere dei "passivi" utilizzatori
- Capire cosa sta dietro all'implementazione di un linguaggio
- Domain-specific languages
- Model-driven software development
- Model checking per controllare le logiche temporali evitanto dead lock o simili.

## Compilatore

**Parser** + **generazione codice oggetto**

Compilare vuol dire 'trasformare'.
Il compilatore è un programma che prende codice sorgente e, una volta che ha digerito tutto produce del codice oggetto che può essere eseguito.

## Generazione automatica del codice del parser/compilatore

Per un nuovo linguaggio tramite **approccio dichiarativo**:

- **Lessico:** espressioni regolari (o automi a stati finiti)
- **Sintassi:** grammatiche, es. EBNF (o automi a pila)

### Esempio di automi: Automi a stati finiti

Modello per descrivere situazioni di calcolo in cui si **consumano informazioni una alla volta**, e durante la consumazione si devono memorizzare **quantità finite di informazioni**.

Usati in:

- Software per la progettazione di circuiti digitali
- Analizzatori lessicali di un compilatore
- Ricerca di parole chiave in un file o sul web
- Software per verificare sistemi a stati finiti, come protocolli di comunicazione

## Esempi

### Interruttore on/off

```

```

### Riconoscimento della stringa "then"

```

```

---

# Alan Turing (1912-1954)

Il matematico senza il quale nessuno starebbe studiando questa materia oggi. La sua rivoluzione è data dal programma della macchina di Turing attraverso un modello matemtico che rappresenta tutto ciò che è possibile risolvere con un computer.

### Macchina di Turing

Modello matematico di un semplice **esecutore automatico/CPU** (automa con memoria ausiliaria).

### Tesi di Turing-Church

Ogni problema calcolabile da un algoritmo (o meglio, più in generale, tramite una procedura anche infinita) può essere risolto da una **Macchina di Turing**

---

# Algoritmi e Calcolabilità

Algoritmo e procudure hanno significati differenti. La procedura è simile ad uno pseudocodice che potrebbe anche non terminare mentre gli algorimti sono procedure che hanno **sempre un termine**.

_Secondo voi gli algoritmi che posso scrivere **dipendono dal linguaggio** che uso/un nuovo linguaggio che mi posso creare?_
No, a patto che il linguaggio abbia almeno la potenza minima per essere Turing equivalente.

## Tutti i problemi sono calcolabili?

Secondo voi tutti i problemi (es. le funzioni ℕ → ℕ) sono calcolabili da un algoritmo/Macchina di Turing?
Le funzioni ℕ → ℕ non sono enumerabili e sono un'infinità continua.
Un programma è un file di testo ed è un'infinità enumerabile.
--> quindi non possono essere risolte da un algoritmo.

### Esempi di problemi non calcolabili (indecidibili)

(Non risolvibili algoritmicamente):

- IDE con la possibilità di capire la **raggiungibilità** di una certa istruzione in un qualsiasi programma dato che è matematicamente dimostrato non essere risolvibile. La complessità è data dal fatto di non capire se un programma si arresta o meno prima di una specifica istruzione.
- **Soddisfacibilità** di formule della logica dei predicati

---

# Modelli Computazionali

- Superamento del modello puramente funzionale (Macchine di Turing)
- Rappresentazione di sistemi distribuiti/concorrenti portando a **multipli programmi comunicanti tra loro**

### Esempio: protocollo per commercio elettronico

Eventi permessi:

1. Il cliente può **pagare** (pay) il negozio (= spedire soldi "elettronici" al negozio)
2. Il cliente può **cancellare** (cancel) i soldi (come bloccare un assegno)
3. Il negozio può **spedire** (ship) la merce al cliente
4. Il negozio può **prendere** (redeem) i soldi (come riscuotere un assegno)
5. La banca può **trasferire** (transfer) i soldi al negozio

### Commercio elettronico - Il protocollo per ogni partecipante

I diversi componenti comunicano nel momento in cui le transizioni hanno nomi uguali.

### (a) Store

```

```

### (b) Customer

```

```

### (c) Bank

```

```

---

# Logiche temporali

Un tool automatico poi va a creare l'intero sistema come automa andando a seguire tutti i percorsi e identificando quelli problematici.
Ad esempio: quando un Customer effettua la cancellazione dell'ordine lo store non viene avvisato.

### Model checker

Strumenti che verificano se **proprietà espresse tramite logiche temporali** valgono oppure no.

Se non valgono forniscono **controesempi** (computazioni che non soddisfano la proprietà).

**Esempio:** `pay,ship,cancel` è un controesempio per la proprietà precedente

---

# Contenuti del corso

## Linguaggi formali e Automi

- Automi a stati finiti, espressioni regolari, grammatiche libere, automi a pila, Macchine di Turing, calcolabilità

## Compilatori

- Analisi lessicale, analisi sintattica, analisi semantica, generazione di codice

## Logica di Base

- Logica delle proposizioni e dei predicati

## Modelli computazionali

- Specifica di sistemi tramite sistemi di transizione, logiche temporali per la specifica e verifica di proprietà dei sistemi (model checking), sistemi concorrenti (algebre di processi e reti di Petri)

---

# Laboratorio

**Parte integrante del corso:**

## Supporto alla parte teorica usando tool specifici

### Prime settimane

- **JFLAP 7.1:** http://www.jflap.org  
  (automi/grammatiche/espressioni regolari)

### Tool per model checking

- **Tina 3.8.0:** http://projects.laas.fr/tina  
  (model checking di sistemi di transizione e reti di Petri)
- **LTSA 3.0:** http://www.doc.ic.ac.uk/ltsa  
  (sistemi di transizione definiti tramite algebre di processi)

### Ambiente di sviluppo per parser/compilatori

- **IntelliJ** esteso con plug-in **ANTLRv4**, ultima versione 1.24
- **Generatore ANTLR:** http://www.antlr.org/

---

# Libri di testo

## J. E. Hopcroft, R. Motwani e J. D. Ullman

**Automi, linguaggi e calcolabilità**  
Addison-Wesley, Terza Edizione, 2009. Cap. 1–9

## A. V. Aho, M. S. Lam, R. Sethi e J. D. Ullman

**Compilatori: principi tecniche e strumenti**  
Addison Wesley, Seconda Edizione, 2009. Cap. 1–5

## M. Huth e M. Ryan

**Logic in Computer Science: Modelling and Reasoning about Systems**  
Cambridge University Press, Second Edition, 2004. Cap. 1–3

---

# Esame

## Scritto: 27 punti

- **3 appelli** sessione invernale (Gennaio e Febbraio)
- **3 appelli** sessione estiva (Giugno, Luglio e Settembre)

_Il voto dello scritto vale solo nell'ambito della sessione._

## Orale di progetto: 7 punti (facoltativo)

### Realizzazione di un compilatore

- Per un semplice linguaggio di programmazione funzionale object-oriented, chiamato **FOOL**
- Estensione del compilatore di base realizzato in laboratorio

### Modalità

- Progetto da svolgersi **singolarmente** o in **gruppo max 4 persone**
- Può essere effettuato **parzialmente** (anche solo una estensione minimale della versione fatta in laboratorio)
- **Discussione progetto** su appuntamento con tutto il gruppo (dopo lo scritto, entro l'inizio della sessione successiva)
