---
title: "Lezione 06 - Percolazione e Transizioni di Fase"
date: 2024-05-14
tags:
  - lezione
  - percolazione
  - transizioni-di-fase
  - esponenti-critici
  - albero-di-Cayley
aliases:
  - Lezione 06
  - Percolazione e transizioni di fase
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_06.pptx
---

# Lezione 06 – Percolazione e Transizioni di Fase

**Docente:** Salvatore Miccichè  
**Data:** 14 Maggio 2024  
**Corso:** PLS in Fisica Statistica e Sistemi Complessi

---

## Panoramica

Questa lezione introduce la **teoria della percolazione** come modello fondamentale per studiare le **transizioni di fase geometriche**. Si parte dalla definizione intuitiva del fenomeno (flusso in un mezzo poroso) per arrivare alla formulazione matematica su reticoli, all'analisi esatta sull'albero di Cayley e alla discussione degli **esponenti critici** e delle **leggi di scaling**.

---

## Parte 1 – Introduzione alla percolazione (Slides 1–5)

### Definizione intuitiva
La percolazione è il fenomeno per cui un flusso (ad esempio di acqua) attraversa un mezzo poroso.

### Definizione formale
Si consideri una roccia con cavità sferiche di raggio $r$ posizionate casualmente nel mezzo, permettendo la sovrapposizione. La domanda fondamentale è: a quale frazione di volume $r = V_{\text{cavity}} / V_{\text{medium}}$ l'acqua è in grado di percorrere distanze arbitrariamente lunghe?

![[attachments/lezione-06/slide-03-img-000.png|400]]

### Tipologie di percolazione
- **Percolazione continua** (*continuum percolation*): cavità distribuite nello spazio continuo
- **Percolazione su reticolo** (*lattice percolation*): siti o legami occupati con probabilità $p$ su un reticolo regolare

![[attachments/lezione-06/slide-04-img-000.png|400]]

### Sito vs Legame percolazione
- **Site percolation**: i siti (nodi) sono occupati con probabilità $p$
- **Bond percolation**: i legami (archi) sono occupati con probabilità $p$

### Soglia critica
Per il reticolo quadrato 2D, la soglia di percolazione di sito è:
$$p_c \approx 0.59274605$$

Nel contesto delle reti complesse, la percolazione è un comportamento emergente probabilistico che causa la formazione di una grande componente gigante.

![[attachments/lezione-06/slide-05-img-000.png|400]]

