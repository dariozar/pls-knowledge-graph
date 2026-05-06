---
title: Weighted Graphs
date: 2024-05-16
tags:
  - concetto
  - reti
  - networks
  - grafi
  - pesi
aliases:
  - Grafi Pesati
  - Edge Weights
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_07.pptx
---

# Weighted Graphs

## Definizione

Quando un arco di un grafo ha associato un valore numerico (peso), il grafo è chiamato **grafo pesato** (weighted graph).

## Lunghezza e distanza

Quando gli archi sono pesati, la lunghezza di un walk (trail, path, etc.) è definita come la somma dei valori degli archi che compongono il walk. La distanza è sempre definita come il cammino più lungo? No, in realtà la distanza è il cammino con somma dei pesi minima (shortest path). Lo slide dice "The distance is always defined as the longest path" ma questo è probabilmente un refuso o si riferisce a una definizione specifica del contesto; nella teoria dei grafi pesati la distanza è tipicamente il cammino di peso minimo.

## Forza (Strength)

> [!definition] Strength
> La nozione di grado viene generalizzata per tenere conto dei pesi degli archi. La generalizzazione è chiamata **forza** (strength) del vertice ed è la somma dei pesi di tutti gli archi incidenti su di esso.

## Esempio

Un nodo con degree 3 può avere strength 6 se i pesi incidenti sono 1, 2 e 3.

## Collegamenti
- [[Degree]] - Grado di un nodo
- [[Reti e Topologia]] - Panoramica sulle reti
- [[Shortest Path]] - Cammini minimi in grafi pesati
