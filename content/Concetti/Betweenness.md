---
title: Betweenness
date: 2024-05-16
tags:
  - concetto
  - reti
  - networks
  - metriche
  - centralità
aliases:
  - Intermediazione
  - Betweenness Centrality
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_07.pptx
---

# Betweenness

## Betweenness di nodo

La **betweenness** è una misura di centralità di un vertice all'interno di un grafo:

1. Per ogni coppia di vertici $(s,t)$, calcolare tutti i cammini minimi tra di essi.
2. Per ogni coppia $(s,t)$, determinare la frazione di cammini minimi che passano attraverso il vertice in esame (qui, vertice $v$).
3. Sommare questa frazione su tutte le coppie di vertici $(s,t)$.

## Betweenness di arco

Analogamente, la **betweenness di arco** è una misura di centralità di un arco:

1. Per ogni coppia di vertici $(s,t)$, calcolare tutti i cammini minimi tra di essi.
2. Per ogni coppia $(s,t)$, determinare la frazione di cammini minimi che passano attraverso l'arco in questione (qui, arco $e$).
3. Sommare questa frazione su tutte le coppie di vertici $(s,t)$.

## Esempio: nodi "go-through" vs nodi di partenza/arrivo

Nelle reti di trasporto, la betweenness distingue nodi che sono semplicemente attraversati (go-through nodes, ad esempio Piazza Indipendenza) dai nodi di partenza/arrivo (ad esempio Belgio/Strasburgo).

## Collegamenti
- [[Shortest Path]] - Base per il calcolo della betweenness
- [[Degree]] - Altra metrica di centralità
- [[Reti e Topologia]] - Panoramica sulle reti
- [[Immunization on networks]] - Rimozione nodi ad alta betweenness
