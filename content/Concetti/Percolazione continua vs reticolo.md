---
title: Percolazione continua vs reticolo
date: 2024-05-14
tags:
  - concetto
  - percolazione
  - geometria
  - continuo
  - reticolo
aliases:
  - Continuum vs lattice percolation
  - Percolazione continua
  - Percolazione su reticolo
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_06.pptx
---

# Percolazione continua vs reticolo

La teoria della percolazione si applica a due contesti geometrici fondamentalmente diversi: la **percolazione continua** (o *continuum percolation*) e la **percolazione su reticolo** (*lattice percolation*).

## Percolazione continua

Nella percolazione continua, le cavità (o gli ostacoli) sono distribuite arbitrariamente nello spazio continuo, senza vincoli di un reticolo sottostante.

### Esempio classico
Si consideri una roccia con cavità sferiche di raggio $r$ posizionate casualmente nel mezzo, con possibile sovrapposizione. La domanda fondamentale è: a quale frazione di volume delle cavità l'acqua è in grado di percorrere distanze arbitrariamente lunghe?

### Caratteristiche
- Gli oggetti sono distribuiti nello spazio continuo $\mathbb{R}^d$
- Non esiste una struttura reticolare sottostante
- Le cavità possono sovrapporsi
- Il parametro di controllo è tipicamente la frazione di volume $r = V_{\text{cavity}} / V_{\text{medium}}$

## Percolazione su reticolo

Nella percolazione su reticolo, i siti (o i legami) di un reticolo regolare sono occupati con una data probabilità $p$.

### Esempio classico
Si consideri un reticolo quadrato bidimensionale. Ogni cella quadrata è una "cavità" con probabilità fissa $p$. La domanda è: qual è il valore di $p$ tale che esista un percorso da un lato all'altro del reticolo?

### Caratteristiche
- La geometria è discreta e regolare
- I siti/legami sono occupati in modo indipendente con probabilità $p$
- La struttura del reticolo (quadrato, triangolare, esagonale, cubico, ...) influenza la soglia critica
- La maggior parte della teoria matematica si concentra su questo caso

## Confronto

| Aspetto | Percolazione continua | Percolazione su reticolo |
|---------|----------------------|--------------------------|
| Spazio | Continuo $\mathbb{R}^d$ | Discreto (reticolo) |
| Randomizzazione | Posizione/dimensione degli oggetti | Occupazione dei siti/legami |
| Teoria | Più complessa, meno sviluppata | Più semplice, ben sviluppata |
| Esempio | Mezzi porosi, compositi | Reticoli cristallini, reti |

## Collegamenti
- [[Percolazione]] - Teoria generale
- [[Sito percolazione vs Legame percolazione]] - Tipologie su reticolo
- [[Soglia di percolazione]] - Soglie critiche nei diversi contesti
