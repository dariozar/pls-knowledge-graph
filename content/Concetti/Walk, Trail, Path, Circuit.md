---
title: "Walk, Trail, Path, Circuit"
date: 2024-05-16
tags:
  - concetto
  - reti
  - networks
  - grafi
  - topologia
aliases:
  - Cammini e Percorsi
  - Walks and Paths
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_07.pptx
---

# Walk, Trail, Path, Circuit

## Walk (Cammino)

Un **walk** su un grafo $G$ da $v_0$ a $v_n$ è il percorso associato alla sequenza
$$v_0, e_1, v_1, e_2, v_2, \dots, e_n, v_n$$
dove l'arco $e_i$ connette i vertici $\{v_{i-1}, v_i\}$.

Un walk con $n$ archi ha lunghezza $n$.

## Trail (Sentiero)

Un walk senza archi ripetuti è chiamato **trail**.

## Path (Percorso)

Un trail senza vertici ripetuti è chiamato **path**.

## Circuit

Un trail che inizia e termina nello stesso vertice è chiamato **circuit**.

## Cycle (Ciclo)

Un walk di lunghezza almeno tre che inizia e termina nello stesso vertice ma con tutti i vertici distinti tra loro è chiamato **cycle** (ciclo).

Grafi che non contengono cicli sono chiamati **aciclici**.

## Collegamenti
- [[Reti e Topologia]] - Panoramica sui grafi
- [[Connected Components]] - Raggiungibilità basata su walk
- [[Shortest Path]] - Path di lunghezza minima
