---
title: Previsione
date: 2024-05-02
tags:
  - concetto
  - caos
  - sistemi-complessi
  - epistemologia
aliases:
  - Predictability
  - Predicibilità
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_03.pptx
---

# Previsione

> [!definition] Previsione
> La previsione è la capacità di determinare lo stato futuro di un sistema a partire dalla conoscenza del suo stato attuale e delle leggi di evoluzione. A differenza del [[Determinismo|determinismo]], che è una proprietà intrinseca del sistema, la previsione dipende dalle capacità dell'osservatore, dalla precisione delle condizioni iniziali e dalla potenza di calcolo disponibile.

## Determinismo ≠ Previsione

È fondamentale distinguere questi due concetti:
- **Determinismo**: il sistema evolve secondo leggi fisse — è una proprietà ontologica.
- **Previsione**: l'osservatore riesce a calcolare tale evoluzione — è una proprietà epistemologica.

Il determinismo non implica la possibilità di fare previsioni accurate. Questa è la lezione fondamentale della teoria del caos.

## Limiti alla previsione

### 1. Incertezza sulle condizioni iniziali

La conoscenza della condizione iniziale è sempre solo approssimativa, con un certo margine di incertezza (errore sperimentale). Nei sistemi caotici, questa incertezza cresce esponenzialmente, rendendo la previsione impossibile oltre un certo orizzonte temporale.

### 2. Tempo di predicibilità

Il tempo entro cui una previsione rimane accurata è detto **tempo di predicibilità**:

$$T \sim \frac{1}{\lambda} \ln\left(\frac{\Delta}{|\delta x(0)|}\right)$$

dove $\lambda$ è l'[[Esponenti di Lyapunov|esponente di Lyapunov]]. Poiché il logaritmo cresce lentamente, il tempo di predicibilità è essenzialmente determinato dall'inverso dell'esponente di Lyapunov.

### 3. Complessità computazionale

Anche quando le leggi sono note, la risoluzione esatta può essere proibitiva. Esempio: le palline della roulette obbediscono alle leggi della meccanica di Newton, proprio come i corpi celesti, ma nessuno risolve le equazioni di Newton per predire l'uscita.

## Crisi del riduzionismo

Il fallimento della previsione in sistemi apparentemente semplici (come il moto dei tre corpi) rappresenta una [[Crisi del riduzionismo|crisi del riduzionismo]]: conoscere le leggi fondamentali non è sufficiente per predire il comportamento macroscopico.

## Collegamenti

- [[Determinismo]] - Il determinismo non garantisce la previsione.
- [[Caos deterministico]] - Il caos pone limiti fondamentali alla previsione.
- [[Effetto farfalla]] - La sensibilità alle condizioni iniziali rende la previsione difficile.
- [[Esponenti di Lyapunov]] - Quantificano il limite temporale di predicibilità.
- [[Crisi del riduzionismo]] - Il fallimento della previsione sfida il riduzionismo.
