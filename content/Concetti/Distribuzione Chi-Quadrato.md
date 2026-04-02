---
title: Distribuzione Chi-Quadrato
date: 2026-04-02
tags:
  - statistica
  - test-statistici
  - biologia
aliases:
  - Chi-Quadrato di Pearson
  - Pearson Chi-Squared
  - Distribuzione χ²
  - Chi-Squared Distribution
source: Lezione 02 - Fenomeni Emergenti e Leggi di Potenza
---
> [!definition] Distribuzione Chi-Quadrato
> La distribuzione chi-quadrato (χ²) di Pearson è una distribuzione di probabilità continua utilizzata in statistica inferenziale. È definita come la distribuzione della somma dei quadrati di $k$ variabili normali standard indipendenti:
>
> $$\chi^2 = \sum_{i=1}^{k} \frac{(O_i - E_i)^2}{E_i}$$
>
> dove $O_i$ sono le frequenze osservate, $E_i$ le frequenze attese e $k$ il numero di gradi di libertà.

## Proprietà

- La distribuzione χ² è definita solo per valori non negativi ($\chi^2 \geq 0$).
- La forma della distribuzione dipende dal numero di **gradi di libertà** ($k$).
- Per $k = 1$, la distribuzione è fortemente asimmetrica a destra.
- Per $k \to \infty$, la distribuzione χ² tende a una distribuzione normale (Teorema del Limite Centrale).

## Funzione densità di probabilità

La funzione densità di probabilità della distribuzione χ² con $k$ gradi di libertà è:

$$p(\chi^2) = \frac{(\chi^2)^{k/2 - 1} e^{-\chi^2 / 2}}{2^{k/2} \Gamma(k/2)}$$

![[attachments/lezione-02/slide-10-img-000.png|400]]
*Figura: Funzione densità di probabilità della distribuzione χ² per diversi gradi di libertà.*

## Test del chi-quadrato

> [!info] Applicazione ai genomi virali
> Nella lezione 02, il test del chi-quadrato è stato applicato per verificare se il numero di [[Inverted Repeats|Inverted Repeats (IR)]] rilevati nei genomi virali è compatibile con l'ipotesi nulla di DNA bernoulliano (ovvero, sequenze casuali). Nel 57% dei 746 genomi virali analizzati, i valori-p risultano inferiori a 0.05, suggerendo che gli IR non sono distribuiti casualmente.

### Ipotesi nulla

L'ipotesi nulla ($H_0$) assume che il numero atteso $n_{ex}$ di IR con lunghezza dello stem $l$ e lunghezza del loop $m$ sia calcolabile assumendo un DNA bernoulliano, dove ogni base appare con la frequenza osservata nel genoma.

### Procedura

1. Calcolare il numero atteso $n_{ex}$ di IR sotto $H_0$.
2. Confrontare con il numero osservato $n_{obs}$.
3. Calcolare la statistica $\chi^2 = \frac{(n_{obs} - n_{ex})^2}{n_{ex}}$.
4. Determinare il valore-p dalla distribuzione χ² con i gradi di libertà appropriati.
5. Se $p < 0.05$, rifiutare $H_0$.

## Collegamenti

- [[Inverted Repeats]] - Applicazione del test χ² alla distribuzione di IR nei genomi virali.
- [[Fenomeni Emergenti]] - Il test rivela proprietà emergenti nei genomi.
- [[Leggi di Potenza]] - Altre distribuzioni statistiche rilevanti nello studio dei sistemi complessi.
