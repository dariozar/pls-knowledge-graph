---
title: Lunghezza di correlazione
date: 2024-05-14
tags:
  - concetto
  - percolazione
  - transizioni-di-fase
  - correlazione
  - scala
aliases:
  - Correlation length
  - Lunghezza di correlazione di percolazione
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_06.pptx
---

# Lunghezza di correlazione

La **lunghezza di correlazione** $\xi$ è la scala caratteristica di dimensione dei cluster finiti nella teoria della percolazione.

## Definizione

La lunghezza di correlazione misura la distanza tipica alla quale due siti sono correlati, ovvero la dimensione caratteristica dei cluster finiti.

Vicino alla soglia di percolazione $p_c$, la lunghezza di correlazione diverge come:

$$\xi \sim |p - p_c|^{-\nu}$$

Dove $\nu$ è l'**esponente critico della lunghezza di correlazione**.

## Significato fisico

- Per $p < p_c$: i cluster sono finiti e isolati; $\xi$ è finita e rappresenta la dimensione tipica dei cluster
- Per $p \to p_c$: i cluster crescono senza limite; $\xi \to \infty$
- Per $p > p_c$: esiste il cluster gigante; la scala caratteristica dei cluster finiti diminuisce man mano che $p$ aumenta

Al punto critico $p = p_c$, poiché $\xi \to \infty$, non esiste più una scala caratteristica di lunghezza: il sistema è **invariante per scala** (*scale invariant*).

## Relazione con la dimensione frattale

La dimensione frattale del cluster $D$ è legata alla lunghezza di correlazione attraverso gli esponenti critici:

$$D = d - \frac{\beta}{\nu}$$

Dove $d$ è la dimensione dello spazio, $\beta$ è l'esponente del parametro d'ordine e $\nu$ è l'esponente della lunghezza di correlazione.

## Valore mean-field

Nell'albero di Cayley (limite mean-field):
$$\nu = \frac{1}{2}$$

## Collegamenti
- [[Percolazione]] - Teoria generale
- [[Esponenti critici]] - Esponente $\nu$
- [[Dimensione frattale del cluster]] - Relazione con $D$
- [[Invarianza di Scala]] - Assenza di scala caratteristica a $p_c$
- [[Sistemi Termodinamici]] - Transizioni di fase e divergenza di $\xi$
