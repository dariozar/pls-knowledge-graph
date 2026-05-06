---
title: Nonlinearità
date: 2024-05-02
tags:
  - concetto
  - caos
  - sistemi-complessi
  - matematica
aliases:
  - Nonlinearity
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_03.pptx
---

# Nonlinearità

> [!definition] Nonlinearità
> La nonlinearità è la proprietà delle equazioni del moto in cui l'output non è proporzionale all'input. Nei sistemi caotici, le equazioni del moto sono necessariamente nonlineari. È la nonlinearità che permette la sensibilità esponenziale alle condizioni iniziali e quindi il [[Caos deterministico|caos deterministico]].

## Il ruolo della nonlinearità nel caos

Le equazioni del moto nei sistemi caotici sono nonlineari. Questa è una condizione necessaria (anche se non sufficiente) per il caos. La nonlinearità introduce effetti come:
- **Amplificazione delle perturbazioni**: piccole differenze crescono esponenzialmente.
- **Comportamento imprevedibile**: traiettorie vicine divergono rapidamente.
- **Strutture complesse**: emergenza di attrattori strani e biforcazioni.

## Esempio: mappa quadratica

Consideriamo la regola iterativa $x_{t+1} = x_t^2 - 2$. È un sistema chiaramente deterministico: dato $x_0$ si determina univocamente $x_1$, poi $x_2$, e così via.

Partendo da:
- $x_0 = 0.5$
- $x_0' = 0.50001$ (differenza di $0.00001$)

Dopo poche iterazioni le traiettorie sono completamente diverse, dimostrando come la nonlinearità generi caos anche in sistemi molto semplici.

## Differenza tra sistemi lineari e nonlineari

| Lineare | Nonlineare |
|---------|-----------|
| Principio di sovrapposizione valido | Principio di sovrapposizione violato |
| Soluzioni stabili o instabili in modo prevedibile | Possibile caos deterministico |
| Piccole perturbazioni rimangono piccole | Piccole perturbazioni possono crescere esponenzialmente |
| Facilmente risolvibili analiticamente | Spesso richiedono metodi numerici |

## Collegamenti

- [[Caos deterministico]] - Il caos nasce dalle equazioni nonlineari.
- [[Effetto farfalla]] - La nonlinearità è la sorgente della sensibilità alle condizioni iniziali.
- [[Esponenti di Lyapunov]] - Quantificano la divergenza causata dalla nonlinearità.
- [[Mappa Logistica]] - Esempio classico di sistema nonlineare caotico.
- [[Modello di Lorenz]] - Sistema di equazioni differenziali nonlineari.
- [[Mappa di Henon]] - Mappa nonlineare bidimensionale.
