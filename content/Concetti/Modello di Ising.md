---
title: Modello di Ising
date: 2024-05-09
tags:
  - concetto
  - ising
  - fisica-statistica
  - transizioni-di-fase
  - modelli-computazionali
aliases:
  - Ising Model
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_05.pptx
---

# Modello di Ising

Il **modello di Ising** è il paradigma fisico per lo studio delle [[Transizioni di Fase|transizioni di fase]] ordine-disordine in sistemi di spin. Fu proposto da Wilhelm Lenz nel 1920 e risolto in una dimensione da Ernst Ising nel 1925.

> [!definition] Modello di Ising
> Un sistema di $N$ [[Spins|spin]] (agenti) disposti su un reticolo che possono assumere due valori $\pm 1$. Ciascuno spin interagisce ferromagneticamente con i suoi primi vicini, tendendo ad allinearsi. L'energia totale (in assenza di campo esterno) è:
> $$
> H = -J \sum_{\langle i,j \rangle} s_i s_j
> $$
> dove $J > 0$ è la costante di accoppiamento ferromagnetico e la somma è estesa alle coppie di primi vicini.

## Dinamica e Simulazione

La dinamica del modello può essere simulata con metodologie di tipo **Monte Carlo**. Un esempio classico è l'[[Algoritmo Metropolis|algoritmo di Metropolis]]:

- Ogni mossa elementare (flip di un singolo spin) è accettata con probabilità $\exp(-\Delta E / k_B T)$
- $\Delta E$ è la variazione di energia associata al flip
- $T$ è la temperatura del sistema

Le interazioni ferromagnetiche spingono il sistema verso uno dei due stati ordinati (tutti $+1$ o tutti $-1$), mentre il rumore termico tende a distruggere l'ordine.

## Transizione di Fase

Per basse temperature ($T < T_c$) la tendenza all'ordinamento prevale e si stabilisce un [[Ordine e Disordine|ordine]] a lungo raggio con [[Magnetizzazione spontanea|magnetizzazione spontanea]]. Al di sopra della [[Temperatura critica|temperatura critica]] $T_c$ il sistema rimane macroscopicamente disordinato, anche se a piccole scale esistono [[Domini magnetici|domini magnetici]] correlati di dimensione finita.

## Collegamenti

- [[Transizioni di Fase]] - Transizioni ordine-disordine e proprietà critiche.
- [[Spins]] - Variabili di stato del modello.
- [[Magnetizzazione spontanea]] - Ordine a lungo raggio al di sotto di $T_c$.
- [[Temperatura critica]] - Temperatura $T_c$ oltre la quale l'ordine scompare.
- [[Ordine e Disordine]] - Concetti fondamentali di organizzazione nei sistemi.
- [[Domini magnetici]] - Regioni di spin correlati sopra $T_c$.
- [[Algoritmo Metropolis]] - Metodo Monte Carlo per la simulazione.
- [[Modelli ad Agente]] - Il modello di Ising come esempio precoce di sistema di agenti interagenti.
