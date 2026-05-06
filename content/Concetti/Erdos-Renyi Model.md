---
title: Erdos-Renyi Model
date: 2024-05-16
tags:
  - concetto
  - reti
  - networks
  - modelli
  - random
aliases:
  - Modello di Erdos-Renyi
  - Random Network
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_07.pptx
---

# Erdos-Renyi Model

## Definizione

Nel **modello di Erdos-Renyi** (ER), ogni coppia di nodi è collegata con una probabilità $p$ fissata, indipendentemente dalle altre coppie.

## Parametri

- $n$: numero di nodi
- $p$: probabilità di connessione
- Grado medio: $\langle d \rangle = z = p(n-1)$

## Distribuzione del grado

Per $n$ grande e $z$ costante, la distribuzione del grado segue una **distribuzione di Poisson**:

$$P(k) = \frac{z^k e^{-z}}{k!}$$

> [!info] Coda esponenziale
> La coda della distribuzione del grado decade rapidamente (esponenzialmente). Questo significa che è molto improbabile trovare nodi con grado molto alto.

## Collegamenti
- [[Barabasi-Albert Model]] - Confronto con reti scale-free
- [[Degree]] - Distribuzione del grado
- [[Reti e Topologia]] - Panoramica sui modelli di rete
- [[Immunization on networks]] - Soglia di immunizzazione nelle reti ER
