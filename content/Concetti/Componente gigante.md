---
title: Componente gigante
date: 2024-05-14
tags:
  - concetto
  - percolazione
  - reti
  - transizioni-di-fase
  - cluster
aliases:
  - Giant component
  - Giant cluster
  - Spanning cluster
  - Cluster di percolazione
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_06.pptx
---

# Componente gigante

La **componente gigante** (o *spanning cluster*, o *cluster di percolazione*) è il cluster di siti (o legami) occupati che attraversa l'intero sistema da un bordo all'altro.

## Definizione

In un reticolo di dimensione lineare $L$, un cluster è detto "gigante" o "di spanning" se esiste un percorso continuo di siti occupati che collega due lati opposti del sistema.

Sopra la soglia di percolazione $p_c$, questo cluster:
- Contiene una frazione finita di tutti i siti del sistema
- Ha massa $M \sim L^d$ per $p > p_c$
- Ha dimensione frattale $M \sim L^D$ (con $D < d$) esattamente a $p = p_c$

## Formazione nell'albero di Cayley

Per un albero di Cayley con coordinazione $z$, un sito di origine $i_0$ appartiene al cluster gigante se, in media, il numero di nodi occupati nei rami adiacenti è maggiore o uguale a 1:

$$p(z-1) \geq 1$$

Da cui si ottiene la soglia critica:
$$p_c = \frac{1}{z-1}$$

## Massa del cluster

La massa $M$ di un cluster di percolazione è definita come il numero totale di siti che vi appartengono (o equivalentemente la sua area/volume).

Il comportamento di scala dipende dal regime:
- $p > p_c$: $M \sim L^d$ (oggetto compatto, dimensione euclidea)
- $p = p_c$: $M \sim L^D$ con $D < d$ (oggetto frattale)
- $p < p_c$: $M \sim \ln L$ (cluster finiti)

## Collegamenti
- [[Percolazione]] - Teoria generale
- [[Soglia di percolazione]] - Soglia critica $p_c$
- [[Probabilità di spanning]] - Probabilità di appartenenza al cluster
- [[Dimensione frattale del cluster]] - Proprietà geometrica al punto critico
- [[Connected Components]] - Componenti connesse nelle reti
