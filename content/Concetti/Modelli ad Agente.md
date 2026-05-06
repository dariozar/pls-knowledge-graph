---
title: Modelli ad Agente
date: 2024-04-16
tags:
  - fisica-statistica
  - simulazione
  - modelli-computazionali
aliases:
  - Agent Based Models
  - ABM
source: Lezione 01 - Introduzione alla Complessità, SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_05.pptx
---

# Modelli ad Agente

> [!definition] Modello ad agente
> Un modello ad agente (Agent-Based Model, ABM) è una classe di modelli computazionali per simulare le azioni e le interazioni di agenti autonomi (singoli entità come individui, famiglie, cellule) all'interno di un ambiente, al fine di comprendere il comportamento emergente del sistema nel suo complesso. Ogni agente obbedisce a regole semplici; il sistema complessivo è l'esito delle interazioni.

I modelli ad agente sono particolarmente utili per studiare sistemi complessi dove la risoluzione analitica è impossibile o troppo complicata. Esempi includono la formazione di banchi di uccelli (flocking), la diffusione di epidemie, i mercati finanziari e i comportamenti sociali. In ambiente NetLogo, è possibile creare simulazioni interattive di modelli ad agente.

> [!info] NetLogo e simulazioni interattive
> NetLogo è un ambiente di programmazione per modelli ad agente, sviluppato dal Center for Connected Learning and Computer-Based Modeling (CCL) della Northwestern University. Offre un'interfaccia grafica per progettare agenti (turtles), ambiente (patches) e regole di interazione. Il modello "Flocking" (stormo) è un esempio classico: ogni uccello segue regole semplici di allineamento, coesione e separazione, generando il comportamento collettivo sincronizzato degli stormi.

## Storia e Sviluppo

I modelli ad agente hanno iniziato a diffondersi nelle comunità accademiche e di ricerca all'inizio degli anni novanta. Tuttavia, hanno antenati famosi:

- **[[Modello di Schelling]]** (1971): uno degli antenati più celebri, riguardante la segregazione razziale in una città.
- **Modello di Boorman**: modello classico sulla diffusione di informazioni lavorative attraverso legami forti e deboli.
- Durante gli anni '90, concetti e strumenti della complessità, teoria del caos, informatica e automi cellulari furono incorporati nello sviluppo del **Agent-Based Modeling**.

## Implementazione: NetLogo

NetLogo è un ambiente di programmazione per modelli ad agente sviluppato dal Center for Connected Learning and Computer-Based Modeling (CCL) della Northwestern University. Offre un'interfaccia grafica per progettare agenti (*turtles*), ambiente (*patches*) e regole di interazione.

## Esempi Classici

- **Flocking**: ogni uccello segue regole semplici di allineamento, coesione e separazione, generando il comportamento collettivo sincronizzato degli stormi.
- **[[Modello di Schelling]]**: agenti su una griglia che si muovono in base alla composizione del vicinato; emerge segregazione residenziale.

## Collegamenti

- [[Sistemi Complessi]] - I modelli ad agente sono strumenti per studiare i sistemi complessi.
- [[Fenomeni Collettivi]] - I modelli ad agenti spiegano i fenomeni collettivi.
- [[Herding]] - Il comportamento di gregge può essere modellato con ABM.
- [[Reti e Topologia]] - Gli agenti interagiscono su reti.
- [[Fenomeni Emergenti]] - Le proprietà emergenti sono generate dalle interazioni tra agenti.
- [[Modello di Schelling]] - Esempio classico di modello ad agente in sociologia.
- [[Spins]] - Spin del modello di Ising come precursori di agenti.
- [[Toy Models]] - I modelli ad agente sono spesso usati per implementare toy models.