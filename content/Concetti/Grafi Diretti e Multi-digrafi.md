---
title: Grafi Diretti e Multi-digrafi
date: 2024-05-16
tags:
  - concetto
  - reti
  - networks
  - grafi
  - diretti
aliases:
  - Directed Graphs
  - Digraphs
  - Multi-digraphs
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_07.pptx
---

# Grafi Diretti e Multi-digrafi

## Grafi diretti (Digraph)

Un grafo in cui la relazione tra il vertice $u$ e il vertice $v$ presenta una direzionalità è chiamato **grafo diretto** o **digraph**.

> [!definition] Arco
> Nei grafi diretti gli archi sono chiamati **archi diretti** o **archi orientati** (arcs). In un grafo diretto l'arco $\{u,v\}$ è diverso dall'arco $\{v,u\}$. Convenzionalmente, la notazione $\{u,v\}$ si legge: dalla coda $u$ alla testa $v$.

## Multi-digrafi

Quando si osserva più di un tipo di arco diretto tra due vertici, si è in presenza di un **multi-digrafo**.

> [!note] Mutualità
> In un digrafo semplice si possono avere fino a 2 archi diretti tra due vertici. Quando entrambi sono presenti, si dice che i due archi sono **mutui** (mutual).

## Collegamenti
- [[Reti e Topologia]] - Panoramica generale sulle reti
- [[Degree]] - In-degree e out-degree nei grafi diretti
- [[Adjacency Matrix]] - Matrice di adiacenza non simmetrica per digrafi
- [[Connected Components]] - Connettività debole e forte
