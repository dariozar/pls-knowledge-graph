---
title: Insieme di Cantor
date: 2024-05-07
tags:
  - concetto
  - frattali
  - geometria
  - complessità
  - matematica
aliases:
  - Cantor Set
  - Middle-third Cantor Set
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_04.pptx
---

# Insieme di Cantor

L'**insieme di Cantor** (o *middle-third Cantor set*) è forse l'oggetto geometrico più semplice che meriti di essere chiamato frattale. È costruito partendo dall'intervallo unitario $[0,1]$ e rimuovendo iterativamente il terzo medio di ogni intervallo rimanente.

## Costruzione

1. **Passo 0**: si parte dall'intervallo $[0,1]$.
2. **Passo 1**: si rimuove il terzo medio $(1/3, 2/3)$, rimangono due intervalli: $[0, 1/3]$ e $[2/3, 1]$.
3. **Passo 2**: si rimuove il terzo medio da ciascuno dei due intervalli rimanenti, ottenendo 4 intervalli di lunghezza $1/9$.
4. **Passo n**: $K_n$ consiste di $2^n$ intervalli, ciascuno di lunghezza $1/3^n$.

L'insieme di Cantor $K$ è l'intersezione di tutti gli $K_n$.

## Proprietà

### Lunghezza zero

La lunghezza totale di $K_n$ è $(2/3)^n$, che tende a 0 per $n \to \infty$. Poiché $K$ è contenuto in ogni $K_n$, si dice che $K$ ha **lunghezza zero** (o [[Misura di un insieme|misura zero]]).

> Esempio: $K_{40}$ ha lunghezza minore di $10^{-6}$.

### Insieme non numerabile

Cantor estese l'idea del contare: un insieme è **numerabile** se può essere messo in corrispondenza biunivoca con i numeri naturali. L'insieme di Cantor è **non numerabile** (*uncountable*), pur avendo misura zero.

Questo mostra la distinzione fondamentale tra "insieme poroso" e "insieme continuo": entrambi possono avere misura diversa anche se intuitivamente sembrano "piccoli" o "grandi" in modi diversi.

## Dimensione frattale

La [[Dimensione frattale|dimensione per box-counting]] dell'insieme di Cantor è:

$$
\text{boxdim}(K) = \frac{\ln 2}{\ln 3} \approx 0.631
$$

Questa dimensione frazionaria riflette il fatto che l'insieme è "più grande" di un punto (dimensione 0) ma "più piccolo" di una linea (dimensione 1).

## Collegamenti

- [[Frattali]] - L'insieme di Cantor è l'esempio classico di frattale.
- [[Misura di un insieme]] - Ha misura zero ma è non numerabile.
- [[Dimensione frattale]] - Esempio calcolabile di dimensione non intera.
- [[Auto-similarità]] - L'insieme è esattamente auto-simile: ogni parte è una copia scalata dell'intero.
