---
title: Probabilità di spanning
date: 2024-05-14
tags:
  - concetto
  - percolazione
  - transizioni-di-fase
  - ordine
aliases:
  - Spanning probability
  - Order parameter (percolation)
  - Strength of the infinite network
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_06.pptx
---

# Probabilità di spanning

La **probabilità di spanning** $P(p)$ è la probabilità che un sito (tipicamente l'origine) appartenga al cluster di percolazione infinito. Essa funge da **parametro d'ordine** nella transizione di percolazione.

## Definizione

Sia $Q$ la probabilità che il nodo origine $i_0$ **non** appartenga al cluster di percolazione attraverso nessuno dei suoi $z-1$ rami.

La probabilità che un nodo non appartenga al cluster gigante attraverso uno specifico ramo, considerando che il nodo adiacente può essere:
- Non occupato (probabilità $1-p$)
- Occupato ma non connesso al cluster (probabilità $p \cdot Q^{z-1}$)

Si ottiene l'equazione:
$$Q = (1-p) + p Q^{z-1}$$

## Soluzione per l'albero di Cayley

### Caso $z = 3$
L'equazione diventa:
$$Q = 1 - p + p Q^2$$

Risolvendo:
$$p Q^2 - Q + (1-p) = 0$$

Le soluzioni sono:
- $Q = 1$ (sempre valida, corrisponde a $P = 0$)
- $Q = \frac{1-p}{p}$ (valida per $p \geq p_c = 1/2$)

### Probabilità di spanning
$$P(p) = 1 - Q = 1 - \frac{1-p}{p} = \frac{2p - 1}{p} = \frac{p - p_c}{p}$$

## Comportamento critico

Per $p \cong p_c$, sviluppando in serie di Taylor:
$$P(p) \sim (p - p_c)^{\beta}$$

Per l'albero di Cayley, $\beta = 1$.

Il parametro d'ordine $P(p)$ si annulla continuamente alla soglia critica, caratteristica di una transizione di fase continua (del secondo ordine).

## Interpretazione fisica

- $P(p) = 0$ per $p \leq p_c$: nessun cluster infinito
- $P(p) > 0$ per $p > p_c$: emerge il cluster gigante; $P(p)$ è la frazione di siti appartenenti a esso
- $P(p)$ cresce monotonicamente da 0 a 1 al crescere di $p$

## Collegamenti
- [[Percolazione]] - Teoria generale
- [[Soglia di percolazione]] - Punto critico $p_c$
- [[Parametro d'ordine]] - Interpretazione come parametro d'ordine
- [[Esponenti critici]] - Esponente $\beta$
- [[Componente gigante]] - Cluster di percolazione
