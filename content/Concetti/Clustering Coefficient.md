---
title: Clustering Coefficient
date: 2024-05-16
tags:
  - concetto
  - reti
  - networks
  - metriche
  - topologia
aliases:
  - Coefficiente di Clustering
  - Transitivity
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_07.pptx
---

# Clustering Coefficient

## Clustering coefficient locale

Il **clustering coefficient locale** di un nodo $i$ misura la frazione di vicini del nodo che sono collegati tra loro:

$$C_i = \frac{\{e_{jk}\}}{\binom{k_i}{2}} = \frac{2 \{e_{jk}\}}{k_i(k_i-1)}$$

dove $\{e_{jk}\}$ è il numero di archi osservati tra coppie di vertici $j,k$ collegati a $i$, e $k_i$ è il grado del vertice $i$.

Il denominatore $\binom{k_i}{2}$ rappresenta il numero di possibili link tra i vicini più prossimi del nodo $i$.

## Clustering coefficient globale

Il **clustering coefficient globale** è definito come la frazione di triple connesse (path di lunghezza 2) nella rete che sono "chiuse" (formano un triangolo).

> [!note] Triangoli e triple
> Una **triple** (connected triple) è un cammino di lunghezza 2. Un **triangolo** contiene 3 triple.

Il clustering coefficient globale misura la tendenza della rete a formare triangoli (transitività).

## Collegamenti
- [[Reti e Topologia]] - Panoramica sulle reti
- [[Degree]] - Grado dei nodi vicini
- [[Clique]] - Sottografi completi come estremo del clustering
- [[Watts-Strogatz Model]] - Modello con alto clustering coefficient
