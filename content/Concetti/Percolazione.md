---
title: Percolazione
date: 2024-05-14
tags:
  - concetto
  - percolazione
  - transizioni-di-fase
  - fisica
  - reti
  - networks
aliases:
  - Percolation
  - Teoria della Percolazione
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_06.pptx
---

# Percolazione

## Definizione intuitiva

La **percolazione** è il fenomeno per cui un flusso (ad esempio di acqua) attraversa un mezzo poroso.

## Definizione formale

Si consideri una roccia con molte piccole cavità. Si pongano casualmente cavità sferiche di raggio $r$ in un mezzo, permettendo loro di sovrapporsi. A quale frazione di volume delle cavità l'acqua è in grado di percorrere distanze arbitrariamente lunghe attraverso il mezzo?

## Parametro d'ordine

La frazione $r = V_{\text{cavity}} / V_{\text{medium}}$ è chiamata **parametro d'ordine**.

## Tipologie di percolazione

### Percolazione continua (continuum percolation)

Le cavità sono distribuite arbitrariamente nello spazio continuo, senza vincoli di reticolo.

### Percolazione su reticolo (lattice percolation)

La maggior parte della teoria della percolazione tratta la percolazione su reticoli. Si considera un reticolo quadrato: la probabilità che un dato sito sia una "cavità" è una probabilità fissa $q$ (o $p$).

- **Sito percolazione** (*site percolation*): i siti del reticolo sono occupati con probabilità $p$
- **Legame percolazione** (*bond percolation*): i legami (archi) del reticolo sono occupati con probabilità $p$

### Percolazione su reti complesse

Nel contesto delle reti complesse, la percolazione si riferisce a un comportamento emergente a livello di rete, probabilistico, tra siti attraverso la rete che causa la formazione di una grande componente gigante (*giant component*).

## Soglia di percolazione

Esiste una **soglia critica** $p_c$ tale che:
- Per $p > p_c$: esiste un cluster che attraversa tutto il sistema (componente gigante)
- Per $p = p_c$: il sistema è al punto critico
- Per $p < p_c$: non esiste percolazione

Per il reticolo quadrato 2D, si ritiene generalmente che:
$$p_c \approx 0.59274605$$

Per un albero di Cayley con coordinazione $z$:
$$p_c = \frac{1}{z-1}$$

## Dimensione frattale del cluster

La massa $M$ di un cluster di percolazione scala con la dimensione tipica $L$ del sistema in modo diverso a seconda del regime:

$$M \sim L^D$$

dove $D$ è la **dimensione frattale** del cluster, con $D < d$ (dimensione dello spazio).

Per $p > p_c$: $M \sim L^d$ (oggetto compatto, $D = d$)
Per $p = p_c$: $M \sim L^D$ con $D < d$ (oggetto frattale)
Per $p < p_c$: $M \sim \ln L$ (cluster finiti)

## Collegamenti
- [[Soglia di percolazione]] - Soglia critica $p_c$
- [[Parametro d'ordine]] - Frazione di siti/legami occupati
- [[Componente gigante]] - Cluster che attraversa il sistema
- [[Albero di Cayley]] - Soluzione esatta della percolazione
- [[Probabilità di spanning]] - Probabilità di appartenere al cluster infinito
- [[Esponenti critici]] - Esponenti della transizione di fase
- [[Dimensione frattale del cluster]] - Proprietà geometrica al punto critico
- [[Connected Components]] - Componente gigante nelle reti
- [[Immunization on networks]] - Rimozione di nodi come percolazione
- [[Networked SIR Model]] - Diffusione e percolazione
- [[Reti e Topologia]] - Panoramica sulle reti
- [[Sistemi Termodinamici]] - Transizioni di fase
