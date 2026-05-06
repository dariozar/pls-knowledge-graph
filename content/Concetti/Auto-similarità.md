---
title: Auto-similarità
date: 2024-05-07
tags:
  - concetto
  - frattali
  - geometria
  - complessità
aliases:
  - Self-similarity
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_04.pptx
---

# Auto-similarità

L'**auto-similarità** (*self-similarity*) è la proprietà per cui un oggetto presenta la **ripetizione di strutture a diverse scale di lunghezza**. È una delle caratteristiche definitori dei [[Frattali|frattali]].

## Definizione

Un oggetto è auto-simile se parti di esso, opportunamente ingrandite, assomigliano all'intero oggetto. Questa ripetizione può essere:

- **Esatta**: la struttura si ripete identica a scale diverse (come nell'[[Insieme di Cantor]]).
- **Statistica**: le proprietà statistiche si ripetono a scale diverse (come in molti frattali naturali).
- **Asintotica**: l'auto-similarità emerge solo in un limite di scale molto piccole (come negli [[Attrattori strani|attrattori strani]]).

## Esempi

### Insieme di Cantor

Ogni intervallo rimanente nell'insieme di Cantor, se ingrandito di un fattore 3, è una copia esatta dell'intero insieme. Questo è l'esempio più puro di auto-similarità esatta.

### Attrattore di Hénon

L'[[Attrattori strani|attrattore di Hénon]] mostra auto-similarità asintotica. Zoomando successivamente su una regione dell'attrattore, si osserva una struttura striata che si ripete su scale sempre più piccole:

- (a) $[-2.5, 2.5] \times [-2.5, 2.5]$
- (b) $[0.78, 0.94] \times [0.78, 0.94]$
- (c) $[0.865, 0.895] \times [0.865, 0.895]$
- (d) $[0.881, 0.886] \times [0.881, 0.886]$

## Significato fisico

L'auto-similarità implica che non esiste una "scala caratteristica" privilegiata: il sistema appare simile indipendentemente dal livello di zoom. Questa assenza di scala è strettamente legata all'[[Invarianza di Scala|invarianza di scala]] e alle [[Leggi di Potenza|leggi di potenza]] che descrivono molti sistemi complessi.

## Collegamenti

- [[Frattali]] - Oggetti che tipicamente presentano auto-similarità.
- [[Insieme di Cantor]] - Esempio di auto-similarità esatta.
- [[Attrattori strani]] - Esempio di auto-similarità asintotica nei sistemi dinamici.
- [[Caos e Frattali]] - L'auto-similarità emerge naturalmente nei sistemi caotici.
- [[Invarianza di Scala]] - Proprietà collegata all'assenza di scala caratteristica.
