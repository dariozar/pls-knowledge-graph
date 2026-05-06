---
title: Clustering Gerarchico
date: 2024-04-16
tags:
  - fisica-statistica
  - statistica
  - metodi-computazionali
aliases:
  - Hierarchical Clustering
source: Lezione 01 - Introduzione alla Complessità
---

# Clustering Gerarchico

> [!definition] Clustering gerarchico
> Il clustering gerarchico è una tecnica di analisi dei dati che raggruppa oggetti in una struttura ad albero (dendrogramma) in base alla loro相似ità (o dissimilarità). A differenza del clustering partizionale, non richiede la specificazione a priori del numero di cluster; la gerarchia emerge naturalmente dal processo aggregativo (o divisivo).

Nello studio dei sistemi complessi, il clustering gerarchico viene utilizzato come tecnica di filtraggio dell'informazione. Ad esempio, partendo dalla matrice di correlazione tra prezzi azionari, si può costruire un dendrogramma che rivela la gerarchia dei settori di mercato e delle sottostrutture. Il dendrogramma visualizza in modo sintetico le relazioni tra le componenti del sistema, rendendo evidenti i gruppi naturali.

> [!info] Dendrogramma e interpretazione
> Un dendrogramma è un albero gerarchico dove le foglie rappresentano gli oggetti e le fusioni dei rami indicano la相似ità tra cluster. L'altezza delle fusioni rappresenta la distanza (o dissimilarità) tra i cluster uniti. Tagliando l'albero ad una certa altezza si ottiene una partizione del sistema in un numero definito di cluster. Nell'analisi finanziaria, i dendrogrammi aiutano a identificare settori correlati e a costruire portafogli diversificati.

## Collegamenti

- [[Correlazioni]] - La matrice di correlazione è l'input per il clustering gerarchico.
- [[Reti e Topologia]] - Il dendrogramma può essere interpretato come una rete gerarchica.
- [[Sistemi Complessi]] - Il clustering gerarchico è uno strumento per analizzare i sistemi complessi.
- [[Leggi di Potenza]] - Le distribuzioni delle distanze possono seguire leggi di potenza.