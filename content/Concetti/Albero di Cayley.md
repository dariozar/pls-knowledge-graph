---
title: Albero di Cayley
date: 2024-05-14
tags:
  - concetto
  - percolazione
  - reti
  - mean-field
  - esatto
aliases:
  - Cayley tree
  - Rete di Bethe
  - Bethe lattice
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_06.pptx
---

# Albero di Cayley

L'**albero di Cayley** (o *Cayley tree*), anche noto come **rete di Bethe** (*Bethe lattice*), è un albero in cui ogni vertice non-foglia ha un numero costante di rami $z$ (numero di coordinazione).

## Definizione

Un albero di Cayley è un grafo senza cicli in cui:
- Ogni nodo interno ha esattamente $z$ vicini (numero di coordinazione $z$)
- Partendo da un nodo origine $i_0$, per ogni sito $i$ già raggiunto ci sono $z-1$ rami uscenti (uno porta al nodo genitore, gli altri $z-1$ ai figli)
- Non esistono cicli chiusi

## Proprietà fondamentali

### Isomorfismo
Un grafo di Bethe con numero di coordinazione pari $2n$ è isomorfo al grafo di Cayley non orientato di un gruppo libero di rango $n$ rispetto a un insieme generatore libero.

### Soglia di percolazione

Poiché non ci sono cicli, la percolazione sull'albero di Cayley è esattamente risolvibile. Per la formazione di un cluster che si estende su tutto l'albero, è necessario che in media almeno un ramo per nodo sia occupato:

$$p(z-1) \geq 1$$

Da cui si ottiene la soglia critica:
$$p_c = \frac{1}{z-1}$$

Per $z = 3$: $p_c = \frac{1}{2}$

## Ruolo nella teoria della percolazione

L'albero di Cayley è fondamentale perché:
- Fornisce una soluzione **esatta** del problema di percolazione
- Rappresenta il limite **mean-field** (campo medio) della percolazione
- Corrisponde alla percolazione in **dimensione infinita** ($d \to \infty$)
- Gli esponenti critici calcolati sull'albero di Cayley sono gli esponenti mean-field

## Limitazioni

L'albero di Cayley non ha cicli, quindi:
- Non c'è effetto di "loop" o percorsi alternativi
- In reti reali o reticoli di dimensione finita, i cicli modificano il comportamento critico
- Gli esponenti critici in dimensione finita differiscono da quelli mean-field

## Collegamenti
- [[Percolazione]] - Teoria generale
- [[Soglia di percolazione]] - Soglia critica $p_c = 1/(z-1)$
- [[Probabilità di spanning]] - Calcolo esatto su Cayley tree
- [[Esponenti critici]] - Esponenti mean-field
- [[Reti e Topologia]] - Strutture di grafi
