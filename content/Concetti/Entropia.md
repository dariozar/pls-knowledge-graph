---
title: Entropia
date: 2024-05-02
tags:
  - concetto
  - caos
  - sistemi-complessi
  - informazione
  - termodinamica
aliases:
  - Entropy
  - Entropia di Shannon
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_03.pptx
---

# Entropia

> [!definition] Entropia nel contesto del caos
> Nel contesto dei sistemi caotici, l'entropia (o entropia di Shannon/informazione) è una misura della complessità del sistema collegata alla geometria dello spazio delle fasi e al suo partizionamento in celle a cui associare una distribuzione di probabilità. L'entropia cattura il tasso di generazione di informazione nuova da parte del sistema caotico.

## Entropia e spazio delle fasi

L'entropia/informazione ha a che fare con:
- La geometria dello spazio delle fasi del sistema
- Il partizionamento dello spazio delle fasi in celle
- L'associazione di una distribuzione di probabilità a queste celle

## Teorema di Pesin

Il Teorema di Pesin mette assieme entropia ed esponenti di Lyapunov:

> [!theorem] Teorema di Pesin
> L'entropia del sistema è data dalla somma degli [[Esponenti di Lyapunov|esponenti di Lyapunov]] positivi:
> $$h = \sum_{\lambda_i > 0} \lambda_i$$

Questo teorema stabilisce un ponte fondamentale tra:
- La dinamica geometrica (dilatazione dello spazio delle fasi)
- La teoria dell'informazione (entropia)

## Densità di probabilità asintotica

Nei sistemi caotici, dopo un tempo sufficientemente lungo, la densità di probabilità $p_t(x)$ tende a una densità $p_\infty(x)$ indipendente dalla densità iniziale. Ad esempio, per la [[Mappa Logistica|mappa logistica]] con $r = 4$:

$$p_\infty(x) = \frac{1}{\pi \sqrt{x(1-x)}}$$

Questa densità è una proprietà intrinseca del sistema ed ha un carattere oggettivo. I risultati sono indipendenti dalla grandezza dell'incertezza iniziale, per quanto piccola sia (purché non nulla).

## Complessità del caos

La complessità del caos può essere misurata attraverso l'entropia:
- Maggiore è l'entropia, maggiore è la complessità e l'imprevedibilità del sistema.
- L'entropia quantifica il tasso con cui il sistema "genera" nuova informazione imprevedibile.

## Collegamenti

- [[Caos deterministico]] - L'entropia misura la complessità del caos.
- [[Esponenti di Lyapunov]] - Collegati all'entropia tramite il teorema di Pesin.
- [[Mappa Logistica]] - Esempio di calcolo esplicito della densità asintotica.
- [[Teorema di Pesin]] - Il teorema che collega entropia ed esponenti di Lyapunov.
