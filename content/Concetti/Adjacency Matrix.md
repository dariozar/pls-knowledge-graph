---
title: Adjacency Matrix
date: 2024-05-16
tags:
  - concetto
  - reti
  - networks
  - rappresentazione
  - algebra
aliases:
  - Matrice di Adiacenza
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_07.pptx
---

# Adjacency Matrix

## Definizione

La **matrice di adiacenza** $A$ di un grafo con $N_V$ vertici è una matrice $N_V \times N_V$ dove l'elemento $A_{ij} = 1$ se esiste un arco tra $i$ e $j$, e $0$ altrimenti.

## Proprietà

- Per grafi **non diretti**, la matrice è **simmetrica** ($A_{ij} = A_{ji}$).
- Per grafi **diretti**, la matrice è **non simmetrica**.
- La somma per riga (o colonna, per grafi non diretti) dà il **degree** del nodo.
- Per digrafi, la somma per riga dà l'**out-degree** e la somma per colonna dà l'**in-degree**.

## Potenze della matrice di adiacenza

> [!important] Cammini di lunghezza $r$
> La $r$-esima potenza della matrice di adiacenza, $A^r$, ha elementi $A^{(r)}_{ij}$ che forniscono il **numero di walk di lunghezza $r$** tra i vertici $i$ e $j$.

Esempi:
- $r=2$: numero di walk di lunghezza 2
- $r=3$: numero di walk di lunghezza 3

## Collegamenti
- [[Adjacency List]] - Alternativa computazionale alla matrice
- [[Degree]] - Calcolo del grado dalla matrice
- [[Reti e Topologia]] - Panoramica sulle reti
