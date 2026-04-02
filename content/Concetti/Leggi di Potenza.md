---
title: Leggi di Potenza
date: 2024-04-16
tags:
  - fisica-statistica
  - leggi-di-potenza
  - scaling
aliases:
  - Power Laws
source: Lezione 01 e 02 - Introduzione alla Complessità / Fenomeni Emergenti e Leggi di Potenza
---
> [!definition] Legge di potenza
> Una legge di potenza è una relazione funzionale del tipo $y = A x^\alpha$, dove $A$ è una costante di proporzionalità e $\alpha$ è l'esponente di scala. In un grafico log-log, una legge di potenza appare come una retta con pendenza $-\alpha$. Le leggi di potenza sono ubiquitarie in natura e descrivono fenomeni che mostrano invarianza di scala.

Le leggi di potenza emergono in moltissimi sistemi complessi: distribuzioni di magnitude di terremoti (legge di Gutenberg-Richter), distribuzioni di reddito (legge di Zipf), distribuzioni di popolazione delle città, tempi di attesa in sistemi di coda, e molti altri. La presenza di una legge di potenza indica che il sistema non ha una scala tipica e che le fluttuazioni sono significative a tutte le scale.

> [!info] Universality delle leggi di potenza
> Le leggi di potenza sono spesso associate a fenomeni di criticalità auto-organizzata (Self-Organized Criticality, SOC), dove un sistema evolve verso un punto critico senza tuning di parametri esterni. Il modello del sandbox (BTW) di Bak, Tang e Wiesenfeld dimostra come interazioni locali possano portare a una dinamica globale descritta da leggi di potenza. Inoltre, le leggi di potenza sono invarianti sotto trasformazioni di scala, il che le rende particolarmente robuste e universali in sistemi molto diversi.

## Esempi dalla Lezione 02

![[attachments/lezione-02/slide-22-img-000.png|400]]
*Figura: Visualizzazione delle leggi di potenza — poche entità con valori alti, molte con valori bassi.*

La [[Legge di Zipf]] è un caso specifico di legge di potenza osservato in linguistica, economia e genomica. Lo studio di Mantegna et al. (1994) ha mostrato che le sequenze non codificanti di mammiferi seguono una legge di Zipf con esponente $\zeta = 0.283$.

Le applicazioni includono:
- Dimensione delle città e degli abitati
- Distribuzione dei redditi e delle imprese
- Forza dei terremoti
- Frequenza delle parole nei testi
- Frequenza degli accessi alle pagine internet

## Collegamenti

- [[Invarianza di Scala]] - La proprietà di scaling è espressa da leggi di potenza.
- [[Sistemi Complessi]] - Le leggi di potenza sono una caratteristica dei sistemi complessi.
- [[Herding]] - Le distribuzioni a code pesanti dei rendimenti possono essere leggi di potenza.
- [[Fenomeni Emergenti]] - L'emergenza di leggi di potenza è spesso un fenomeno collettivo.
- [[Sistemi Termodinamici]] - Le transizioni di fase sono descritte da leggi di potenza.
- [[Legge di Zipf]] - Caso specifico di legge di potenza in linguistica e genetica.
- [[Istogrammi]] - Strumento per visualizzare le distribuzioni che possono seguire leggi di potenza.