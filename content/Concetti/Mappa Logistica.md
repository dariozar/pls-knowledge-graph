---
title: Mappa Logistica
date: 2024-05-02
tags:
  - concetto
  - caos
  - sistemi-complessi
  - matematica
  - modello
aliases:
  - Logistic Map
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_03.pptx
---

# Mappa Logistica

> [!definition] Mappa Logistica
> La mappa logistica è un modello matematico semplice che descrive l'evoluzione di una popolazione ed è definita dall'equazione iterativa:
> $$x_{n+1} = r \, x_n (1 - x_n)$$
> dove $r$ è un parametro reale positivo e $x_n \in [0, 1]$. Nonostante la sua semplicità, la mappa logistica mostra comportamenti caotici per valori elevati di $r$ ed è divenuta un paradigma classico per lo studio del caos deterministico.

## Interpretazione biologica

L'equazione descrive due effetti competitivi:
- **Riproduzione**: la popolazione cresce a un tasso proporzionale alla popolazione corrente quando la popolazione iniziale è piccola.
- **Mortalità**: il tasso di crescita diminuisce proporzionalmente alla differenza tra la "portata" teorica dell'ambiente e la popolazione corrente.

## Diagramma delle biforcazioni

Al variare del parametro $r$, la mappa logistica mostra un ricco scenario di comportamenti:
- Per $r < 3$: il sistema converge a un punto fisso.
- Per $3 < r < 3.57$: successione di [[Biforcazioni|biforcazioni]] a raddoppio di periodo.
- Per $r > 3.57$: comportamento caotico con finestre di periodicità.

Il diagramma delle biforcazioni è una delle figure più iconiche della teoria del caos.

## Densità di probabilità asintotica

Per $r = 4$ (regime caotico), la densità di probabilità asintotica è:

$$p_\infty(x) = \frac{1}{\pi \sqrt{x(1-x)}}$$

Questa densità è indipendente dalle condizioni iniziali (purché l'incertezza non sia nulla) e rappresenta una proprietà intrinseca del sistema.

## Rilevanza storica

La mappa logistica è stata studiata da Robert May nel 1976 e ha mostrato come comportamenti caotici possano emergere da equazioni estremamente semplici, sfidando l'intuizione che il caos richieda sistemi complessi.

## Collegamenti

- [[Caos deterministico]] - La mappa logistica è il paradigma del caos semplice.
- [[Biforcazioni]] - La mappa mostra biforcazioni a raddoppio di periodo.
- [[Nonlinearità]] - L'equazione è fondamentalmente nonlineare.
- [[Entropia]] - Per $r = 4$ si può calcolare la densità asintotica.
- [[Effetto farfalla]] - La mappa mostra sensibilità alle condizioni iniziali.
