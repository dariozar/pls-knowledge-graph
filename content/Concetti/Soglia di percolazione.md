---
title: Soglia di percolazione
date: 2024-05-14
tags:
  - concetto
  - percolazione
  - transizioni-di-fase
  - soglia-critica
aliases:
  - Percolation threshold
  - $p_c$
  - Punto critico di percolazione
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_06.pptx
---

# Soglia di percolazione

La **soglia di percolazione** ($p_c$) è la probabilità critica di occupazione al di sopra della quale emerge un cluster di percolazione (componente gigante) che attraversa l'intero sistema.

## Definizione

Per un dato reticolo o rete, la soglia di percolazione divide due regimi fondamentali:

- **$p < p_c$**: i cluster occupati sono finiti e isolati; non esiste percorso che attraversa il sistema
- **$p = p_c$**: punto critico; emerge il cluster di percolazione con proprietà frattali
- **$p > p_c$**: esiste un unico cluster gigante che attraversa il sistema

## Valori noti

### Reticolo quadrato 2D
Per la percolazione di sito su reticolo quadrato:
$$p_c \approx 0.59274605$$

### Albero di Cayley (Rete di Bethe)
Per un albero di Cayley con numero di coordinazione $z$:
$$p_c = \frac{1}{z-1}$$

Ad esempio, per $z = 3$:
$$p_c = \frac{1}{2} = 0.5$$

## Significato fisico

La soglia di percolazione rappresenta una **transizione di fase geometrica**: al variare del parametro di controllo $p$, il sistema passa bruscamente da uno stato in cui non esiste connettività globale a uno stato in cui essa è presente.

Questa transizione è analoga alle transizioni di fase termodinamiche (es. magnetizzazione spontanea), ma in questo caso l'ordine è di natura puramente geometrica/topologica.

## Collegamenti
- [[Percolazione]] - Teoria generale della percolazione
- [[Parametro d'ordine]] - Probabilità di occupazione $p$
- [[Componente gigante]] - Cluster che emerge sopra $p_c$
- [[Probabilità di spanning]] - Probabilità di appartenere al cluster infinito
- [[Esponenti critici]] - Comportamento universale vicino a $p_c$
