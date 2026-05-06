---
title: Mappa di Henon
date: 2024-05-02
tags:
  - concetto
  - caos
  - sistemi-complessi
  - matematica
  - modello
aliases:
  - Henon Map
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_03.pptx
---

# Mappa di Henon

> [!definition] Mappa di Henon
> La mappa di Henon è una mappa bidimensionale nonlineare proposta nel 1976 dall'astronomo Michel Henon. È definita dalle equazioni:
> $$x_{n+1} = 1 - a x_n^2 + y_n$$
> $$y_{n+1} = b x_n$$
> Con i parametri tipici $a = 1.4$ e $b = 0.3$, la mappa genera un [[Attrattori|attrattore strano]] di forma caratteristica.

## Scopo storico

Henon propose questa mappa con lo scopo di fornire il modello più semplice possibile capace di mostrare le proprietà essenziali dell'attrattore strano presente nel [[Modello di Lorenz|modello di Lorenz]]. In particolare, la mappa ha giocato un ruolo fondamentale per capire la struttura geometrica del modello di Lorenz.

## L'attrattore di Henon

Con $a = 1.4$ e $b = 0.3$:
- Le traiettorie convergono a un insieme compatto di forma frattale.
- L'attrattore ha dimensione frattale (non intera).
- Mostra la struttura a "foglia" tipica degli attrattori strani.

La mappa di Henon è contratta nelle $y$ (fattore $b < 1$) e piegata nelle $x$ (termine quadratico), producendo la struttura caratteristica.

## Semplificazione del modello di Lorenz

Il modello di Lorenz è un sistema continuo di tre equazioni differenziali. La mappa di Henon ne cattura l'essenza geometrica in una forma discreta e bidimensionale, rendendo più facile l'analisi numerica e concettuale.

## Collegamenti

- [[Modello di Lorenz]] - La mappa di Henon semplifica la geometria dell'attrattore di Lorenz.
- [[Attrattori]] - Genera uno degli attrattori strani più studiati.
- [[Caos deterministico]] - Esempio di caos in un sistema discreto bidimensionale.
- [[Nonlinearità]] - Il termine quadratico $x_n^2$ è essenziale per il caos.
