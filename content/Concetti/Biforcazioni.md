---
title: Biforcazioni
date: 2024-05-02
tags:
  - concetto
  - caos
  - sistemi-complessi
  - matematica
  - transizione
aliases:
  - Bifurcations
  - Diagramma delle biforcazioni
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_03.pptx
---

# Biforcazioni

> [!definition] Biforcazioni
> Una biforcazione è una brusca varia qualitativa del comportamento di un sistema dinamico al variare di un parametro. Nel contesto della [[Mappa Logistica|mappa logistica]] e dei sistemi caotici, le biforcazioni rappresentano i punti in cui il sistema passa da un regime stabile (punto fisso) a uno oscillante (ciclo limite) e infine a uno caotico.

## Biforcazioni nella mappa logistica

Nella mappa logistica $x_{n+1} = r x_n (1 - x_n)$, al crescere del parametro $r$ si osserva una successione di biforcazioni:

- **$r < 3$**: un unico punto fisso stabile.
- **$r = 3$**: prima biforcazione — il punto fisso diventa instabile e nasce un ciclo di periodo 2.
- **$3 < r < 1 + \sqrt{6} \approx 3.449$**: ciclo di periodo 2 stabile.
- **$r \approx 3.449$**: seconda biforcazione — raddoppio del periodo a 4.
- **Successione infinita**: la frequenza dei raddoppi aumenta geometricamente.

## Costante di Feigenbaum

La successione di biforcazioni a raddoppio di periodo è governata dalla costante di Feigenbaum:

$$\delta = \lim_{n \to \infty} \frac{r_n - r_{n-1}}{r_{n+1} - r_n} \approx 4.669...$$

Questa costante è universale: la stessa per una vasta classe di mappe unimodali, indipendentemente dai dettagli specifici dell'equazione.

## Diagramma delle biforcazioni

Il diagramma delle biforcazioni mostra, per ogni valore di $r$, i valori asintotici di $x$. È una delle figure più iconiche della teoria del caos, con la sua struttura a "albero" che si dirama sempre più finemente.

All'interno del regime caotico si trovano anche "finestre di periodicità" dove il sistema torna temporaneamente a comportamenti periodici.

## Collegamenti

- [[Mappa Logistica]] - Il paradigma delle biforcazioni a raddoppio di periodo.
- [[Caos deterministico]] - Le biforcazioni sono la via verso il caos.
- [[Nonlinearità]] - La nonlinearità è necessaria per le biforcazioni.
- [[Attrattori]] - Ogni regime ha il suo attrattore (punto fisso, ciclo limite, attrattore strano).
