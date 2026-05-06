---
title: Immunization on networks
date: 2024-05-16
tags:
  - concetto
  - reti
  - networks
  - epidemie
  - immunizzazione
aliases:
  - Immunizzazione su Reti
  - Network Immunization
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_07.pptx
---

# Immunization on networks

## Problema

Quanti nodi devono essere immunizzati per evitare un'epidemia?

Si consideri una società di $n$ individui connessi attraverso una rete. Se un nodo è inizialmente infetto, la malattia può diffondersi in una frazione non trascurabile della popolazione? Questo problema può essere mappato in un problema di **percolazione**.

## Condizione di Molloy-Reed

La condizione per l'emergere di una componente gigante in una rete con distribuzione di grado $P(k)$ è:

$$\frac{\langle k^2 \rangle}{\langle k \rangle} > 2$$

## Rimozione di nodi (immunizzazione)

Se una frazione $\pi$ di nodi viene rimossa (immunizzata), la nuova distribuzione di grado $P_\pi(d)$ si ottiene considerando la probabilità binomiale che un nodo di grado $d'$ perda $d'-d$ vicini.

## Risultati per diverse reti

### Rete regolare con grado $d_1$
- $d_1=2$: $\pi=0$ (la componente gigante esiste sempre)
- $d_1=3$: $\pi=1/2$ (se meno della metà è immune, emerge la componente gigante)

### Rete Erdos-Renyi
- La soglia dipende dal grado medio

### Rete scale-free
- $\langle k^2 \rangle$ diverge
- Nel limite $\pi \to 1$: in una rete scale-free infinita **tutti i nodi devono essere immunizzati** per far scomparire la componente gigante
- Per reti finite, $\langle k^2 \rangle$ è finito (anche se molto grande), quindi il numero di nodi da immunizzare è elevato ma inferiore al 100%

## Collegamenti
- [[Percolazione]] - Teoria della percolazione
- [[SIR Model]] - Modello epidemico
- [[Networked SIR Model]] - Diffusione su reti
- [[Erdos-Renyi Model]] - Reti random
- [[Barabasi-Albert Model]] - Reti scale-free
- [[Reti e Topologia]] - Panoramica sulle reti
