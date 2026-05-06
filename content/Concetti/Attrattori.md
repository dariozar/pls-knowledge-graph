---
title: Attrattori
date: 2024-05-02
tags:
  - concetto
  - caos
  - sistemi-complessi
  - matematica
  - geometria
aliases:
  - Attractors
  - Attrattore strano
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_03.pptx
---

# Attrattori

> [!definition] Attrattore
> Un attrattore è un insieme chiuso $A$ nello spazio delle fasi verso cui convergono tutte le traiettorie che partono da condizioni iniziali sufficientemente vicine. Più precisamente, un attrattore soddisfa tre proprietà:
> 1. **Invarianza**: ogni traiettoria che inizia in $A$ vi rimane per tutti i tempi.
> 2. **Attrazione**: esiste un intorno aperto $U$ di $A$ tale che se $x(0) \in U$, la distanza di $x(t)$ da $A$ tende a zero per $t \to \infty$. Il più grande tale $U$ è chiamato bacino di attrazione.
> 3. **Minimalità**: non esiste alcun sottoinsieme proprio di $A$ che soddisfi le due proprietà precedenti.

## Tipi di attrattori

| Tipo | Descrizione | Esempio |
|------|-------------|---------|
| Punto fisso | Un singolo punto stabile | Molla smorzata |
| Ciclo limite | Traiettoria periodica stabile | Oscillatore di van der Pol |
| Toro | Moto quasi-periodico su un toro | Sistema con due frequenze incommensurabili |
| Attrattore strano | Insieme frattale con caos | [[Modello di Lorenz]], [[Mappa di Henon]] |

## Attrattori strani

> [!definition] Attrattore strano
> Gli attrattori strani sono attrattori con dimensione frattale (non intera). Sono caratteristici dei sistemi caotici e possiedono una struttura geometrica complessa:
- Sono invarianti per la dinamica.
- Attraggono un insieme aperto di condizioni iniziali.
- Mostrano sensibilità alle condizioni iniziali all'interno dell'attrattore.
- Hanno dimensione di Hausdorff frazionaria.

## Esempi notevoli

- **Attrattore di Lorenz**: forma a farfalla, generato dal [[Modello di Lorenz|modello di Lorenz]].
- **Attrattore di Henon**: struttura a foglia, generato dalla [[Mappa di Henon|mappa di Henon]].
- **Attrattore di Rössler**: sistema continuo più semplice del Lorenz.

## Esempio: cosa NON è un attrattore

Consideriamo il sistema $\dot{x} = x - x^3$, $\dot{y} = -y$. L'intervallo $I = \{ -1 < x < 1, y = 0 \}$ è invariante e attrae tutte le traiettorie, ma **non è un attrattore** perché non è minimale: i punti fissi stabili $(\pm 1, 0)$ sono sottoinsiemi propri che soddisfano anch'essi le proprietà di invarianza e attrazione.

## Collegamenti

- [[Modello di Lorenz]] - Genera l'attrattore di Lorenz.
- [[Mappa di Henon]] - Genera l'attrattore di Henon.
- [[Caos deterministico]] - Gli attrattori strani sono la geometria del caos.
- [[Biforcazioni]] - Le biforcazioni cambiano il tipo di attrattore.
