---
title: Adjacency List
date: 2024-05-16
tags:
  - concetto
  - reti
  - networks
  - rappresentazione
  - algoritmi
aliases:
  - Lista di Adiacenza
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_07.pptx
---

# Adjacency List

## Definizione

La **lista di adiacenza** è una rappresentazione di un grafo in cui per ogni nodo si memorizza la lista dei suoi vicini (nodi adiacenti).

## Vantaggi rispetto alla matrice di adiacenza

- **Spazio**: $O(N_V + N_E)$ contro $O(N_V^2)$ della matrice
- **Efficienza**: per grafi sparsi (come la maggior parte delle reti reali), la lista di adiacenza è molto più compatta

## Confronto di complessità

| Rappresentazione | Spazio |
|------------------|--------|
| Matrice di adiacenza | $O(N_V^2)$ |
| Lista di adiacenza | $O(N_V + N_E)$ |

Per reti sparse ($N_E \ll N_V^2$), la lista di adiacenza è decisamente preferibile.

## Collegamenti
- [[Adjacency Matrix]] - Rappresentazione matriciale
- [[Reti e Topologia]] - Panoramica sulle reti
