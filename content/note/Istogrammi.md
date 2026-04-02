---
title: Istogrammi
tags:
  - statistica
  - misure
  - visualizzazione
aliases:
  - Istogramma
  - Histogram
source: Lezione 02 - Fenomeni Emergenti e Leggi di Potenza
---

# Istogrammi

> [!definition] Istogramma
> Un istogramma è un grafico che rappresenta la distribuzione di frequenza di un insieme di dati. L'asse orizzontale riporta gli intervalli (bin) e l'asse verticale mostra il numero di osservazioni in ciascun intervallo. Al limite di un numero infinito di misure, l'istogramma tende alla funzione di densità di probabilità continua $p(x)$.

## Costruzione

Dato un insieme di misure con valore minimo $m$ e valore massimo $M$:

- Si sceglie il numero di bin: $\text{nbin}$
- La larghezza di ciascun bin è: $\Delta x = \frac{M - m}{\text{nbin}}$
- I bordi dei bin sono: $g[j] = m + j \cdot \Delta x$, per $j = 0, \ldots, \text{nbin}$
- Il conteggio $c[j]$ indica quante misure cadono nell'intervallo $[g[j-1], g[j])$

## Esempio: esperimento della moneta

> [!example] Misura del diametro di una moneta da 2 Euro
> Ciascuno studente misura il diametro di una moneta da 2 Euro due volte, usando un vecchio righello di legno. Si osserva l'occorrenza delle varie misure riportate dagli studenti e si costruisce l'istogramma. Con $N = 20$ studenti:

| Misura (mm) | Occorrenza |
|-------------|------------|
| 2.40 | 4 |
| 2.45 | 8 |
| 2.50 | 8 |
| 2.55 | |
| 2.60 | |

Media $\approx 2.56$ mm.

![[attachments/lezione-02/slide-17-img-000.png|400]]
*Figura: Esperimento di misura — studenti che misurano il diametro della moneta da 2 Euro.*

> [!info] Implicazioni
> Le misure variano, ma la probabilità di trovare misure molto più grandi o molto più piccole della media non è trascurabile. **Non esiste quindi una scala tipica di fluttuazioni**: questo concetto è collegato all'assenza di scala tipica nelle [[Leggi di Potenza]] e all'[[Invarianza di Scala]].

## Limite continuo

Nel limite in cui si fanno **molte** misure ($N \to \infty$), la distribuzione di probabilità discreta tende a una funzione continua $p(x)$, dove l'integrale su un intervallo dà la probabilità che una misura cada in quell'intervallo.

## Collegamenti

- [[Leggi di Potenza]] - Le distribuzioni a legge di potenza possono essere visualizzate con istogrammi.
- [[Fenomeni Emergenti]] - Gli istogrammi rivelano pattern emergenti nei dati sperimentali.
- [[Legge di Zipf]] - L'analisi di Zipf si basa sulla costruzione di istogrammi di occorrenza.
