---
title: Watts-Strogatz Model
date: 2024-05-16
tags:
  - concetto
  - reti
  - networks
  - modelli
  - small-world
aliases:
  - Modello di Watts-Strogatz
  - Small-World Networks
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_07.pptx
---

# Watts-Strogatz Model

## Definizione

Il **modello di Watts-Strogatz** (WS) genera reti **small-world**, caratterizzate da un alto clustering coefficient e da un basso average path length.

## Meccanismo

1. Si parte da un anello regolare in cui ogni nodo è connesso ai suoi $k$ vicini più prossimi.
2. Ogni arco viene "ri-cablato" (rewired) con probabilità $p$ verso un nodo scelto a caso.

## Proprietà

- **Nodi localmente connessi**: alta densità di triangoli (alto clustering)
- **Legami deboli** (weak ties): pochi collegamenti a lunga distanza che collegano tra loro gruppi locali
- **Piccolo diametro**: anche per $p$ piccolo, il diametro della rete diminuisce drasticamente

## Motivazione

Le reti small-world spiegano il fenomeno dei "sei gradi di separazione": in molte reti sociali reali, due persone qualsiasi sono collegate da un breve cammino.

## Collegamenti
- [[Erdos-Renyi Model]] - Confronto con reti random
- [[Barabasi-Albert Model]] - Confronto con reti scale-free
- [[Clustering Coefficient]] - Alta transitività
- [[Diametro della rete]] - Basso diametro
- [[Reti e Topologia]] - Panoramica sui modelli di rete
