---
title: Invarianza di Scala
date: 2026-03-26
tags:
  - fisica-statistica
  - scaling
  - leggi-di-potenza
aliases:
  - Scaling
  - Scale Invariance
source: Lezione 01 - Introduzione alla Complessità
---
> [!definition] Invarianza di scala
> L'invarianza di scala (o scaling) è una proprietà di sistemi fisici, biologici, biomedici, ecc., che si osserva quando sono descritti da una legge funzionale che non cambia forma se si scalano le scale tipiche o dimensioni, a meno di un fattore comune. Il caso più tipico è dato da sistemi in cui certe proprietà sono descritte da [[leggi di potenza]]: $f(x) = A x^\alpha$.

Quando un sistema è invariante di scala, significa che non ha una scala tipica o una dimensione tipica; al contrario, tutte le scale/dimensioni sono presenti nel sistema. L'invarianza di scala si manifesta in diversi contesti: scale spaziali (geometrie frattali), scale temporali (cluster di spin senza dimensione tipica), e sistemi alla criticità (transizioni di fase di primo ordine con Cv divergente).

> [!info] Esempi di scaling
> 1. **Scale spaziali**: le geometrie frattali sono invariate sotto trasformazioni di scala; la lunghezza di una costa misurata con un righello di lunghezza $l$ segue $L(l) \propto l^{1-D}$, dove $D$ è la dimensione frattale.
> 2. **Sistemi alla criticità**: nelle transizioni di fase di secondo ordine, le grandezze termodinamiche seguono leggi di potenza vicino al punto critico. Ad esempio, la suscettibilità magnetica $\chi \propto |T-T_c|^{-\gamma}$.
> 3. **Scale temporali**: cluster di spin in sistemi magnetici hanno dimensioni che crescono a legge di potenza senza dimensione tipica, caratterizzando sistemi superdiffusivi con memoria a lungo raggio.

## Collegamenti

- [[Leggi di Potenza]] - La forma matematica tipica dell'invarianza di scala.
- [[Sistemi Complessi]] - I sistemi complessi spesso presentano invarianza di scala.
- [[Fenomeni Emergenti]] - L'emergenza è spesso associata a scaling.
- [[Sistemi Termodinamici]] - Le transizioni di fase sono esempi di scaling.