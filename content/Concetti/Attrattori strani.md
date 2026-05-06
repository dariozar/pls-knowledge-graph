---
title: Attrattori strani
date: 2024-05-07
tags:
  - concetto
  - frattali
  - caos
  - complessità
  - sistemi dinamici
aliases:
  - Strange Attractors
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_04.pptx
---

# Attrattori strani

Gli **attrattori strani** (*strange attractors*) sono insiemi invarianti che compaiono nello spazio delle fasi di **sistemi dinamici dissipativi caotici**. Sono "strani" perché la loro geometria non è quella di una curva o di una superficie regolare, ma possiede una struttura frattale complessa.

## Proprietà

Gli attrattori strani mostrano tipicamente:

- **[[Auto-similarità|Auto-similarità]]**: strutture che si ripetono su scale sempre più piccole. Nell'attrattore di Hénon, zoomando successivamente si osserva la stessa struttura striata ripetersi.
- **[[Dimensione frattale|Dimensione frazionaria]]**: sia i frattali che gli attrattori hanno dimensione non intera. Per l'attrattore di Hénon, la dimensione di correlazione è circa $d \approx 1.23$ e la [[Box-counting dimension|box-counting dimension]] circa $d \approx 1.27$.
- **Attrattività**: le traiettorie nelle vicinanze convergono verso l'attrattore nel tempo.
- **Sensibilità alle condizioni iniziali**: due traiettorie sull'attrattore divergono esponenzialmente, pur rimanendo confinate su di esso.

## Esempio: attrattore di Hénon

L'attrattore di Hénon è uno dei più famosi esempi. Studiando il numero di box necessarie per coprirlo:

| Lato box $\epsilon$ | Box colpiti $N(\epsilon)$ |
|---------------------|---------------------------|
| $1/8$ | 177 |
| $1/16$ | 433 |
| $1/32$ | 1037 |
| $1/64$ | 2467 |
| $1/128$ | 5763 |

Da questi dati si ricava una [[Box-counting dimension|box-counting dimension]] $d \approx 1.27$.

## Relazione con il caos

Gli attrattori strani sono intimamente legati al **caos deterministico**: la dinamica caotica "sparge" le traiettorie in modo da riempire un insieme con struttura frattale. Non tutti gli attrattori sono strani (quelli periodici o quasi-periodici non lo sono), ma nei sistemi caotici dissipativi l'attrattore è quasi sempre strano.

> Una trattazione approfondita di questo punto va oltre gli scopi del corso, ma è importante riconoscere che il caos genera naturalmente geometria frattale.

## Collegamenti

- [[Caos e Frattali]] - La connessione profonda tra sistemi caotici e strutture frattali.
- [[Frattali]] - La geometria frattale descrive la struttura degli attrattori strani.
- [[Auto-similarità]] - Proprietà geometrica fondamentale degli attrattori strani.
- [[Dimensione frattale]] - Misura quantitativa della complessità di un attrattore.
- [[Sistemi Complessi]] - Gli attrattori strani emergono in sistemi dinamici complessi.
