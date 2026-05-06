---
title: Dimensione frattale
date: 2024-05-07
tags:
  - concetto
  - frattali
  - geometria
  - complessità
  - matematica
aliases:
  - Fractal Dimension
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_04.pptx
---

# Dimensione frattale

La **dimensione frattale** è una generalizzazione della nozione classica di dimensione geometrica (topologica) che permette di descrivere oggetti la cui "complessità" non è catturata da numeri interi. Per i frattali, la dimensione è tipicamente un numero **frazionario**.

## Intuizione

Consideriamo un oggetto posto su una griglia di spaziatura $\epsilon$ e contiamo il numero di celle $N(\epsilon)$ necessarie per coprirlo. Per un frattale, $N(\epsilon)$ varia in modo non banale al diminuire di $\epsilon$.

## Definizioni principali

### 1. Dimensione per box-counting

La definizione più comune è la **box-counting dimension** (o dimensione di Minkowski-Bouligand):

$$
d = \lim_{\epsilon \to 0} \frac{\ln N(\epsilon)}{\ln(1/\epsilon)}
$$

dove $N(\epsilon)$ è il numero minimo di box (celle) di lato $\epsilon$ necessari per coprire l'oggetto.

> Se $C$ è costante per tutti gli $\epsilon$ piccoli, il contributo del secondo termine nel numeratore è trascurabile.

### 2. Dimensione di correlazione

Esistono anche definizioni alternative, come la **correlation dimension**:

$$
d = \lim_{r \to 0} \frac{\ln C(r)}{\ln(r)}
$$

dove $C(r)$ è la funzione di correlazione che conta le coppie di punti a distanza minore di $r$.

## Esempi

| Oggetto | Dimensione |
|---------|-----------|
| Linea continua | $d = 1$ |
| [[Insieme di Cantor]] | $d \approx 0.631$ |
| [[Attrattori strani|Attrattore di Hénon]] (correlation) | $d \approx 1.23$ |
| [[Attrattori strani|Attrattore di Hénon]] (box-counting) | $d \approx 1.27$ |

## Relazione con la misura

Esiste un legame tra dimensione per box-counting e misura zero: se un sottoinsieme limitato di $\mathbb{R}^m$ ha box-counting dimension $d < m$, allora ha **misura zero**. Tuttavia, il viceversa non è vero: esistono insiemi numerabili con dimensione per box-counting uguale a 1 e misura zero.

## Collegamenti

- [[Frattali]] - Oggetti che possiedono dimensione frattale.
- [[Box-counting dimension]] - La definizione operativa più usata.
- [[Insieme di Cantor]] - Esempio con dimensione $d = \ln 2 / \ln 3$.
- [[Misura di un insieme]] - Relazione tra dimensione e misura.
- [[Caos e Frattali]] - Gli attrattori caotici hanno dimensione frazionaria.
