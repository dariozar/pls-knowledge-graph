---
title: Reti e Topologia
date: 2024-05-16
tags:
  - fisica-statistica
  - reti
  - teoria-dei-grafi
  - networks
  - complessità
aliases:
  - Networks and Topology
  - Grafi
  - Reti Complesse
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_07.pptx
---

# Reti e Topologia

> [!definition] Rete (grafo)
> Una rete (o grafo) $G=(V,E)$ è un oggetto matematico costituito da un insieme $V$ di vertici (o nodi) e un insieme $E$ di archi (o link). Gli archi sono definiti come coppie non ordinate $\{u,v\}$ di vertici distinti. Il numero di vertici $N_V$ è detto ordine del grafo, mentre il numero di archi $N_E$ è detto dimensione.

I nodi rappresentano entità (es. persone, aeroporti, neuroni, pagine web) e i link rappresentano relazioni o interazioni tra di esse. La topologia di una rete descrive il pattern di connessioni, indipendentemente dalla posizione geometrica dei nodi. Le reti sono un linguaggio universale per descrivere sistemi complessi.

> [!info] Esempi di reti complesse
> - Internet (mappa parziale disponibile su opte.org)
>- Reti sociali (Facebook, Twitter/X)
>- Reti di trasporto (compagnie aeree, metropolitane)
>- Reti biologiche (interazioni proteiche, reti neurali)
>- Reti di collaborazione (co-autori scientifici)

## Tipologie di grafi

- [[Grafi Diretti e Multi-digrafi]] - Grafi con archi diretti (digraph) e multi-digrafi
- [[Weighted Graphs]] - Grafi con pesi sugli archi
- [[Bipartite Networks]] - Grafi bipartiti con proiezioni
- [[Clique]] - Sottografi completi e grafi d-regolari
- [[Walk, Trail, Path, Circuit]] - Definizioni di cammini e percorsi
- [[Connected Components]] - Componenti connesse, connettività debole e forte

## Metriche fondamentali

Le metriche di base che caratterizzano la topologia di una rete includono:

- [[Degree]] - Il grado di un nodo (numero di connessioni)
- [[Betweenness]] - Centralità basata sui cammini minimi (nodi e archi)
- [[Shortest Path]] - Distanza minima tra due nodi
- [[Diametro della rete]] - Massima distanza tra coppie di nodi
- [[Clustering Coefficient]] - Misura di raggruppamento locale e globale
- [[Assortatività]] - Preferenza dei nodi di collegarsi a nodi simili

## Rappresentazioni

- [[Adjacency Matrix]] - Rappresentazione matriciale del grafo
- [[Adjacency List]] - Rappresentazione tramite liste di adiacenza

## Modelli di rete

- [[Erdos-Renyi Model]] - Rete casuale con distribuzione di Poisson
- [[Barabasi-Albert Model]] - Reti scale-free con attachment preferenziale
- [[Watts-Strogatz Model]] - Reti small-world
- [[Borgatti-Everett Model]] - Modello core-periphery

## Diffusione su reti

- [[SIR Model]] - Modello compartimentale classico
- [[Networked SIR Model]] - Adattamento del modello SIR su reti di contatti
- [[Percolazione]] - Teoria della percolazione e componente gigante
- [[Immunization on networks]] - Strategie di immunizzazione su reti

## Collegamenti

- [[Correlazioni]] - Le correlazioni definiscono link in reti di componenti.
- [[Clustering Gerarchico]] - Il dendrogramma è una rete gerarchica.
- [[Sistemi Complessi]] - Le reti sono un modello per sistemi complessi.
- [[Modelli ad Agente]] - Gli agenti interagiscono in reti.
- [[Fenomeni Collettivi]] - I fenomeni collettivi si propagano nelle reti.
- [[Leggi di Potenza]] - Le reti scale-free presentano distribuzioni a legge di potenza.
- [[Invarianza di Scala]] - Proprietà di scaling nelle reti complesse.
