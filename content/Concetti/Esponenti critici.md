---
title: Esponenti critici
date: 2024-05-14
tags:
  - concetto
  - percolazione
  - transizioni-di-fase
  - esponenti
  - universality
aliases:
  - Critical exponents
  - Esponenti della percolazione
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_06.pptx
---

# Esponenti critici

Gli **esponenti critici** descrivono il comportamento delle grandezze fisiche nella vicinanza della soglia di percolazione $p_c$. Essi caratterizzano la natura universale della transizione di fase geometrica.

## Esponenti principali

### Esponente $\beta$ (parametro d'ordine)
La probabilità di spanning (parametro d'ordine) si annulla come:
$$P(p) \sim (p - p_c)^{\beta} \quad \text{per } p \to p_c^+$$

### Esponente $\gamma$ (dimensione media dei cluster)
La dimensione media dei cluster finiti diverge come:
$$S \sim |p - p_c|^{-\gamma} \quad \text{per } p \to p_c$$

### Esponente $\tau$ (distribuzione delle dimensioni dei cluster)
Il numero di cluster di dimensione $s$ per sito segue una legge di potenza:
$$n_s \sim s^{-\tau} \quad \text{per } s \text{ grande, a } p = p_c$$

### Esponenti $\sigma$ e relazioni di scala
Vicino a $p_c$, la distribuzione delle dimensioni dei cluster obbedisce all'**ansatz di scaling**:
$$n_s(p) \sim s^{-\tau} f\big((p - p_c) s^{\sigma}\big)$$

Dove $f$ è una funzione di scaling universale.

## Valori mean-field (Albero di Cayley)

Nell'albero di Cayley (limite mean-field, $d \to \infty$):
- $\beta = 1$
- $\gamma = 1$
- $\tau = 5/2$
- $\sigma = 1/2$

## Relazioni di scala (Scaling laws)

Gli esponenti critici non sono indipendenti, ma soddisfano relazioni di scala. Una fondamentale è la **relazione di Fisher**:
$$\tau = \sigma \beta + \gamma$$

O equivalentemente:
$$\tau = 2 + \sigma \beta$$

## Universality

Gli esponenti critici dipendono solo dalla:
- Dimensione dello spazio $d$
- Tipo di percolazione (sito vs legame)

Ma **non** dipendono dalla struttura microscopica del reticolo (es. quadrato vs triangolare) né dai dettagli della distribuzione di probabilità. Questa proprietà è detta **universalità**.

## Collegamenti
- [[Percolazione]] - Teoria generale
- [[Soglia di percolazione]] - Punto critico $p_c$
- [[Parametro d'ordine]] - Esponente $\beta$
- [[Legge di scaling]] - Ansatz di scaling e relazioni
- [[Esponente di Fisher]] - Relazione fondamentale tra esponenti
- [[Sistemi Termodinamici]] - Universalità nelle transizioni di fase
