---
title: Inverted Repeats
date: 2026-04-02
tags:
  - biologia
  - genomica
  - bioinformatica
aliases:
  - Inverted Repeats (Biologia)
  - IR
  - Sequenze Invertite Ripetute
source: Lezione 02 - Fenomeni Emergenti e Leggi di Potenza
---
> [!definition] Inverted Repeats (IR)
> Gli Inverted Repeats (IR) sono sequenze di nucleotidi in un genoma dove una sequenza di basi è seguita, a distanza variabile (loop), dalla sua sequenza complementare invertita. Quando un singolo filamento di RNA (o DNA a doppio filamento) presenta una sequenza IR, può formare una struttura a forcina (hairpin) nell'RNA o una struttura cruciforme nel DNA.

## Struttura

Una sequenza IR tipica ha la forma:

```
...5'... AGACCCCCACTGCTAAATATAGTGGGTGGGTG ...3'...
         | stem |    loop    |  stem  |
```

La sequenza si ripiega su sé stessa formando:
- **Stem**: la parte appaiata della struttura, dove le basi complementari si legano.
- **Loop**: la regione non appaiata che collega i due tratti del gambo.

## Funzione regolativa

> [!info] Funzione biologica degli IR
> Gli Inverted Repeats svolgono un ruolo fondamentale nella regolazione dell'espressione genica:

- **Terminazione trascrizionale Rho-indipendente**: negli organismi batterici, gli IR nell'mRNA possono formare strutture a forcina che fungono da terminatori di trascrizione Rho-indipendenti.
- **Virus Induced Gene Silencing (VIGS)**: tecnologia basata su meccanismi di difesa antivirale mediati da RNA. In piante infettate da virus modificati, tale meccanismo può essere indirizzato contro specifici geni della pianta stessa.
- **Regolazione del triptofano**: a seconda della concentrazione di triptofano, la formazione di IR può essere favorita o impedita, risultando nella trascrizione completa o incompleta di mRNA in E. coli.

## IR nei genomi virali

Nei 746 genomi virali completamente sequenziati, la presenza di IR è stata analizzata tramite il [[Distribuzione Chi-Quadrato|test del chi-quadrato]]. Il risultato mostra che nel 57% dei genomi virali i valori-p sono inferiori a 0.05, indicando che gli IR non sono distribuiti casualmente. Questo suggerisce che esiste una struttura organizzativa nei genomi virali che va oltre il semplice contenuto sequenziale — un [[Fenomeni Emergenti|fenomeno emergente]] legato alla struttura terziaria.

> [!example] IR come fenomeno emergente
> Se si considerano solo le frequenze di basi, i genomi virali sembrerebbero sequenze casuali. Tuttavia, la distribuzione non casuale degli IR rivela proprietà organizzative che emergono solo a livello strutturale. Il contenuto non è sufficiente per spiegare il tutto: la struttura terziaria porta a proprietà che il riduzionismo non può predire.

## Collegamenti

- [[Fenomeni Emergenti]] - La distribuzione non casuale degli IR è un esempio di emergenza.
- [[Distribuzione Chi-Quadrato]] - Il test χ² è usato per verificare la significatività statistica degli IR.
- [[Leggi di Potenza]] - La distribuzione delle sequenze genomiche può seguire leggi di potenza.
- [[Legge di Zipf]] - Analisi di frequenza delle sequenze genomiche.
