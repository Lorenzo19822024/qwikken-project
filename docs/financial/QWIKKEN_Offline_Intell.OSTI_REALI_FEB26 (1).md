**QWIKKEN — Offline Intelligence,** **Online Delivery**

**Architettura di Pre-Generazione Artefatti per** **l’Ottimizzazione dei Costi AI**

**Rev. 2.0 — Prezzi Reali Febbraio 2026**

**Documento Integrativo al SOCRATES 2.0**

**18 Febbraio 2026**

*Synthetic Data S.r.l. — Confidenziale* **CHANGELOG**

**Rev. **

**Data**

**Modifiche**

Documento originale. Architettura 3 strati 12 Feb

1.0

\(Fabbrica/Bibliotecario/Professore\). Stime costi basate su prezzi 2026

stimati. 

Aggiornamento con prezzi reali Google feb 2026. Introduzione 4°

18 Feb

2.0

strato \(Gemini 3 Flash\). Scenario Pilot Zero-Cost per CEPO

2026

Multiversity. Ricalcolo COGS completo. 

**1. EXECUTIVE SUMMARY**

La Rev. 2.0 di questo documento aggiorna l’architettura Offline Intelligence, Online Delivery con i prezzi reali dei modelli Google a febbraio 2026, introduce un quarto strato architetturale \(Gemini 3 Flash\) e include uno scenario di Pilot a costo quasi-zero per la demo CEPO Multiversity. 

**Risultato chiave:** il COGS per studente scende da €40 \(architettura attuale\) a **€15-19 con** **la nuova architettura a 4 strati**, grazie alla combinazione di pre-generazione offline, Batch API al 50% di sconto, Context Caching al 90% di riduzione, e Gemini 3 Flash come strato intermedio. 

**Arch. **

**Rev 1.0 \(3**

**Rev 2.0 \(4**

**Delta vs**

**Metrica**

**Attuale**

**strati\)**

**strati\)**

**Attuale**

COGS Inferenza /

€26.00

€12.00

€6.50-9.00

−65-75%

studente / anno

**Arch. **

**Rev 1.0 \(3**

**Rev 2.0 \(4**

**Delta vs**

**Metrica**

**Attuale**

**strati\)**

**strati\)**

**Attuale**

COGS Totale / studente

€40.00

€27.10

€15.50-19.00

−52-61%

/ anno

Margine Lordo

60%

73%

81-85%

\+21-25pp

% traffico su Pro

15%

15-20%

3-5%

−10-12pp

\(runtime\)

% traffico su Flash 3

—

—

10-15%

Nuovo strato

\(runtime\)

% servito da artefatti

0%

70-80%

75-85%

\+75-85pp

pre-generati

Costo Fabbrica \(Batch

—

€0.10

€0.04-0.06

−40-60%

API\)

**2. PREZZI REALI: Listino Google Febbraio 2026**

