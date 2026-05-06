---
title: Sito percolazione vs Legame percolazione
date: 2024-05-14
tags:
  - concetto
  - percolazione
  - reticolo
  - tipologie
aliases:
  - Site percolation vs Bond percolation
  - Percolazione di sito
  - Percolazione di legame
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_06.pptx
---

# Sito percolazione vs Legame percolazione

Esistono due tipologie principali di percolazione su reticolo: la **percolazione di sito** (*site percolation*) e la **percolazione di legame** (*bond percolation*).

## Percolazione di sito (Site percolation)

Nella percolazione di sito, ogni **nodo** (sito) del reticolo è occupato con probabilità $p$ e vuoto con probabilità $1-p$.

- Due siti occupati adiacenti sono connessi
- Il cluster è un insieme di siti occupati e adiacenti
- La soglia critica $p_c$ dipende dalla geometria del reticolo

## Percolazione di legame (Bond percolation)

Nella percolazione di legame, tutti i **siti** sono presenti, ma ogni **legame** (arco) tra siti adiacenti è presente con probabilità $p$ e assente con probabilità $1-p$.

- I siti sono sempre occupati
- Due siti sono connessi se esiste un percorso di legami presenti
- Il cluster è un insieme di siti collegati da legami presenti

## Confronto

| Aspetto | Sito percolazione | Legame percolazione |
|---------|-------------------|---------------------|
| Entità randomizzata | Siti (nodi) | Legami (archi) |
| Siti vuoti | Possibili | Impossibili |
| Soglia su reticolo quadrato 2D | $p_c \approx 0.5927$ | $p_c = 0.5$ |

## Dualità

Per alcuni reticoli esistono relazioni di dualità tra la percolazione di sito e di legame. Ad esempio, la percolazione di legame su un reticolo è dualmente correlata alla percolazione di sito sul reticolo duale.

## Collegamenti
- [[Percolazione]] - Teoria generale
- [[Soglia di percolazione]] - Soglie critiche per diversi reticoli
- [[Reti e Topologia]] - Struttura dei grafi e reticoli
