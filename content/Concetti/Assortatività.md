---
title: Assortatività
date: 2024-05-16
tags:
  - concetto
  - reti
  - networks
  - metriche
  - topologia
aliases:
  - Assortativity
  - Degree Correlation
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_07.pptx
---

# Assortatività

## Definizione

L'**assortatività** è una preferenza per i nodi della rete di collegarsi ad altri nodi simili in qualche modo, ad esempio con lo stesso grado $k$.

## Funzione del grado medio dei vicini

Un metodo per valutare l'assortatività è considerare la funzione del grado medio dei vicini più prossimi (average nearest neighbours' degree function):

$$k_{nn}(k) = \frac{1}{N_k} \sum_{i: k_i=k} \frac{1}{k_i} \sum_{j \in \mathcal{N}(i)} k_j$$

dove $N_k$ è il numero di nodi di grado $k$.

Se $k_{nn}(k)$ cresce con $k$, la rete è **assortativa** (nodi con grado alto si collegano a nodi con grado alto). Se decresce, è **disassortativa**.

## Collegamenti
- [[Degree]] - Grado dei nodi
- [[Barabasi-Albert Model]] - Reti scale-free spesso disassortative
- [[Reti e Topologia]] - Panoramica sulle reti