**2.1 Listino Modelli Google \(Febbraio 2026\)** **Input /**

**Output /**

**Context**

**Modello**

**Ruolo in QWIKKEN**

**1M tok**

**1M tok**

**Window**

Gemini 2.0

Bibliotecario \(opzione

$0.10

$0.40

1M tokens

Flash-Lite

economy\)

Gemini 2.0

$0.10

$0.40

1M tokens

Bibliotecario \(default\)

Flash

Gemini 2.5

Bibliotecario

$0.30

$2.50

1M tokens

Flash

\(reasoning ibrido\)

Gemini 3 Flash

**Assistente Senior**

$0.50

$3.00

1M tokens

Preview

**\(NUOVO\)**

Gemini 2.5 Pro

$1.25

$10.00

1M tokens

Professore \(standard\)

Gemini 3 Pro

$2.00

$12.00

1M tokens

Professore \(top tier\)

Preview

**2.2 Sconti Strutturali Confermati** **Applicazione in**

**Sconto**

**Meccanismo**

**Riduzione**

**QWIKKEN**

Processamento

-50% su tutti i

LA FABBRICA: tutta la

Batch API

asincrono

modelli paid

pre-generazione

Context

Cache del prefix di

-90% sui token di

BIBLIOTECARIO \+

Caching

contesto

input cachati

PROFESSORE

Context

Mantenimento cache $1-4.50 / 1M tok Caching

Costo marginale

in memoria

/ ora

Storage

**Applicazione in** **Sconto**

**Meccanismo**

**Riduzione**

**QWIKKEN**

Free Tier \(AI

Accesso gratuito con 100% gratis \(15

PILOT: primi 200-500

Studio\)

rate limit

RPM, 1K RPD\)

studenti

**Insight critico:** il Batch API al 50% di sconto rende la Fabbrica 2x più economica di quanto stimato nella Rev. 1.0. Con Gemini 2.5 Pro in batch, il costo di pre-generazione scende a 0.625/5.00 per milione di token — circa €60 per un intero corso di 200 Unità Concettuali. 

**3. ARCHITETTURA REV 2.0: Quattro Strati** La principale innovazione della Rev. 2.0 è l’introduzione di un quarto strato: l’Assistente Senior, basato su Gemini 3 Flash. Questo modello, rilasciato a fine 2025, offre intelligenza di livello frontier a un prezzo 4x inferiore al Pro, creando un buffer naturale tra il Bibliotecario economico e il Professore costoso. 

**Modello**

**Costo**

**Costo**

**Quando**

**%**

**Strato**

**Nome**

**AI**

**In/1M Out/1M**

**Opera**

**Interazioni**

Gemini

0%

Offline

1

**LA FABBRICA**

2.5 Pro

$0.625 $5.00

\(produce

\(batch\)

\(Batch\)

artefatti\)

Gemini

**IL**

Runtime

2

2.0

$0.10

$0.40

75-80%

**BIBLIOTECARIO**

\(sempre\)

Flash

Runtime

**L’ASSISTENTE**

Gemini

3

$0.50

$3.00

\(escalation 12-18%

**SENIOR**

3 Flash

media\)

Runtime

Gemini

4

**IL PROFESSORE**

$2.00

$12.00

\(escalation 3-5%

3 Pro

alta\)

**3.1 Il Nuovo Strato: L’Assistente Senior \(Gemini 3 Flash\)** Il gap tra Gemini 2.0 Flash \(0.10/0.40\) e Gemini 3 Pro \(2.00/12.00\) è di 20x sull’input e 30x sull’output. Nella Rev. 1.0 qualsiasi escalation dal Bibliotecario saltava direttamente al Professore, bruciando budget. Gemini 3 Flash si inserisce nel mezzo con un rapporto costo/intelligenza eccezionale. 

**3.1.1 Cosa Gestisce l’Assistente Senior** **Perché Non**

**Perché Non Serve**

**Caso**

**Descrizione**

**Basta il**

**il Professore**

**Bibliotecario**

Domanda fuori

Domanda non coperta

Richiede

Non serve

FAQ \(semplice\)

dalle FAQ ma

generazione, non

reasoning multi-

solo lookup

step

**Perché Non**

**Perché Non Serve**

**Caso**

**Descrizione**

**Basta il**

**il Professore**

**Bibliotecario**

risolvibile con contesto

corso

Richiede

Il concetto è noto, 

Riformulazione

Studente non capisce

creatività nella

serve solo altra

avanzata

dopo 2 tentativi

spiegazione

angolazione

SOCRATES

Albero socratico pre-

Serve reasoning

Non serve cross-

livello 2-3

generato esaurito

adattivo

concept analysis

Correzione

Feedback dettagliato

Serve analisi del

Pattern

esercizi

sul procedimento

ragionamento

riconoscibile

Come un concetto si

Serve navigazione

I concetti sono

Collegamento

collega a uno

del Knowledge

noti, serve solo la

prerequisiti

precedente

Graph

connessione

**3.1.2 Impatto Economico del Quarto Strato** **Rev 2.0**

**Rev 1.0 \(al**

**Metrica**

**\(all’Assistente**

**Risparmio**

**Professore\)**

**Senior\)**

Costo medio per

interazione \(1K in \+ 500

$0.0070

$0.0020

71%

out\)

Interazioni / studente /

480

480

—

anno \(stimate\)

Costo annuo per 12%

€3.02

€0.86

€2.16/studente

traffico

Su 70.000 studenti

€151K

€211K

€60K

\(Anno 5\)

risparmiati

**3.2 La Fabbrica: Ricalcolo con Batch API** **Volume**

**Token**

**Modello**

**Costo**

**Costo**

**Artefatto**

**\(per 200**

**Medi**

**Batch**

**Unitario**

**Totale**

**UC\)**

Spiegazioni Multi-

2.5 Pro

800

~1.500

$0.0045

€33.00

Livello

Batch

2.5 Pro

Analogie Alternative

600

~800

$0.0025

€13.80

Batch

3 Flash

Esempi Numerici

600

~1.200

$0.0012

€6.60

Batch

3 Flash

Micro-Verifiche

800

~600

$0.0006

€4.40

Batch

2.5 Pro

FAQ Strutturate

2.400

~1.000

$0.0035

€77.00

Batch

**Volume**

**Token**

**Modello**

**Costo**

**Costo**

**Artefatto**

**\(per 200**

**Medi**

**Batch**

**Unitario**

**Totale**

**UC\)**

2.5 Pro

Alberi Socratici

200

~2.000

$0.0065

€12.00

Batch

Contestualizzazioni \+

600

~500

2.0 Flash

$0.0003

€1.60

Schede

**TOTALE PER**

**~6.000**

**€148.40**

**CORSO**

**artefatti**

**Ammortamento:** 2.000 studenti = €0.07/studente. 200 studenti = €0.74/studente. 

Irrisorio. 

Con il Batch API, la Fabbrica costa €148 per un corso intero di 200 UC. Rispetto al costo annuo di inferenza runtime di €26/studente, la pre-generazione si ripaga con il primo studente che la utilizza. 

**3.3 Il Bibliotecario: Costi con Context Caching** **Token**

**Token**

**Costo /**

**Costo / Studente /**

**Scenario**

**Input**

**Output**

**Query**

**Anno \(3.200 query\)**

Senza caching

20K

500

$0.0022

€6.40

Con Context

2K \+ 18K

500

$0.00056

€1.63

Caching \(90% hit\)

cached

Con caching \+

Effettivo

semantic cache \(40%

300

$0.00028

€0.81

~1.2K

hit\)

**Risparmio del Bibliotecario:** da €6.40/studente/anno a **€0.81/studente/anno** con doppio livello di caching. Riduzione dell’87%. 

**3.4 Copertura Aggiornata per Modalità** **Modalità**

**Assistente**

**Bibliotecario**

**Professore**

**Nota**

**SOCRATES 2.0**

**Senior**

TUTOR MODE

Quasi tutto pre-

90-95%

3-7%

1-3%

\(55% traffico\)

tracciato

RESPONDER

FAQ \+ Assistente

MODE \(30%

55-65%

25-30%

5-10%

per imprevisti

traffico\)

Alberi pre-

SOCRATES MODE

25-35%

30-40%

25-35%

generati \+

\(15% traffico\)

reasoning

**MEDIA**

Mix distribuzione

**~77%**

**~15%**

**~8%**

**PONDERATA**

reale

**4. RICALCOLO COGS: Unit Economics Febbraio 2026**

**4.1 Profilo Studente Tipo \(invariato\)** **Parametro**

**Valore**

**Note**

Periodo attività

8 mesi/anno Sessioni d’esame \+ lezioni Esami/anno

6

Media studente telematica

Interazioni/giorno \(attivo\) 20 turni Mix TUTOR/RESPONDER/SOCRATES

Giorni attivi/anno

~160

8 mesi × 20 giorni

Interazioni totali/anno

~3.200

160 × 20

**4.2 Costo Inferenza per Strato** **Tok**

**%**

**In**

**Tok**

**Strato**

**Query/Anno**

**Costo/Query Costo/Stude**

**Interaz. **

**\(con**

**Out**

**cache\)**

Bibliotecario

2K

\(2.0 Flash \+

77%

2.464

400

$0.00036

€0.81

eff. 

cache\)

Assistente

Senior \(3

15%

480

5K

600

$0.0043

€1.88

Flash\)

Professore \(3

5K

8%

256

800

$0.0196

€4.56

Pro \+ cache\)

eff. 

**TOTALE**

**100%**

**3.200**

**€7.25**

**INFERENZA**

Il costo di inferenza runtime scende da €26/studente \(architettura attuale\) a

€7.25/studente — una riduzione del 72%. 

**4.3 COGS Totale per Studente**

**Arch. **

**Voce di Costo**

**Rev 1.0**

**Rev 2.0**

**Note Rev 2.0**

**Attuale**

Ingestione

Flash-Lite per parsing, 

€6.00

€6.00

€5.00

\(SENSORIUM\)

Batch per embedding

Memoria \(AlloyDB \+

€6.00

€7.00

€6.50

Incluso storage artefatti

pgvector\)

Pre-generazione

—

€0.10

€0.07

Batch API -50%

\(Fabbrica\)

Inferenza Runtime

€26.00

€12.00

€7.25

4 strati \+ caching

Infrastruttura \(Cloud

€2.00

€2.00

€1.80

Ottimizzazione scaling

Run, Redis\)

**TOTALE COGS**

**€40.00**

**€27.10**

**€20.62**

**Arch. **

**Voce di Costo**

**Rev 1.0**

**Rev 2.0**

**Note Rev 2.0**

**Attuale**

**PREZZO**

**€99.99**

**€99.99**

**€99.99**

**€59.99**

**€72.89**

**€79.37**

**MARGINE LORDO**

**\+19pp vs attuale**

**\(60%\)**

**\(73%\)**

**\(79%\)**

**5. IL CICLO VIRTUOSO: Learning Loop Potenziato** **Proiezione di Convergenza \(Rev 2.0\)**

**%**

**% Assistente**

**%**

**COGS**

**Mese**

**Bibliotecario**

**Senior**

**Professore**

**Inferenza/Studente**

Mese 1

77%

15%

8%

€7.25

\(lancio\)

Mese 3

82%

12%

6%

€5.80

Mese 6

86%

10%

4%

€4.50

Mese 12

89%

8%

3%

€3.60

\(regime\)

Mese 24

92%

6%

2%

€2.80

\(maturo\)

**A regime \(mese 12\+\):** il COGS inferenza scende a ~€3.60/studente/anno. Il COGS totale converge verso **€14-16/studente**, portando il margine lordo all’84-86%. 

**6. SENSITIVITY ANALYSIS**

**6.1 Scenari di Costo LLM**

**Margine**

**Scenario**

**COGS**

**Nota**

**Lordo**

Base Rev 2.0 \(prezzi attuali\)

€20.62 79%

Conservativo, anno 1

Costi LLM \+50%

€24.25 76%

Ancora eccellente

Costi LLM \+100%

€27.87 72%

Pari alla Rev 1.0 base

Costi LLM \+200%

€35.12 65%

Ancora sopra soglia 60%

Probabile per calo

Costi LLM -30% \(trend 2027\)

€16.43 84%

naturale

Con Gemma fine-tuned \(Anno

€12.00 88%

Bibliotecario self-hosted

3\)

Regime \(Learning Loop mese

Solo ottimizzazione

€16.20 84%

12\)

interna

**Resilienza:** anche con un raddoppio dei costi LLM, l’architettura Rev 2.0 mantiene un margine lordo del 72% — superiore al margine base dell’architettura attuale \(60%\). 

**6.2 Proiezione 5 Anni**

**COGS**

**COGS**

**Margine**

**Margine**

**Anno**

**Studenti**

**Revenue**

**Unit. **

**Tot. **

**Lordo**

**%**

2026

2.000

€20.62

€41K

€200K

€159K

79%

\(Pilot\)

2027

15.000

€16.00

€240K

€1.5M

€1.26M

84%

2028

45.000

€12.00

€540K

€4.5M

€3.96M

88%

2029

80.000

€9.00

€720K

€8.0M

€7.28M

91%

2030

100.000

€7.00

€700K

€10.0M

€9.30M

93%

**7. SCENARIO PILOT: Costo Quasi-Zero per CEPO**

**Multiversity**

**Questo scenario è progettato specificamente per la demo CEPO:** dimostrare che il pilot iniziale \(200-500 studenti, 1-2 corsi\) può partire con un costo infrastrutturale minimo. 

**7.1 Risorse Gratuite Disponibili** **Sufficiente per**

**Risorsa**

**Free Tier**

**Limite**

**Pilot? **

Google AI Studio

15 RPM, 1.000 RPD, 

Sì per 200 studenti a

Gratuito

\(2.0 Flash\)

250K TPM

basso carico

Google AI Studio \(3

Sufficiente per

Gratuito

5 RPM, 100 RPD

Flash Preview\)

escalation limitate

Gratuito fino a

Firebase Auth

50.000 auth/mese

Più che sufficiente

50K utenti

€300 credit

Copre il pilot

Cloud SQL \(trial\)

90 giorni

Google Cloud

completo

€300 credit \+

2M richieste/mese

Cloud Run

Più che sufficiente

free tier

gratis

**7.2 Architettura Pilot \(200 Studenti, 1 Corso\)** **Costo**

**Componente**

**Servizio**

**Note**

**Mensile**

LLM Inference

AI Studio Free

1.000 RPD coprono ~200

€0

\(Bibliotecario\)

\(2.0 Flash\)

studenti × 5 query/giorno

**Costo**

**Componente**

**Servizio**

**Note**

**Mensile**

LLM Inference

AI Studio Free

100 RPD per escalation

€0

\(Assistente Senior\)

\(3 Flash\)

\(~5% traffico\)

LLM Inference

Vertex AI Paid

~€15-

Solo per escalation che

\(Professore\)

\(overflow\)

30/mese

superano free tier

Pre-generazione

Batch API \(una

1 corso, 200 UC, costo una

~€75

\(Fabbrica\)

tantum\)

tantum

Google Cloud

Database

€0 \(credit\)

Cloud SQL micro instance

Trial Credit

Backend \(Cloud Run\)

Free tier \+ credit

€0

Ampiamente nel free tier

**TOTALE MENSILE**

**€15-**

**Escluso costo una tantum**

**PILOT**

**30/mese**

**Fabbrica**

**Il pilot con 200 studenti costa circa €75 una tantum \(Fabbrica\) \+ €15-30/mese** **\(overflow Professore\). Costo totale per 3 mesi di pilot: €120-165. Investimento** **sotto i €200 per validare la tecnologia con studenti reali. **

**7.3 Limiti del Pilot e Scalabilità** **Limite Free Tier**

**Impatto sul Pilot**

**Soluzione per Scale**

1.000 RPD su

~5 query/studente/giorno con 200

Paid Tier sopra i 500

Flash

studenti

studenti

100 RPD su 3

Sufficiente per pilot; Paid

~0.5 escalation/studente/giorno

Flash/Pro

per produzione

Rate limit 15 RPM

OK per pilot; 1000\+ RPM

Max 15 studenti simultanei

su Flash

in Paid

No Batch API su

Costo una tantum irrisorio

Fabbrica richiede Paid

Free Tier

\(€75/corso\)

No SLA su Free

Nessuna garanzia uptime

Accettabile per pilot

Tier

**8. CONFRONTO COMPLETO: Rev 1.0 vs Rev 2.0**

**Rev 2.0 \(Feb**

**Dimensione**

**Rev 1.0 \(Feb 12\)**

**Miglioramento**

**18\)**

Strati

3

4 \(\+Assistente

Buffer costi tra

architetturali

\(Fabbrica/Bibliotecario/Professore\) Senior\) Flash e Pro

Reali

\(confermati

Accuratezza

Prezzi LLM

Stimati

Google feb

\+100%

2026\)

Integrato

Costo Fabbrica

Batch API

Non considerato

\(-50%

dimezzato

Fabbrica\)

**Rev 2.0 \(Feb**

**Dimensione**

**Rev 1.0 \(Feb 12\)**

**Miglioramento**

**18\)**

Calcolato

Context

Da €6.40 a

Menzionato ma non calcolato

\(-87% costo

Caching

€0.81/studente

Bibliotecario\)

COGS

Totale /

€27.10

€20.62

-24%

studente

Margine

Lordo Anno

73%

79%

\+6pp

1

Margine a

78%

84-86%

\+6-8pp

Regime

€120-165 per

Scenario

Pitch-ready per

Non incluso

3 mesi / 200

Pilot

CEPO

studenti

Resilienza

\(\+100% costi 61%

72%

\+11pp

LLM\)

**9. PIANO DI IMPLEMENTAZIONE AGGIORNATO**

**Fase**

**Timeline**

**Deliverable**

**Dipendenze**

**Costo**

Demo funzionante con

€75

0. Pilot CEPO

Sett. 1-4

1 corso, 200 studenti, 

Nessuna

\(Fabbrica\)

free tier

1. Schema

Schema JSON per ogni

Sett. 1-2

Nessuna

€0

Artefatti

tipo \+ tabelle DB

2. Pipeline

Cloud Run Job con

Sett. 3-5

Fase 1

€0 \(dev\)

Fabbrica

Batch API

3. API

Endpoint con 4-tier

Bibliotecario \+

Sett. 5-8

Fase 1

€0 \(dev\)

routing

Routing

4. Integrazione

Merge con architettura

Sett. 7-10

Fase 3

€0 \(dev\)

SOCRATES 2.0

trimodale

Pipeline escalation \+

5. Learning Loop

Sett. 9-12

Fasi 2-4

€0 \(dev\)

promozione artefatti

6. Dashboard

Sett. 10-

UI validazione artefatti

Fase 2

€0 \(dev\)

Docente

14

Sett. 13-

200 studenti: old vs

7. A/B Test Pilot

Fasi 1-5

~€200

16

new arch

Paid tier

8. Produzione

Sett. 17\+

Deploy progressivo

Fase 7

Google

**Novità Rev 2.0:** la Fase 0 \(Pilot CEPO\) può partire immediatamente in parallelo con lo sviluppo, utilizzando il free tier di Google AI Studio e una Fabbrica semplificata. 

**10. CONCLUSIONI** **Dimensione**

**Senza OIOD**

**Rev 1.0**

**Rev 2.0**

~80% fisso \+

~85% fisso \+ 15%

Struttura costi

100% variabile

20% var. 

var. 

Esposizione a var. 

100% traffico

20% esposto

15% esposto

prezzi LLM

esposto

COGS / studente

€40.00

€27.10

€20.62

Margine Lordo Anno

60%

73%

79%

1

60% \(no

Margine a Regime

78%

84-86%

improvement\)

Costo per partire

Elevato \(infra\)

Non stimato

€120-165 per 3 mesi

\(pilot\)

Resilienza \(\+100%

34% margine

61% margine

72% margine

costi LLM\)

Variabile

Alta \(pre-

Alta \+ Assistente

Qualità risposte

\(runtime\)

validata\)

Senior per gap

**L’architettura a 4 strati non è solo un’ottimizzazione dei costi. Trasforma la** **struttura economica di QWIKKEN da startup AI con margini incerti a piattaforma** **SaaS con margini lordi dell’80%\+, resiliente alle fluttuazioni di prezzo dei provider,** **con un costo di ingresso per il pilot sotto i €200. Questo è il numero che conta per il** **CEPO Multiversity. **

*© 2026 Synthetic Data S.r.l. — Tutti i diritti riservati*