### Concetti chiave
- [[Percolazione]] – Teoria generale della percolazione
- [[Parametro d'ordine]] – Frazione di volume / probabilità di occupazione
- [[Percolazione continua vs reticolo]] – Differenze tra i due contesti
- [[Sito percolazione vs Legame percolazione]] – Tipologie su reticolo

---

## Parte 2 – Cluster e dimensione frattale (Slides 6–9)

### Visualizzazione della transizione
La lezione mostra la simulazione della percolazione su reticolo 2D al variare di $p$:
- $p = 0.57$ (sotto soglia): nessun cluster di spanning
- $p = 0.59$ (vicino alla soglia): emerge il cluster gigante
- $p = 0.61$ (sopra soglia): cluster gigante ben definito

![[attachments/lezione-06/slide-07-img-000.png|400]]

### Scaling della massa del cluster
La massa $M$ di un cluster di percolazione scala con la dimensione $L$ del sistema:

$$M \sim L^D$$

Dove $D$ è la **dimensione frattale**:
- $p > p_c$: $M \sim L^d$ (oggetto compatto, $D = d$)
- $p = p_c$: $M \sim L^D$ con $D < d$ (oggetto frattale)
- $p < p_c$: $M \sim \ln L$ (cluster finiti)

Per il reticolo quadrato 2D a $p_c$: $D \approx 1.89$.

![[attachments/lezione-06/slide-08-img-000.png|400]]

### Perché $D < d$?
Il cluster di percolazione è un oggetto **ramificato**, non compatto. Contiene buchi (*holes*) a tutte le scale. L'unico requisito è che colleghi due lati opposti del reticolo, non che cresca uniformemente in tutte le direzioni.

![[attachments/lezione-06/slide-09-img-000.png|400]]

### Concetti chiave
- [[Componente gigante]] – Cluster che attraversa il sistema
- [[Dimensione frattale del cluster]] – Proprietà geometrica al punto critico
- [[Soglia di percolazione]] – Soglia critica $p_c$

---

## Parte 3 – Albero di Cayley e soluzione esatta (Slides 10–13)

### Definizione
Un **albero di Cayley** (o *rete di Bethe*) è un albero in cui ogni vertice non-foglia ha $z$ rami (numero di coordinazione costante).

![[attachments/lezione-06/slide-11-img-000.png|400]]

### Soglia di percolazione
Poiché non ci sono cicli, la percolazione è esattamente risolvibile. La condizione per la formazione di un cluster gigante è:

$$p(z-1) \geq 1 \quad \Rightarrow \quad p_c = \frac{1}{z-1}$$

Per $z = 3$: $p_c = 1/2$.

### Probabilità di spanning
Sia $Q$ la probabilità che il nodo origine non appartenga al cluster gigante. L'equazione:

$$Q = (1-p) + p Q^{z-1}$$

Per $z = 3$, le soluzioni sono $Q = 1$ e $Q = (1-p)/p$. La probabilità di spanning è:

$$P(p) = 1 - Q = \frac{p - p_c}{p}$$

![[attachments/lezione-06/slide-13-img-000.png|400]]

### Concetti chiave
- [[Albero di Cayley]] – Soluzione esatta della percolazione
- [[Probabilità di spanning]] – Parametro d'ordine $P(p)$

---

## Parte 4 – Esponenti critici e scaling (Slides 14–21)

### Comportamento critico del parametro d'ordine
Vicino a $p_c$, la probabilità di spanning si annulla con una legge di potenza:

$$P(p) \sim (p - p_c)^{\beta}$$

Per l'albero di Cayley, $\beta = 1$.

![[attachments/lezione-06/slide-14-img-000.png|400]]

### Dimensione media dei cluster
La dimensione media dei cluster finiti $S$ diverge come:

$$S \sim |p - p_c|^{-\gamma}$$

Per l'albero di Cayley, $\gamma = 1$.

![[attachments/lezione-06/slide-15-img-000.png|400]]

### Perimetro dei cluster
Per un cluster di $s$ siti su un albero di Cayley con coordinazione $z$:

$$t = s(z-2) + 2$$

Dove $t$ è il perimetro (numero di vicini non occupati).

![[attachments/lezione-06/slide-17-img-002.png|400]]

### Distribuzione delle dimensioni dei cluster
Il numero di cluster di dimensione $s$ per sito:

$$n_s = g_s \, p^s (1-p)^{s(z-2)+2}$$

Dove $g_s$ è il numero di configurazioni possibili con $s$ siti occupati.

### Ansatz di scaling
Vicino a $p_c$:

$$n_s(p) \sim s^{-\tau} f\big((p - p_c) s^{\sigma}\big)$$

![[attachments/lezione-06/slide-19-img-000.png|400]]

### Divergenza di $S$ e calcolo di $\tau$
Imponendo consistenza con $S = \sum_s s^2 n_s$, si ottiene la relazione tra gli esponenti.

![[attachments/lezione-06/slide-20-img-000.png|400]]

### Riassunto degli esponenti critici
Per l'albero di Cayley:
- $\beta = 1$ (parametro d'ordine)
- $\gamma = 1$ (dimensione media cluster)
- $\tau = 5/2$ (distribuzione cluster)
- $\sigma = 1/2$ (scaling)

**Relazione di Fisher:**
$$\tau = 2 + \sigma \beta$$

![[attachments/lezione-06/slide-21-img-000.png|400]]

### Concetti chiave
- [[Esponenti critici]] – Esponenti $\beta$, $\gamma$, $\tau$, $\sigma$
- [[Legge di scaling]] – Ansatz di scaling e relazioni
- [[Esponente di Fisher]] – Relazione fondamentale tra esponenti
- [[Lunghezza di correlazione]] – Scala caratteristica $\xi$

---

## Collegamenti trasversali

- [[Percolazione]] – Nota concettuale principale sulla percolazione
- [[Sistemi Termodinamici]] – Transizioni di fase e analogie
- [[Frattali]] – Geometria frattale dei cluster al punto critico
- [[Invarianza di Scala]] – Assenza di scala caratteristica a $p_c$
- [[Leggi di Potenza]] – Descrizione matematica dello scaling
- [[Reti e Networks]] – Percolazione nel contesto delle reti complesse
- [[Lezione 07 - Reti Complesse e Metriche]] – Percolazione su reti complesse
