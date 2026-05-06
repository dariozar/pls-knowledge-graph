---
title: Misura di un insieme
date: 2024-05-07
tags:
  - concetto
  - frattali
  - geometria
  - complessità
  - matematica
  - analisi
aliases:
  - Measure of a Set
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_04.pptx
---

# Misura di un insieme

La **misura di un insieme** è una generalizzazione intuitiva di concetti come lunghezza, area e volume. Misurare la grandezza di un oggetto significa prendere uno strumento che rappresenta una certa unità di misura e riportarlo tante volte sull'oggetto finché non lo si è ricoperto completamente.

## Intuizione: set "porosi" vs "continui"

Con questa definizione di misura, si introduce l'idea fondamentale che i set **"porosi"** e i set **"continui"** hanno misura diversa. Vogliamo una misura che:

- vada bene anche per insiemi infiniti
- corrisponda all'intuizione che le cose "piene" e le cose "con vuoti" abbiano misura diversa

## Misura zero

Un insieme $A$ ha **misura zero** se può essere "coperto" da una collezione di intervalli (o box) la cui misura totale può essere resa arbitrariamente piccola.

### Esempio: l'insieme di Cantor

L'[[Insieme di Cantor]] $K$ è contenuto in $K_n$, che consiste di $2^n$ intervalli di lunghezza $3^{-n}$. La lunghezza totale di $K_n$ è $(2/3)^n$, che tende a 0. Quindi $K$ ha **lunghezza zero** (misura zero), pur essendo un insieme **non numerabile**.

> Esempio numerico: $K_{40}$ ha lunghezza minore di $10^{-6}$.

## Relazione con la dimensione frattale

Esiste un legame formale tra [[Box-counting dimension|box-counting dimension]] e misura zero:

> **Teorema 4.16**: sia $A$ un sottoinsieme limitato di $\mathbb{R}^m$ con $\text{boxdim}(A) = d < m$. Allora $A$ è un insieme di misura zero.
>
> **Dimostrazione**: $A$ è contenuto nell'unione di $N(\epsilon)$ box di lato $\epsilon$. Il volume totale è $\epsilon^m N(\epsilon)$. Poiché $d < m$, si ha:
> $$
> \lim_{\epsilon \to 0} \ln(\epsilon^m N(\epsilon)) = \lim_{\epsilon \to 0} (m \ln \epsilon + \ln N(\epsilon)) = \lim_{\epsilon \to 0} \ln \epsilon \left(m - \frac{\ln N(\epsilon)}{\ln(1/\epsilon)}\right) = -\infty
> $$
> Quindi $\epsilon^m N(\epsilon) \to 0$, cioè il volume totale può essere reso piccolo a piacere.

> **Attenzione**: il **viceversa non vale**. Esistono sottoinsiemi dell'intervallo unitario (in effetti, sottoinsiemi numerabili) con box-counting dimension uguale a 1 e misura zero. Quindi "misura zero" non implica "dimensione piccola" nel senso della box-counting dimension.

## Collegamenti

- [[Insieme di Cantor]] - Esempio paradigmatico di insieme non numerabile con misura zero.
- [[Box-counting dimension]] - Definizione di dimensione legata formalmente alla misura.
- [[Frattali]] - Oggetti che sfidano l'intuizione classica su misura e dimensione.
- [[Dimensione frattale]] - Concetto che generalizza la nozione di dimensione oltre la misura.
