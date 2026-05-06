---
title: Lezione 03 - Determinismo, Caos e Sistemi Nonlineari
date: 2024-05-02
tags:
  - lezione
  - caos
  - sistemi-nonlineari
  - determinismo
aliases:
  - Lezione 3 - Determinismo, Caos e Sistemi Nonlineari
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_03.pptx
---

# Lezione 03 - Determinismo, Caos e Sistemi Nonlineari

Questa lezione, tenuta dal Prof. Salvatore Miccichè il 2 Maggio 2024, esplora il confine tra [[Determinismo|determinismo]] e [[Previsione|previsione]], introducendo i concetti di [[Caos deterministico|caos deterministico]], [[Nonlinearità|nonlinearità]], [[Effetto farfalla|effetto farfalla]] ed [[Attrattori|attrattori]], con esempi classici come la [[Mappa Logistica|mappa logistica]], la [[Mappa di Henon|mappa di Henon]] e il [[Modello di Lorenz|modello di Lorenz]].

## Riassunto degli slide

### Slide 1-2: Introduzione
- Docente: Salvatore Miccichè, Università degli Studi di Palermo, Dipartimento di Fisica e Chimica Emilio Segrè.
- Data: 02 Maggio 2024.
- Titolo: "Determinismo, caos e sistemi nonlineari".

### Slide 3-4: Il Caos deterministico e il moto dei tre corpi
- Esistono fenomeni macroscopici regolari (palline da biliardo, caduta di un grave) e fenomeni apparentemente imprevedibili (tempo meteorologico).
- Il moto di un pianeta attorno a un singolo Sole segue le leggi di Keplero e è perfettamente prevedibile.
- Il moto di un pianeta in un sistema binario (con due Soli) diventa caotico: esempio classico del problema dei tre corpi.

### Slide 5-6: Determinismo e Previsione
- Esiste una regola di evoluzione che dato $x(0)$ determina univocamente $x(t)$.
- [[Determinismo]] è proprietà intrinseca del sistema; [[Previsione]] dipende dalle capacità dell'osservatore.
- Successo storico: scoperta di Nettuno dalle perturbazioni del moto di Urano.
- A prima vista, nulla sembra contrario all'idea di poter risolvere ogni equazione.

![[attachments/lezione-03/slide-05-img-000.png|400]]
*Figura 1: Equazione fondamentale della dinamica (Secondo Principio).* — [[Determinismo|Determinismo]]

### Slide 7-8: Crisi del riduzionismo
- Fenomeni come la dinamica atmosferica e le correnti marine sfuggono all'approccio riduzionista.
- Esempio della roulette: le palline obbediscono alle leggi di Newton, ma nessuno risolve le equazioni.
- Moto dei tre corpi: anche conoscendo le leggi, la previsione è impossibile a lungo termine.
- Piccole differenze nelle condizioni iniziali producono grandissime differenze nei fenomeni finali.
- Questo rappresenta una [[Crisi del riduzionismo|crisi del riduzionismo]] diversa da quella legata ai [[Fenomeni Emergenti|fenomeni emergenti]]: non servono molte componenti, basta la [[Nonlinearità|nonlinearità]].

### Slide 9-10: Effetto farfalla e Caos deterministico
- Il determinismo non implica la possibilità di fare previsioni accurate.
- Ci può essere complessità anche in un sistema con solo 3 variabili.
- La domanda cruciale: cosa rende così cruciali le piccole deviazioni nelle condizioni iniziali?

### Slide 11-13: Nonlinearità
- Le equazioni del moto nei sistemi caotici sono [[Nonlinearità|nonlineari]].
- Esempio della mappa $x_{t+1} = x_t^2 - 2$: partendo da $x_0 = 0.5$ e $x_0 = 0.50001$, dopo poche iterazioni le traiettorie divergono completamente.

![[attachments/lezione-03/slide-11-img-000.png|400]]
*Figura 2: Divergenza delle traiettorie in un sistema nonlineare.* — [[Nonlinearità|Nonlinearità]]

- [[Esponenti di Lyapunov]]: misurano la massima dilatazione dello spazio delle fasi.

![[attachments/lezione-03/slide-12-img-000.png|400]]
*Figura 3: Definizione dell'esponente di Lyapunov e del tempo di predicibilità.* — [[Esponenti di Lyapunov|Esponenti di Lyapunov]]

- Connessione con processi stocastici: un'incertezza iniziale evolve secondo una densità di probabilità.

### Slide 14-16: Caos, probabilità ed Entropia
- Dopo un tempo sufficientemente lungo, la densità di probabilità tende a una distribuzione asintotica indipendente dalle condizioni iniziali.
- Esempio: per la mappa logistica con $r=4$, $p_\infty(x) = \frac{1}{\pi\sqrt{x(1-x)}}$.

