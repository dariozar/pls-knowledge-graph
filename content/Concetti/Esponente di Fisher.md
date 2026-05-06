---
title: Esponente di Fisher
date: 2024-05-14
tags:
  - concetto
  - percolazione
  - transizioni-di-fase
  - esponenti
  - scaling
aliases:
  - Fisher exponent
  - Relazione di Fisher
  - Fisher scaling relation
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_06.pptx
---

# Esponente di Fisher

L'**esponente di Fisher** è legato alla **relazione di scaling** che collega gli esponenti critici della distribuzione delle dimensioni dei cluster nella teoria della percolazione.

## Relazione di Fisher

La relazione di Fisher stabilisce che:

$$\tau = \sigma \beta + \gamma$$

O, in forma alternativa:

$$\tau = 2 + \sigma \beta$$

Dove:
- $\tau$ è l'esponente della distribuzione delle dimensioni dei cluster a $p_c$
- $\sigma$ è l'esponente di scaling della variabile $(p - p_c)s^{\sigma}$
- $\beta$ è l'esponente del parametro d'ordine
- $\gamma$ è l'esponente della dimensione media dei cluster finiti

## Significato fisico

La relazione di Fisher riflette il fatto che gli esponenti critici non sono indipendenti, ma sono legati dalla struttura dell'ansatz di scaling. Essa garantisce la **consistenza** tra:
- Il comportamento della distribuzione dei cluster $n_s(p)$
- La divergenza della dimensione media dei cluster $S \sim |p - p_c|^{-\gamma}$
- L'andamento del parametro d'ordine $P(p) \sim (p - p_c)^{\beta}$

## Verifica nell'albero di Cayley

Per l'albero di Cayley, gli esponenti mean-field sono:
- $\beta = 1$
- $\gamma = 1$
- $\tau = 5/2$
- $\sigma = 1/2$

Sostituendo nella relazione di Fisher:
$$\tau = 2 + \sigma \beta = 2 + \frac{1}{2} \cdot 1 = \frac{5}{2}$$

Il che è consistente con il valore di $\tau$.

## Collegamenti
- [[Percolazione]] - Teoria generale
- [[Esponenti critici]] - Gli esponenti $\beta$, $\gamma$, $\tau$, $\sigma$
- [[Legge di scaling]] - Ansatz di scaling e relazioni
- [[Sistemi Termodinamici]] - Universalità nelle transizioni di fase
