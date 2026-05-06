---
title: Lezione 05 - Modello di Ising Schelling e Modelli ad Agente
date: 2024-05-09
tags:
  - lezione
  - ising
  - modelli-ad-agente
  - schelling
  - transizioni-di-fase
  - toy-models
aliases:
  - Lezione 5 - Modello di Ising, Schelling e Modelli ad Agente
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_05.pptx
---

# Lezione 05 – Modello di Ising, Schelling e Modelli ad Agente

Questa lezione introduce il **[[Modello di Ising]]** come paradigma fisico per le [[Transizioni di Fase|transizioni di fase]] ordine-disordine, passa attraverso il concetto di **[[Toy Models|toy models]]**, e conclude con il **[[Modello di Schelling]]** e un'introduzione ai **[[Modelli ad Agente]]** (ABM).

## Riassunto degli slide

### Slide 1: Titolo
- Titolo: "Lezione 05 – Il Modello di Ising"
- Data: 09 Maggio 2024
- Docente: Salvatore Miccichè (Università degli Studi di Palermo)

### Slide 2-3: Ordine e Disordine
- Introduzione ai concetti di [[Ordine e Disordine|ordine e disordine]] con esempi fisici (ghiaccio vs acqua).
- Riferimenti alla coesistenza e alle transizioni di fase.

![[attachments/lezione-05/slide-03-img-001.png|400]]

### Slide 4-5: Il Modello di Ising
- Il modello di Ising per ferromagneti è l'esempio paradigmatico di transizioni ordine-disordine.
- Sistema di $N$ [[Spins|spin]] $\pm 1$ su un reticolo; energia totale:
$$
H = -J \sum_{\langle i,j \rangle} s_i s_j
$$
- Nessun campo esterno.
- Dinamica simulabile con metodologia Monte Carlo ([[Algoritmo Metropolis]]): ogni flip è accettato con probabilità $\exp(-\Delta E / k_B T)$.

![[attachments/lezione-05/slide-04-img-000.png|400]]
*Figura: Hamiltoniana del modello di Ising.*

### Slide 6: Transizione di fase del primo ordine
- Transizione di fase del primo ordine caratterizzata da:
  - divergenza del calore specifico $C_V$
  - [[Magnetizzazione spontanea|magnetizzazione spontanea]] non nulla
- Riferimento: R.K. Pathria & P.D. Beale, *Statistical Mechanics* (2022).

![[attachments/lezione-05/slide-06-img-000.png|400]]
*Figura: Calore specifico del modello di Ising 2D per reticoli finiti (2×2 fino a 64×64). La divergenza approccia la temperatura critica (linea verticale).*

### Slide 7: Magnetizzazione e simulazioni Monte Carlo
- Magnetizzazione positiva: spin allineati (ordine).
- Magnetizzazione nulla: spin orientati casualmente (disordine).
- Grafici di energia e magnetizzazione in funzione della temperatura da simulazioni Monte Carlo.

![[attachments/lezione-05/slide-07-img-000.png|350]]
*Figura: Energia vs temperatura (reticolo 10×10).*

![[attachments/lezione-05/slide-07-img-001.png|350]]
*Figura: Magnetizzazione da approssimazione di campo medio.*

![[attachments/lezione-05/slide-07-img-002.png|350]]
*Figura: Magnetizzazione vs temperatura da simulazione Monte Carlo (10×10).*

### Slide 8: Domini magnetici e correlazione
- Sopra $T_c$ non esiste ordine a lungo raggio, ma su scale piccole gli spin sono correlati: esistono [[Domini magnetici|domini magnetici]] di dimensione finita.
- Sotto $T_c$ i domini ordinati si estendono all'infinito (spanning), anche se a temperature finite permangono fluttuazioni disordinate su scale piccole.

![[attachments/lezione-05/slide-08-img-000.png|400]]
*Figura: Configurazioni di equilibrio del modello di Ising al di sotto, a e al di sopra di $T_c$.*

### Slide 9: Riferimenti
- Link a risorse su transizioni ordine-disordine.

### Slide 10-11: Toy Models
- Definizione e caratteristiche dei [[Toy Models|toy models]] in fisica.
- Modelli semplici con pochi parametri per investigare aspetti specifici di sistemi complessi.
- Utili per esperimenti "what-if" controllati.

### Slide 12-14: Modello di Schelling
- Il [[Modello di Schelling]] è un esempio di modellazione computazionale applicata alla sociologia.
- Schelling dimostrò che la [[Segregazione|segregazione]] residenziale non richiede estrema intolleranza: anche preferenze deboli per vicini simili generano effetti macroscopici di segregazione.
- Griglia bidimensionale con agenti di due famiglie che si spostano se la percentuale di vicini simili è inferiore a una soglia.

![[attachments/lezione-05/slide-13-img-000.png|350]]
*Figura: Mappa etnica di Chicago (1960).*

![[attachments/lezione-05/slide-13-img-001.png|350]]
*Figura: Mappa etnica di Chicago (1940).*

![[attachments/lezione-05/slide-13-img-002.png|300]]
*Figura: Titolo del paper originale di Schelling (1971).*

### Slide 15-17: Dettagli del Modello di Schelling
- Ogni agente è inserito casualmente in un reticolo 2D.
- A ogni iterazione, l'agente decide se spostarsi in base al numero di primi vicini diversi.
- La simulazione termina quando tutti gli elementi sono "soddisfatti" (happy).

![[attachments/lezione-05/slide-16-img-001.png|400]]
*Figura: Frazione di vicini identici vs tolleranza in una matrice 300×300.*

![[attachments/lezione-05/slide-17-img-000.png|350]]
*Figura: Griglia del modello di Schelling in uno stato intermedio.*

![[attachments/lezione-05/slide-17-img-001.png|350]]
*Figura: Griglia del modello di Schelling a convergenza (ticks: 37, unhappy: 0).*

### Slide 18-20: Introduzione ai Modelli ad Agente (ABM)
- I [[Modelli ad Agente]] si sono diffusi negli anni '90, ma hanno antenati famosi (Schelling, Boorman).
- Incorporano concetti di complessità, caos, informatica e automi cellulari.
- Un agente è un'entità che obbedisce a un insieme limitato di regole semplici; il sistema genera un modello ad agente.
- Secondo Gilbert: "l'agent-based modeling è un metodo computazionale che permette di creare, analizzare e sperimentare modelli composti da agenti che interagiscono in un ambiente."

### Slide 21: Conclusione
- Contatto: salvatore.micciche@unipa.it

## Collegamenti ai concetti

- [[Modello di Ising]] - Paradigma fisico per transizioni ordine-disordine.
- [[Spins]] - Variabili di stato del modello di Ising.
- [[Algoritmo Metropolis]] - Metodo Monte Carlo per la simulazione.
- [[Transizioni di Fase]] - Transizioni ordine-disordine e proprietà critiche.
- [[Magnetizzazione spontanea]] - Ordine a lungo raggio al di sotto di $T_c$.
- [[Temperatura critica]] - Temperatura critica del modello di Ising.
- [[Ordine e Disordine]] - Concetti fondamentali di organizzazione nei sistemi.
- [[Domini magnetici]] - Regioni di spin correlati sopra $T_c$.
- [[Toy Models]] - Modelli semplificati per investigare la dinamica dei sistemi.
- [[Modello di Schelling]] - Toy model per la segregazione residenziale.
- [[Segregazione]] - Fenomeno sociale modellato da Schelling.
- [[Modelli ad Agente]] - Strumenti computazionali per simulare sistemi complessi.

## Mappe dei contenuti

- [[Complessità]] - MOC dei concetti di complessità.
