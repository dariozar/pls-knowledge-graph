---
title: Degree
date: 2024-05-16
tags:
  - concetto
  - reti
  - networks
  - metriche
  - centralità
aliases:
  - Grado
  - Degree Centrality
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_07.pptx
---

# Degree

## Definizione

Il **grado** (degree) di un vertice è il numero di archi incidenti su di esso. È la più semplice metrica di centralità.

> [!definition] Adiacenza
> Due vertici $u, v \in V$ sono **adiacenti** se sono uniti da un arco in $E$. Due archi $e_1, e_2 \in E$ sono adiacenti se connessi da un vertice in $V$.

## Sequenza di grado

La **sequenza di grado** si ottiene ordinando i gradi dei vertici in ordine non decrescente.

Esempio: $\{1,1,1,1,1,1,1,2,2,2,2,2,2,3,3,4,4,5,6\}$

## In-degree e Out-degree

Nei grafi diretti si distinguono:
- **In-degree**: numero di archi entranti
- **Out-degree**: numero di archi uscenti

## Collegamenti
- [[Weighted Graphs]] - Generalizzazione del degree in forza (strength)
- [[Betweenness]] - Altra metrica di centralità
- [[Assortatività]] - Correlazione tra gradi dei nodi vicini
- [[Reti e Topologia]] - Panoramica sulle reti
- [[Erdos-Renyi Model]] - Distribuzione di grado di Poisson
- [[Barabasi-Albert Model]] - Distribuzione di grado a legge di potenza
