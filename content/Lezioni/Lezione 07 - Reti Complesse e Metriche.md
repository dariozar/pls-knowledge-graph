---
title: Lezione 07 - Reti Complesse e Metriche
date: 2024-05-16
tags:
  - lezione
  - reti
  - networks
  - metriche
aliases:
  - Lezione 7 - Reti Complesse e Metriche
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_07.pptx
---

# Lezione 07 - Reti Complesse e Metriche

Questa lezione introduce il linguaggio della teoria dei grafi e delle reti complesse, coprendo definizioni fondamentali, metriche di centralità e struttura, modelli di rete classici, e applicazioni alla diffusione di epidemie su reti di contatti.

## Riassunto degli slide

### Slide 1-3: Introduzione
- Presentazione del corso e data (16 Maggio 2024)
- Argomenti della lezione: Networks, Metrics, Adjacency matrix, Network models

### Slide 4-7: Esempi di reti complesse
- Mappa parziale di Internet (opte.org)
- Reti sociali, di trasporto, biologiche, di collaborazione
- Nodi = entità, Link = relazioni
- Le reti sono caratterizzate da evoluzione temporale e organizzazione topologica
- Obiettivi: osservazione, modellizzazione, spiegazione del "perché" e del "come"

![[attachments/lezione-07/slide-04-img-000.png|400]]

### Slide 8-21: Definizioni di base
- **Grafo**: $G=(V,E)$ con vertici e archi
- **Sottografo** e **sottografo indotto**
- **Multigrafo**: grafi con self-loop e/o multi-archi
- [[Grafi Diretti e Multi-digrafi]] - Digraph e multi-digrafi
- [[Walk, Trail, Path, Circuit]] - Cammini, sentieri, percorsi e cicli
- [[Connected Components]] - Connettività e componenti connesse
- [[Clique]] - Grafi completi, d-regolari e clique
- [[Bipartite Networks]] - Reti bipartite e grafi proiettati

![[attachments/lezione-07/slide-12-img-000.png|300]]
![[attachments/lezione-07/slide-14-img-000.png|300]]
![[attachments/lezione-07/slide-16-img-000.png|300]]

### Slide 22-37: Metriche di rete
- [[Degree]] - Grado, sequenza di grado, in-degree/out-degree
- [[Weighted Graphs]] - Forza (strength) e gradi pesati
- [[Betweenness]] - Betweenness di nodi e archi (esempio Piazza Indipendenza vs Belgio/Strasburgo)
- [[Shortest Path]] e [[Diametro della rete]] - Distanza minima e diametro
- [[Clustering Coefficient]] - Locale e globale
- [[Assortatività]] - Grado medio dei vicini più prossimi
- Applicazione: identificazione di collegamenti tra clan mafiosi tramite shortest path

![[attachments/lezione-07/slide-23-img-000.png|300]]
![[attachments/lezione-07/slide-27-img-000.png|300]]
![[attachments/lezione-07/slide-31-img-000.png|300]]
![[attachments/lezione-07/slide-32-img-000.png|300]]

### Slide 38-42: Rappresentazioni computazionali
- [[Adjacency Matrix]] - Matrice simmetrica (non diretta) e non simmetrica (diretta); potenze della matrice e cammini di lunghezza $r$
- [[Adjacency List]] - Lista di adiacenza
- Complessità: $O(N_V^2)$ per matrice vs $O(N_V+N_E)$ per lista

![[attachments/lezione-07/slide-39-img-000.png|400]]

### Slide 43-48: Modelli di rete
- [[Erdos-Renyi Model]] - Connessione casuale con probabilità $p$; distribuzione di Poisson per $n$ grande
- [[Barabasi-Albert Model]] - Attachment preferenziale; coda della distribuzione di grado che decade lentamente (scale-free)
- [[Watts-Strogatz Model]] - Nodi localmente connessi + legami deboli (weak ties); small-world
- [[Borgatti-Everett Model]] - Modello a blocchi core-periphery
- Visualizzazioni interattive su NetLogo

![[attachments/lezione-07/slide-44-img-000.png|300]]
![[attachments/lezione-07/slide-45-img-000.png|300]]
![[attachments/lezione-07/slide-46-img-000.png|300]]

### Slide 49-56: Modello SIR e diffusione su reti
- [[SIR Model]] - Compartimenti Susceptible, Infected, Removed; equazioni differenziali; evoluzione temporale
- [[Networked SIR Model]] - Limiti dell'approccio fully-mixing; diffusione su network di contatti
- Simulazione interattiva del modello SIR su network (uni-graz.at)

![[attachments/lezione-07/slide-53-img-000.png|400]]

### Slide 57-67: Immunizzazione e percolazione
- [[Percolazione]] - Flusso attraverso un mezzo poroso; componente gigante; soglia di percolazione
- [[Immunization on networks]] - Immunizzazione come rimozione di nodi; condizione di Molloy-Reed per l'emergere della componente gigante
- Esempi: reti regolari, Erdos-Renyi, scale-free; nelle reti scale-free infinite servono immunizzare tutti i nodi ($\pi \to 1$)
- Signature del percolation threshold: confronto rimozione per degree vs betweenness

![[attachments/lezione-07/slide-60-img-000.png|300]]
![[attachments/lezione-07/slide-67-img-000.png|400]]

### Slide 68: Avvertenza
- Note a supporto degli studenti; consultazione NON esime dallo studio sui libri di testo.

## Collegamenti ai concetti
- [[Reti e Topologia]] - Panoramica completa su reti e topologia
- [[Grafi Diretti e Multi-digrafi]] - Grafi con direzionalità e multi-archi
- [[Walk, Trail, Path, Circuit]] - Definizioni di percorsi su grafi
- [[Connected Components]] - Componenti connesse
- [[Clique]] - Sottografi completi
- [[Bipartite Networks]] - Reti bipartite
- [[Degree]] - Metrica di centralità per grado
- [[Weighted Graphs]] - Grafi pesati e forza
- [[Betweenness]] - Centralità di intermediazione
- [[Shortest Path]] - Cammini minimi
- [[Diametro della rete]] - Diametro di una rete
- [[Clustering Coefficient]] - Coefficiente di clustering
- [[Assortatività]] - Assortatività per grado
- [[Adjacency Matrix]] - Rappresentazione matriciale
- [[Adjacency List]] - Rappresentazione per liste
- [[Erdos-Renyi Model]] - Modello di rete casuale
- [[Barabasi-Albert Model]] - Modello scale-free
- [[Watts-Strogatz Model]] - Modello small-world
- [[Borgatti-Everett Model]] - Modello core-periphery
- [[SIR Model]] - Modello epidemico classico
- [[Networked SIR Model]] - SIR su reti
- [[Percolazione]] - Teoria della percolazione
- [[Immunization on networks]] - Immunizzazione su reti

## Mappe dei contenuti
- [[Complessità]] - MOC dei concetti di complessità.
- [[Reti e Topologia]] - MOC dedicato alle reti e ai grafi.
