---
title: Lezione 04 - Frattali e Dimensione Frattale
date: 2024-05-07
tags:
  - lezione
  - frattali
  - geometria
aliases:
  - Lezione 4 - Frattali e Dimensione Frattale
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_04.pptx
---

# Lezione 04 - Frattali e Dimensione Frattale

Questa lezione introduce i **frattali** e la nozione di **dimensione frattale**, strumenti geometrici fondamentali per descrivere la complessità dei sistemi che presentano strutture auto-simili su molte scale. Si parte dall'intuizione della misura per giungere alla costruzione dell'[[Insieme di Cantor]], e si conclude con il legame tra [[Caos e Frattali|caos e frattali]] attraverso gli [[Attrattori strani|attrattori strani]].

## Riassunto degli slide

### Slide 1: Titolo
- Titolo: "Lezione 04 – I frattali"
- Data: 07 Maggio 2024
- Docente: Salvatore Miccichè (Università degli Studi di Palermo)

### Slide 2-3: Introduzione alla misura
- Misurare la grandezza di un oggetto significa coprirlo con unità di misura.
- Si introduce l'idea che set "porosi" e set "continui" abbiano misura diversa.

### Slide 4: Proprietà dei frattali
I frattali hanno alcune o tutte le seguenti proprietà:
- struttura complicata su una vasta gamma di scale di lunghezza
- ripetizione di strutture a diverse scale ([[Auto-similarità|auto-similarità]])
- [[Dimensione frattale|dimensione frattale]] non intera
- l'[[Insieme di Cantor]] è il più semplice esempio geometrico di frattale

![[attachments/lezione-04/slide-04-img-000.png|400]]
*Figura: Costruzione dell'insieme di Cantor per terzi intermedi. A ogni passo si rimuove il terzo medio di ogni intervallo rimanente.*

### Slide 5-7: Lunghezza e misura dell'insieme di Cantor
- $K_n$ consiste di $2^n$ intervalli di lunghezza $1/3^n$
- Lunghezza totale di $K_n$: $(2/3)^n \to 0$
- L'insieme di Cantor $K$ ha **lunghezza zero** ([[Misura di un insieme|misura zero]])
- Concetto di insieme **numerabile** vs **non numerabile** (Cantor)
- Il termine **frattale** fu coniato da Benoît Mandelbrot nel 1975, dal latino *fractus* (rotto, spezzato)

### Slide 8-10: Dimensione dei frattali – box-counting
- Si introduce il metodo del **box-counting**: contare il numero di celle $N(\epsilon)$ necessarie a coprire il frattale su una griglia di spaziatura $\epsilon$
- Relazione di scaling: $N(\epsilon) \sim C \cdot \epsilon^{-d}$
- **Box-counting dimension**:
$$
d = \lim_{\epsilon \to 0} \frac{\ln N(\epsilon)}{\ln(1/\epsilon)}
$$

![[attachments/lezione-04/slide-10-img-000.png|300]]
*Formula per la dimensione d.*

![[attachments/lezione-04/slide-10-img-001.png|300]]
*Limite della pendenza nel grafico log-log.*

### Slide 11-12: Esempi di calcolo
- **Linea continua**: $d = 1$
- **Insieme di Cantor**:
$$
\text{boxdim}(K) = \lim_{n \to \infty} \frac{\ln 2^n}{\ln 3^n} = \frac{\ln 2}{\ln 3} \approx 0.631
$$

![[attachments/lezione-04/slide-12-img-000.png|350]]
*Calcolo della dimensione dell'insieme di Cantor.*

![[attachments/lezione-04/slide-12-img-001.png|300]]
*Formula generale della box-counting dimension.*

### Slide 13: Relazione tra box-counting e misura zero
- **Teorema**: se $\text{boxdim}(A) = d < m$ in $\mathbb{R}^m$, allora $A$ ha misura zero.
- Il **viceversa non vale**: esistono insiemi numerabili con box-counting dimension 1 e misura zero.

![[attachments/lezione-04/slide-13-img-000.png|400]]
*Enunciato e dimostrazione del Teorema 4.16.*

### Slide 14: Dimensione di correlazione
- Esistono definizioni alternative (e più semplici) di dimensione frattale
- **Correlation dimension**:
$$
d = \lim_{r \to 0} \frac{\ln C(r)}{\ln(r)}
$$
- Esempio: attrattore di Hénon ha correlation dimension $d \approx 1.23$

![[attachments/lezione-04/slide-14-img-000.png|300]]
*Definizione della funzione di correlazione C(r).*

![[attachments/lezione-04/slide-14-img-001.png|350]]
*Stima grafica della correlation dimension per l'attrattore di Hénon (slope ≈ 1.23).*

![[attachments/lezione-04/slide-14-img-002.png|300]]
*Formula della correlation dimension.*

### Slide 15-16: Caos e Frattali
- Connessione profonda: alcuni [[Attrattori strani|attrattori]] mostrano [[Auto-similarità|auto-similarità]]
- Esempio: attrattore di Hénon con ingrandimenti successivi che mostrano la struttura striata ripetersi

![[attachments/lezione-04/slide-16-img-000.png|400]]
*Auto-similarità dell'attrattore di Hénon. (a) orbita attrattiva; (b)-(d) ingrandimenti successivi.*

### Slide 17: Frattali e dimensione frazionaria
- Sia i frattali che gli attrattori hanno dimensione frazionaria
- Conteggio dei box per l'attrattore di Hénon:
  - lato $1/8$: 177 box
  - lato $1/16$: 433 box
  - lato $1/32$: 1037 box
  - lato $1/64$: 2467 box
  - lato $1/128$: 5763 box
- Box-counting dimension stimata: $d \approx 1.27$

![[attachments/lezione-04/slide-17-img-000.png|350]]
*Griglia di box con lato ε = 1/4 sovrapposta all'attrattore di Hénon.*

![[attachments/lezione-04/slide-17-img-001.png|350]]
*Griglie con lato 1/8 e 1/16 per la stima della box-counting dimension.*

![[attachments/lezione-04/slide-17-img-002.png|350]]
*Rapporto logaritmico per la stima della box-counting dimension (slope ≈ 1.27).*

### Slide 18: Conclusione
- Contatto: salvatore.micciche@unipa.it

## Collegamenti ai concetti

- [[Frattali]] - Definizione, proprietà e storia dei frattali.
- [[Insieme di Cantor]] - Esempio paradigmatico di frattale con misura zero.
- [[Misura di un insieme]] - Generalizzazione di lunghezza, area, volume; relazione con la dimensione.
- [[Dimensione frattale]] - Concetto di dimensione non intera.
- [[Box-counting dimension]] - Definizione operativa più comune di dimensione frattale.
- [[Auto-similarità]] - Ripetizione di strutture a diverse scale.
- [[Caos e Frattali]] - Legame tra sistemi caotici e geometria frattale.
- [[Attrattori strani]] - Oggetti geometrici dei sistemi caotici con dimensione frazionaria.

## Mappe dei contenuti

- [[Complessità]] - MOC dei concetti di complessità.
- [[Frattali e Geometria]] - MOC dedicata ai concetti di frattali e geometria.
