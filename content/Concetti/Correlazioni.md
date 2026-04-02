---
title: Correlazioni
date: 2026-03-26
tags:
aliases:
  - Correlations
source: Lezione 01 - Introduzione alla Complessità
---
> [!definition] Correlazione tra serie temporali
> La correlazione è una misura statistica della relazione lineare tra due o più variabili. Nel contesto dei sistemi complessi, si studiano le correlazioni tra le serie temporali delle componenti del sistema (es. prezzi di N azioni contemporaneamente negoziate). Il coefficiente di correlazione di Pearson quantifica la forza e la direzione della relazione lineare tra due serie.

Lo studio delle correlazioni è fondamentale per analizzare il comportamento collettivo di un ensemble di componenti. Ad esempio, nel mercato azionario, si calcola la matrice di correlazione tra i rendimenti di N azioni per identificare strutture di dipendenza comune. Questa matrice diventa la base per applicare tecniche di clustering gerarchico e ricostruire reti di correlazioni.

> [!info] Matrice di correlazione e struttura di mercato
> La matrice di correlazione dei rendimenti azionari rivela la struttura sottostante del mercato. Analizzando gli autovalori e gli autovettori di questa matrice, si possono identificare fattori comuni (principal components) che influenzano l'intero mercato. La decomposizione della matrice in parti "rumorosa" e "segnale" è un problema centrale nella teoria delle reti finanziarie e nella gestione del rischio di portafoglio.

## Collegamenti

- [[Clustering Gerarchico]] - Tecnica per filtrare l'informazione dalla matrice di correlazione.
- [[Reti e Topologia]] - Le correlazioni definiscono i link in una rete di componenti.
- [[Sistemi Complessi]] - Le correlazioni sono una caratteristica chiave dei sistemi complessi.
- [[Leggi di Potenza]] - Le distribuzioni delle correlazioni possono seguire leggi di potenza.