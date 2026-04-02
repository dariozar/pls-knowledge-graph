---
title: Legge di Zipf
tags:
  - fisica-statistica
  - leggi-di-potenza
  - linguistica
  - genomica
aliases:
  - Zipf's Law
  - Legge di Zipf
source: Lezione 02 - Fenomeni Emergenti e Leggi di Potenza
---

# Legge di Zipf

> [!definition] Legge di Zipf
> La Legge di Zipf afferma che l'occorrenza $P_i$ di un certo evento, in funzione del rango $i$, segue una [[Leggi di Potenza|legge di potenza]]:
>
> $$P_i \propto \frac{1}{i^\alpha}$$
>
> dove $\alpha$ è l'esponente di Zipf (tipicamente $\alpha \approx 1$).

## Rango

> [!info] Definizione di rango
> Il **rango** è la posizione in cui si trova un elemento in una lista ordinata dal maggiore al minore. Ad esempio, in un testo, la parola con rango 1 è la più frequente, quella con rango 2 è la seconda più frequente, e così via.

## Origini linguistiche

La legge fu osservata per la prima volta nel campo della linguistica, contando l'occorrenza delle parole in un testo molto lungo. Per tutte le lingue studiate, il grafico delle occorrenze in funzione del rango mostra un andamento descritto da una legge di potenza.

> [!example] Applicazione alla linguistica
> Nei testi in lingua inglese, la parola più frequente ("the") appare circa il doppio della seconda ("of"), il triplo della terza ("and"), e così via. Questa relazione $P_i \propto 1/i$ è una legge di Zipf con esponente $\alpha = 1$.

## Applicazioni

La Legge di Zipf si osserva in contesti molto diversi:

- **Frequenza degli accessi** alle pagine internet
- **Frequenza delle parole** in testi scritti
- **Note** in spartiti musicali
- **Dimensione degli abitati** e delle città
- **Distribuzione dei redditi**
- **Distribuzione delle imprese** per dimensione
- **Forza dei terremoti**
- **Trascritti di singola cellula**

![[attachments/lezione-02/slide-22-img-000.png|400]]
*Figura: Visualizzazione delle leggi di potenza — poche entità con valori alti, molte con valori bassi.*

## Zipf in genetica

> [!info] Legge di Zipf nelle sequenze genomiche
> È possibile applicare la stessa analisi di Zipf alle sequenze genomiche. Per le sequenze codificanti, la scelta naturale dei "parole" sono i triplettoni (codoni). Per le sequenze non codificanti, non esiste una scelta naturale: si usano sequenze di $n$ lettere, lasciando $n$ come parametro libero (tipicamente $n = 6$).
>
> Lo studio di Mantegna et al. (PRL, 73, 3169, 1994) ha mostrato che le sequenze non codificanti di mammiferi seguono una legge di Zipf con esponente $\zeta = 0.283$.

## Riferimenti

- G. K. Zipf, *Human Behavior and the Principle of Least Effort*, Addison-Wesley Press (1949).
- R.N. Mantegna et al., *Linguistic Features of NonCoding DNA sequences*, PRL, 73, 3169 (1994).

## Collegamenti

- [[Leggi di Potenza]] - La Legge di Zipf è un caso specifico di legge di potenza.
- [[Invarianza di Scala]] - La legge di Zipf esprime invarianza di scala.
- [[Fenomeni Emergenti]] - La comparsa della legge di Zipf è un fenomeno emergente.
- [[Inverted Repeats]] - Applicazione dell'analisi di frequenza alle sequenze genomiche.
