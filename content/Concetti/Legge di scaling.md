---
title: Legge di scaling
date: 2024-05-14
tags:
  - concetto
  - percolazione
  - transizioni-di-fase
  - scaling
  - leggi-di-potenza
aliases:
  - Scaling law
  - Ansatz di scaling
  - Relazioni di scala
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_06.pptx
---

# Legge di scaling

Le **leggi di scaling** (o *relazioni di scala*) sono relazioni matematiche che legano tra loro gli esponenti critici nella teoria della percolazione (e più in generale nelle transizioni di fase).

## Ansatz di scaling per la distribuzione dei cluster

Vicino alla soglia di percolazione $p_c$, il numero di cluster di dimensione $s$ per sito $n_s(p)$ obbedisce all'**ansatz di scaling**:

$$n_s(p) \sim s^{-\tau} f\big((p - p_c) s^{\sigma}\big)$$

Dove:
- $\tau$ è l'esponente della distribuzione delle dimensioni dei cluster a $p_c$
- $\sigma$ è l'esponente di scaling
- $f(x)$ è una funzione di scaling universale

Per $p = p_c$, la distribuzione è una pura legge di potenza:
$$n_s(p_c) \sim s^{-\tau}$$

## Divergenza della dimensione media dei cluster

La dimensione media dei cluster finiti $S$ diverge vicino a $p_c$:

$$S \sim |p - p_c|^{-\gamma}$$

Questa divergenza è coerente con l'ansatz di scaling imponendo la condizione di consistenza.

## Relazione di Fisher

Una delle relazioni di scala più importanti è la **relazione di Fisher**:

$$\tau = \sigma \beta + \gamma$$

O equivalentemente:
$$\tau = 2 + \sigma \beta$$

Questa relazione lega gli esponenti $\tau$, $\sigma$, $\beta$ e $\gamma$.

## Significato fisico

Le relazioni di scaling riflettono l'**invarianza di scala** (o *self-similarity*) del sistema al punto critico:
- Non esiste una scala caratteristica di lunghezza
- Il sistema appare statisticamente identico a diverse scale di ingrandimento
- Le grandezze fisiche obbediscono a leggi di potenza con esponenti universalmente correlati

## Collegamenti
- [[Percolazione]] - Teoria generale
- [[Esponenti critici]] - Esponenti $\beta$, $\gamma$, $\tau$, $\sigma$
- [[Esponente di Fisher]] - La relazione di Fisher
- [[Invarianza di Scala]] - Proprietà di assenza di scala caratteristica
- [[Leggi di Potenza]] - Descrizione matematica dello scaling
- [[Sistemi Termodinamici]] - Transizioni di fase e scaling
