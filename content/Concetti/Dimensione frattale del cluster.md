---
title: Dimensione frattale del cluster
date: 2024-05-14
tags:
  - concetto
  - percolazione
  - frattali
  - geometria
  - transizioni-di-fase
aliases:
  - Fractal dimension of cluster
  - Dimensione del cluster di percolazione
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_06.pptx
---

# Dimensione frattale del cluster

La **dimensione frattale del cluster** $D$ è una proprietà geometrica fondamentale dei cluster di percolazione esattamente al punto critico $p = p_c$.

## Definizione

La massa $M$ di un cluster di percolazione (numero totale di siti appartenenti a esso) scala con la dimensione lineare $L$ del sistema come:

$$M \sim L^D$$

Dove $D$ è la dimensione frattale del cluster. Per $p = p_c$, si ha $D < d$ (dove $d$ è la dimensione euclidea dello spazio).

## Comportamento nei diversi regimi

### $p > p_c$ (sopra la soglia)
Il cluster gigante è un oggetto compatto:
$$M \sim L^d \quad \Rightarrow \quad D = d$$

### $p = p_c$ (punto critico)
Il cluster di percolazione è un oggetto **frattale**:
$$M \sim L^D \quad \text{con } D < d$$

Per il reticolo quadrato 2D ($d = 2$):
$$D \approx 1.89$$

### $p < p_c$ (sotto la soglia)
I cluster sono finiti e isolati:
$$M \sim \ln L$$

## Perché $D < d$?

La ragione fisica per cui la dimensione frattale è minore della dimensione dello spazio è la presenza di **buchi** (*holes*) nel cluster:

- Il cluster di percolazione non è un oggetto compatto e uniforme
- Esso è un oggetto ramificato con vuoti a tutte le scale
- L'unico requisito per il cluster di spanning è che colleghi due lati opposti del reticolo
- Non è necessario che cresca uniformemente in tutte le direzioni

Si tratta quindi di oggetti **ramificati**, non compatti.

## Relazione con gli esponenti critici

La dimensione frattale è legata agli esponenti critici. In particolare, per la percolazione:
$$D = d - \frac{\beta}{\nu}$$

Dove $\beta$ è l'esponente del parametro d'ordine e $\nu$ è l'esponente della lunghezza di correlazione.

Nell'albero di Cayley (dimensione infinita), $D = 4$.

## Collegamenti
- [[Percolazione]] - Teoria generale
- [[Componente gigante]] - Cluster al punto critico
- [[Esponenti critici]] - Esponenti $\beta$ e $\nu$
- [[Dimensione frattale]] - Concetto generale di dimensione frattale
- [[Frattali]] - Oggetti frattali e auto-similarità
- [[Invarianza di Scala]] - Proprietà di assenza di scala caratteristica
