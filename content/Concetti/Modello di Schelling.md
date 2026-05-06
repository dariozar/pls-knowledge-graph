---
title: Modello di Schelling
date: 2024-05-09
tags:
  - concetto
  - modelli-ad-agente
  - sociologia-computazionale
  - segregazione
  - toy-models
aliases:
  - Schelling Model
  - Schelling Segregation Model
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_05.pptx
---

# Modello di Schelling

Il **modello di Schelling** è un toy model di sociologia computazionale che dimostra come la segregazione residenziale possa emergere anche in assenza di estrema intolleranza.

> [!definition] Modello di Schelling
> Modello proposto da Thomas C. Schelling (1971) in cui agenti appartenenti a due gruppi diversi sono disposti su una griglia. Ogni agente si sposta se la frazione di vicini dello stesso gruppo è inferiore a una soglia di tolleranza prefissata.

## Storia e Contesto

- **Autore**: Thomas C. Schelling, Università di Harvard (paper "Dynamic Models of Segregation", 1971).
- **Motivazione**: Spiegare la formazione dei ghetti urbani (es. mappe etniche di Chicago 1940–1960, vedi [[Segregazione]]).
- **Risultato sorprendente**: anche con preferenze debolmente omofiliche (tolleranza moderata), emerge macroscopicamente una forte segregazione.

## Regole del Modello

1. **Setup**: ogni agente è rappresentato da un numero (o colore) e inserito casualmente in un reticolo bidimensionale.
2. **Decisione**: a ogni iterazione, un agente decide se spostarsi in base al numero di vicini *diversi*.
3. **Mossa**: se la frazione $m_{ij}$ di vicini identici è inferiore alla soglia di tolleranza, l'agente si sposta in una cella vuota.
4. **Terminazione**: la simulazione termina quando tutti gli agenti sono "soddisfatti" ("happy") con il proprio vicinato.

## Risultato Chiave

Anche con una soglia di tolleranza relativamente bassa (es. 30%), il sistema evolve verso configurazioni altamente segregate. Questo è un esempio di [[Fenomeni Emergenti|fenomeno emergente]]: la segregazione macroscopica non è programmata nelle regole individuali, ma emerge dalle interazioni locali.

## Collegamenti

- [[Segregazione]] - Fenomeno sociale modellato da Schelling.
- [[Modelli ad Agente]] - Classe di modelli a cui appartiene il modello di Schelling.
- [[Toy Models]] - Il modello di Schelling come esempio di toy model sociale.
- [[Fenomeni Emergenti]] - La segregazione emerge da regole locali semplici.
- [[Modello di Ising]] - Analogia fisica con transizioni ordine-disordine.
- [[Fenomeni Collettivi]] - Comportamento collettivo della popolazione.