![[attachments/lezione-03/slide-14-img-000.png|400]]
*Figura 4: Densità di probabilità asintotica per la mappa logistica.* — [[Entropia|Entropia]]

- [[Entropia]] e [[Esponenti di Lyapunov]]: il Teorema di Pesin collega entropia e esponenti di Lyapunov positivi.
- La complessità del caos può essere misurata attraverso l'entropia.

### Slide 17-21: Mappa Logistica
- Definizione: $x_{n+1} = r \, x_n (1 - x_n)$, con $r$ parametro reale positivo.
- Descrive riproduzione e mortalità in una popolazione.

![[attachments/lezione-03/slide-19-img-000.png|400]]
*Figura 5: Equazione della mappa logistica.* — [[Mappa Logistica|Mappa Logistica]]

- Diagramma delle biforcazioni: al crescere di $r$, successione di [[Biforcazioni|biforcazioni]] a raddoppio di periodo fino al caos.

![[attachments/lezione-03/slide-19-img-001.png|400]]
*Figura 6: Diagramma delle biforcazioni della mappa logistica.* — [[Biforcazioni|Biforcazioni]]

![[attachments/lezione-03/slide-19-img-002.png|400]]
*Figura 7: Interpretazione biologica della mappa logistica.* — [[Mappa Logistica|Mappa Logistica]]

- Per $r=4$, distribuzione asintotica con istogramma e curva teorica.

![[attachments/lezione-03/slide-20-img-000.png|400]]
*Figura 8: Simulazione numerica e distribuzione asintotica per $r=4$.* — [[Mappa Logistica|Mappa Logistica]]

### Slide 22: Mappa di Henon
- Mappa bidimensionale proposta da Henon nel 1976.
- Equazioni: $x_{n+1} = 1 - a x_n^2 + y_n$, $y_{n+1} = b x_n$.
- Scopo: modello semplice che mostra le proprietà essenziali dell'attrattore strano di Lorenz.

![[attachments/lezione-03/slide-22-img-000.png|400]]
*Figura 9: Attrattore di Henon per $a = 1.4$, $b = 0.3$.* — [[Mappa di Henon|Mappa di Henon]]

![[attachments/lezione-03/slide-22-img-001.png|400]]
*Figura 10: Equazioni della mappa di Henon.* — [[Mappa di Henon|Mappa di Henon]]

### Slide 23: Modello di Lorenz
- Sistema di tre equazioni differenziali per la convezione di Rayleigh-Bénard.
- Rappresenta l'atmosfera con temperatura maggiore al suolo e minore a quota.

![[attachments/lezione-03/slide-23-img-000.png|400]]
*Figura 11: Immagine dell'attrattore di Lorenz.* — [[Modello di Lorenz|Modello di Lorenz]]

![[attachments/lezione-03/slide-23-img-001.png|400]]
*Figura 12: Equazioni del modello di Lorenz.* — [[Modello di Lorenz|Modello di Lorenz]]

### Slide 24: Biforcazioni
- Transizioni qualitative del comportamento al variare di un parametro.
- Nella mappa logistica: successione di raddoppi di periodo che portano al caos.

### Slide 25: Caos e probabilità
- Il caos deterministico si comporta, in qualche modo, come un processo stocastico.
- L'evoluzione della densità di probabilità segue equazioni simili a quelle dei processi stocastici.

### Slide 26-28: Attrattori
- Definizione formale di attrattore: insieme invariante, attrattivo e minimale.
- Bacino di attrazione: insieme delle condizioni iniziali che convergono all'attrattore.
- Gli [[Attrattori|attrattori strani]] hanno dimensione frattale.

![[attachments/lezione-03/slide-28-img-000.png|400]]
*Figura 13: Esempio di attrattore e non-attrattore (sistema $x - x^3$).* — [[Attrattori|Attrattori]]

### Slide 29: Conclusione
- Contatto: salvatore.micciche@unipa.it

## Collegamenti ai concetti

- [[Determinismo]]
- [[Previsione]]
- [[Caos deterministico]]
- [[Effetto farfalla]]
- [[Nonlinearità]]
- [[Esponenti di Lyapunov]]
- [[Entropia]]
- [[Mappa Logistica]]
- [[Mappa di Henon]]
- [[Modello di Lorenz]]
- [[Biforcazioni]]
- [[Attrattori]]
- [[Crisi del riduzionismo]]
- [[Riduzionismo]]

## Mappe dei contenuti

- [[Complessità]] - MOC dei concetti di complessità.
- [[Caos e Nonlinearità]] - MOC dedicata al caos, alla nonlinearità e agli attrattori.
