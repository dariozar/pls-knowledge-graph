---
title: SIR Model
date: 2024-05-16
tags:
  - concetto
  - reti
  - networks
  - epidemie
  - modelli
aliases:
  - Modello SIR
  - Susceptible-Infected-Removed
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_07.pptx
---

# SIR Model

## Definizione

Il **modello SIR** è un modello compartimentale fondamentale in epidemiologia. La popolazione è divisa in tre compartimenti:

- **S** (Susceptible): individui suscettibili di contrarre la malattia
- **I** (Infected): individui infetti
- **R** (Removed): individui rimossi (guariti o deceduti)

> [!note] Rimozione
> Il compartimento R include sia gli individui guariti che quelli deceduti: in entrambi i casi non possono più far parte dei compartimenti S e I.

## Equazioni

Assumendo che la dimensione della popolazione $N(t)=N_0$ rimanga costante, il modello è descritto dalle equazioni:

$$\frac{ds}{dt} = -\beta s x$$
$$\frac{dx}{dt} = \beta s x - \gamma x$$
$$\frac{dr}{dt} = \gamma x$$

dove:
- $s, x, r$: frazioni di popolazione suscettibile, infetta e rimossa ($s+x+r=1$)
- $\beta$: tasso medio di contatto per unità di tempo
- $\gamma$: tasso di recupero (inverso del tempo medio di infezione)

## Soluzione

La variabile $s$ può essere scritta in termini di $r$:

$$s(t) = s_0 e^{-\frac{\beta}{\gamma} r(t)}$$

Il valore asintotico di $r$ si ottiene ponendo $dr/dt = 0$.

## Collegamenti
- [[Networked SIR Model]] - Adattamento su reti di contatti
- [[Reti e Topologia]] - Panoramica sulle reti
- [[Modelli ad Agente]] - Altri modelli di simulazione
