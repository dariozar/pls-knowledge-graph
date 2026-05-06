---
title: Algoritmo Metropolis
date: 2024-05-09
tags:
  - concetto
  - metodo-monte-carlo
  - ising
  - simulazione
  - modelli-computazionali
aliases:
  - Metropolis Algorithm
  - Metropolis-Hastings
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_05.pptx
---

# Algoritmo Metropolis

L'**algoritmo di Metropolis** è un metodo di campionamento Monte Carlo utilizzato per simulare l'equilibrio termico di sistemi statistici, come il [[Modello di Ising|modello di Ising]].

> [!definition] Algoritmo di Metropolis
> Algoritmo iterativo che propone una mossa elementare (es. flip di uno spin) e la accetta con probabilità:
> $$
> P_{\text{acc}} = \min\left(1, \exp\left(-\frac{\Delta E}{k_B T}\right)\right)
> $$
> dove $\Delta E$ è la variazione di energia e $T$ è la temperatura.

## Regole di Accettazione

- Se $\Delta E < 0$ (la mossa abbassa l'energia): la mossa è sempre accettata.
- Se $\Delta E > 0$ (la mossa aumenta l'energia): la mossa è accettata con probabilità $\exp(-\Delta E / k_B T)$.

## Ruolo della Temperatura

- A **bassa temperatura**: mosse che aumentano l'energia sono raramente accettate; il sistema converge verso il minimo di energia (stato ordinato).
- A **alta temperatura**: anche mosse disordinanti sono accettate; il sistema esplora configurazioni casuali.

## Collegamenti

- [[Modello di Ising]] - Applicazione classica dell'algoritmo.
- [[Temperatura critica]] - Vicino a $T_c$ la dinamica diventa critica e l'algoritmo richiede simulazioni più lunghe.
- [[Modelli ad Agente]] - Gli algoritmi Monte Carlo sono strumenti per simulare l'evoluzione di sistemi di agenti.
- [[Sistemi Termodinamici]] - Contesto fisico in cui opera l'algoritmo.
