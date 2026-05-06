---
title: Modello di Lorenz
date: 2024-05-02
tags:
  - concetto
  - caos
  - sistemi-complessi
  - matematica
  - modello
aliases:
  - Lorenz System
  - Attrattore di Lorenz
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_03.pptx
---

# Modello di Lorenz

> [!definition] Modello di Lorenz
> Il modello di Lorenz è un sistema di tre equazioni differenziali ordinarie nonlineari che descrive il moto convettivo di un fluido in condizioni di Rayleigh-Bénard. Fu introdotto da Edward Lorenz nel 1963 ed è divenuto il paradigma del caos deterministico, mostrando come un sistema deterministico con sole tre variabili possa produrre comportamenti imprevedibili.

## Equazioni

Il sistema è definito da:

$$\dot{x} = \sigma (y - x)$$
$$\dot{y} = \rho x - z - y$$
$$\dot{z} = xy - \beta z$$

dove $\sigma$, $\rho$ e $\beta$ sono parametri del sistema.

## Interpretazione fisica

Il modello rappresenta il moto di un fluido sotto condizioni di Rayleigh-Bénard:
- Una porzione di fluido incomprimibile è contenuta in una cella con temperatura maggiore $T_1$ sul fondo e temperatura minore $T_2$ in cima.
- Fisicamente, questa situazione rappresenta l'atmosfera terrestre: temperatura maggiore al suolo (riscaldamento solare) e minore a maggiore altitudine.
- Le variabili $x$, $y$, $z$ descrivono rispettivamente l'intensità del moto convettivo, la differenza di temperatura tra correnti ascendenti e discendenti, e la distorsione del profilo termico verticale.

## L'attrattore di Lorenz

Con i parametri standard ($\sigma = 10$, $\rho = 28$, $\beta = 8/3$):
- Il sistema evolve verso un insieme compatto nello spazio delle fasi.
- Questo insieme ha la forma iconica di una "farfalla" o di un "occhio".
- È un [[Attrattori|attrattore strano]] con dimensione frattale.
- Le traiettorie girano attorno a due punti foci instabili in modo apparentemente casuale.

## Scoperta dell'effetto farfalla

Fu studiando questo modello che Lorenz scoprì la sensibilità alle condizioni iniziali. Arrotondando i dati di input da sei a tre cifre decimali, ottenne previsioni completamente diverse, dando origine al concetto di [[Effetto farfalla|effetto farfalla]].

## Collegamenti

- [[Effetto farfalla]] - Scoperto studiando questo modello.
- [[Attrattori]] - L'attrattore di Lorenz è il più famoso attrattore strano.
- [[Caos deterministico]] - Paradigma del caos in sistemi continui.
- [[Mappa di Henon]] - Semplificazione discreta della geometria dell'attrattore.
- [[Nonlinearità]] - Le equazioni sono fortemente nonlineari.
- [[Previsione]] - Il modello mostra i limiti fondamentali alla previsione meteorologica.
