---
title: Connected Components
date: 2024-05-16
tags:
  - concetto
  - reti
  - networks
  - grafi
  - connettività
aliases:
  - Componenti Connesse
  - Connettività
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_07.pptx
---

# Connected Components

## Definizione di connettività

Un grafo $G$ si dice **connesso** se ogni vertice è raggiungibile da ogni altro vertice.

> [!definition] Raggiungibilità
> Un vertice $v$ è raggiungibile da un vertice $u$ se esiste almeno un walk che connette $u$ a $v$.

## Componente connessa

Una **componente** di un grafo è un sottografo **massimalmente connesso**.

> [!info] Largest Connected Component (LCC)
> La componente con il maggior numero di vertici è chiamata **largest connected component** (LCC) o componente gigante.

## Connettività nei digrafi

Nel caso dei grafi diretti, il concetto di connettività si specializza in due casi:

- **Debolmente connesso** (weakly connected): il grafo non diretto sottostante è connesso
- **Fortemente connesso** (strongly connected): ogni vertice $v$ è raggiungibile da ogni vertice $u$ attraverso un walk diretto

## Collegamenti
- [[Reti e Topologia]] - Panoramica sulle reti
- [[Walk, Trail, Path, Circuit]] - Walk come base della raggiungibilità
- [[Percolazione]] - Emergenza della componente gigante
- [[Immunization on networks]] - Rimozione di nodi e frammentazione della componente gigante
