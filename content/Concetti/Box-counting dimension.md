---
title: Box-counting dimension
date: 2024-05-07
tags:
  - concetto
  - frattali
  - geometria
  - complessità
  - matematica
aliases:
  - Dimensione per box-counting
  - Dimensione di Minkowski-Bouligand
  - Minkowski Dimension
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_04.pptx
---

# Box-counting dimension

La **box-counting dimension** (o *dimensione di Minkowski-Bouligand*) è una delle definizioni più usate e intuitive di [[Dimensione frattale|dimensione frattale]]. Si ottiene contando quante celle di una griglia di lato $\epsilon$ sono necessarie per coprire un oggetto.

## Definizione

Sia $N(\epsilon)$ il numero minimo di box (celle quadrate o cubiche) di lato $\epsilon$ necessari per coprire l'insieme. La box-counting dimension è definita come:

$$
\text{boxdim}(A) = \lim_{\epsilon \to 0} \frac{\ln N(\epsilon)}{\ln(1/\epsilon)}
$$

In pratica, si traccia $\ln N(\epsilon)$ in funzione di $\ln(1/\epsilon)$ e si calcola la pendenza asintotica per $\epsilon \to 0$.

## Esempi calcolati

### Esempio 1 – la linea continua

Per una linea di lunghezza $L$, $N(\epsilon) \approx L/\epsilon$, quindi:

$$
d = \lim_{\epsilon \to 0} \frac{\ln(L/\epsilon)}{\ln(1/\epsilon)} = 1
$$

### Esempio 2 – l'insieme di Cantor

Per l'[[Insieme di Cantor]], $K_n$ consiste di $2^n$ intervalli di lunghezza $3^{-n}$. Quindi:

$$
\text{boxdim}(K) = \lim_{n \to \infty} \frac{\ln 2^n}{\ln 3^n} = \frac{\ln 2}{\ln 3} \approx 0.631
$$

### Esempio 3 – attrattore di Hénon

Per l'[[Attrattori strani|attrattore di Hénon]]:
- con box di lato $1/8$: 177 box colpiti
- con box di lato $1/16$: 433 box colpiti
- con box di lato $1/32$: 1037 box colpiti
- con box di lato $1/64$: 2467 box colpiti
- con box di lato $1/128$: 5763 box colpiti

La pendenza limite dà $d \approx 1.27$.

## Relazione con la misura

> **Teorema**: sia $A$ un sottoinsieme limitato di $\mathbb{R}^m$ con $\text{boxdim}(A) = d < m$. Allora $A$ ha [[Misura di un insieme|misura zero]].
>
> **Dimostrazione**: $A$ è contenuto nell'unione di $N(\epsilon)$ box di lato $\epsilon$. Il volume totale è $\epsilon^m N(\epsilon) \to 0$ per $\epsilon \to 0$ poiché $m > d$.

> **Nota**: il viceversa **non** vale. Esistono sottoinsiemi numerabili dell'intervallo unitario con box-counting dimension uguale a 1 e misura zero.

## Collegamenti

- [[Dimensione frattale]] - Concetto generale di cui la box-counting è un'istanza.
- [[Insieme di Cantor]] - Esempio classico con dimensione $\ln 2 / \ln 3$.
- [[Misura di un insieme]] - Legame formale tra dimensione e misura.
- [[Attrattori strani]] - Oggetti caotici la cui dimensione si misura con il box-counting.
