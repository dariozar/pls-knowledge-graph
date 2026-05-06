---
title: Parametro d'ordine
date: 2024-05-14
tags:
  - concetto
  - percolazione
  - transizioni-di-fase
  - ordine
aliases:
  - Order parameter
  - Frazione di occupazione
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_06.pptx
---

# Parametro d'ordine

Il **parametro d'ordine** nella teoria della percolazione è la grandezza che misura il grado di "ordine" o connettività del sistema e che cambia in modo non analitico (o con una discontinuità nella derivata) alla soglia critica.

## Definizione nella percolazione

Nella percolazione continua, il parametro d'ordine è la frazione di volume delle cavità:

$$r = \frac{V_{\text{cavity}}}{V_{\text{medium}}}$$

Nella percolazione su reticolo, il parametro di controllo è la probabilità di occupazione $p$ (dei siti o dei legami), mentre il parametro d'ordine vero e proprio è la **probabilità di spanning** $P(p)$, ovvero la frazione di siti appartenenti al cluster di percolazione infinito.

## Comportamento critico

Vicino alla soglia di percolazione $p_c$, il parametro d'ordine $P(p)$ si annulla con una legge di potenza:

$$P(p) \sim (p - p_c)^{\beta}$$

Dove $\beta$ è un **esponente critico**. Per l'albero di Cayle (approccio mean-field):
$$\beta = 1$$

Questo comportamento è analogo a quello della magnetizzazione spontanea in un ferromagnete vicino alla temperatura critica.

## Significato fisico

Il parametro d'ordine distingue le due fasi:
- **Fase disordinata** ($p < p_c$): $P(p) = 0$, non c'è connettività globale
- **Fase ordinata** ($p > p_c$): $P(p) > 0$, esiste un cluster che attraversa il sistema

## Collegamenti
- [[Percolazione]] - Teoria generale
- [[Soglia di percolazione]] - Punto critico $p_c$
- [[Probabilità di spanning]] - Frazione nel cluster infinito
- [[Esponenti critici]] - Esponente $\beta$ e altri
- [[Sistemi Termodinamici]] - Transizioni di fase termodinamiche
