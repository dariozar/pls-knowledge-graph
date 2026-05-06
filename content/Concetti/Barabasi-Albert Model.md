---
title: Barabasi-Albert Model
date: 2024-05-16
tags:
  - concetto
  - reti
  - networks
  - modelli
  - scale-free
aliases:
  - Modello di Barabasi-Albert
  - Scale-Free Networks
  - Preferential Attachment
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_07.pptx
---

# Barabasi-Albert Model

## Definizione

Il **modello di Barabasi-Albert** (BA) descrive la crescita di reti **scale-free** attraverso il meccanismo dell'**attachment preferenziale** (preferential attachment).

## Meccanismo

- Nuovi nodi si collegano con probabilità proporzionale al grado dei nodi esistenti
- Ogni nuovo nodo si collega a $m$ altri nodi
- I nodi con grado più alto tendono ad attrarre più nuovi link ("il ricco diventa più ricco")

## Distribuzione del grado

La coda della distribuzione del grado decade lentamente, seguendo una **legge di potenza**:

$$P(k) \sim k^{-\gamma}$$

con $\gamma$ tipicamente tra 2 e 3.

> [!info] Scale-free
> Le reti scale-free non hanno una scala caratteristica: possono presentare nodi hub con grado arbitrariamente alto.

## Collegamenti
- [[Erdos-Renyi Model]] - Confronto con reti random
- [[Watts-Strogatz Model]] - Confronto con reti small-world
- [[Degree]] - Distribuzione del grado a legge di potenza
- [[Leggi di Potenza]] - Descrizione matematica dello scaling
- [[Reti e Topologia]] - Panoramica sui modelli di rete
- [[Immunization on networks]] - Immunizzazione nelle reti scale-free
