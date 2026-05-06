---
title: Effetto farfalla
date: 2024-05-02
tags:
  - concetto
  - caos
  - sistemi-complessi
  - sensibilità-condizioni-iniziali
aliases:
  - Butterfly Effect
  - Sensibilità alle condizioni iniziali
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_03.pptx
---

# Effetto farfalla

> [!definition] Effetto farfalla
> L'effetto farfalla è la caratteristica dei sistemi caotici per cui piccole variazioni nelle condizioni iniziali producono effetti enormemente amplificati nell'evoluzione futura del sistema. Il nome deriva dalla metafora secondo cui il battito d'ali di una farfalla in Brasile potrebbe scatenare un tornado in Texas.

## Origine del concetto

Il termine fu reso popolare da Edward Lorenz nel 1972, nel contesto della meteorologia. Lorenz scoprì che le sue equazioni del moto atmosferico mostravano una sensibilità estrema alle condizioni iniziali: arrotondando i dati di input da sei a tre cifre decimali, ottenne previsioni completamente diverse.

## Implicazioni per la previsione

L'effetto farfalla ha conseguenze profonde:
- La previsione a lungo termine diventa impossibile, anche conoscendo perfettamente le leggi fisiche.
- La conoscenza della condizione iniziale è sempre solo approssimativa, con un margine di incertezza (errore sperimentale).
- Questa incertezza, per quanto piccola, cresce esponenzialmente nel tempo nei sistemi caotici.

## Esempio numerico

Considerando la mappa $x_{t+1} = x_t^2 - 2$:
- Partendo da $x_0 = 0.5$ e $x_0' = 0.50001$ (differenza di $10^{-5}$)
- Dopo poche iterazioni le traiettorie divergono completamente:
  - $x_3 \approx -0.87109$ vs $x_3' \approx -0.87116$
  - $x_{15} \approx 0.31690$ vs $x_{15}' \approx 0.64501$
  - $x_{18} \approx 0.58626$ vs $x_{18}' \approx -1.74099$

Questo esempio mostra come due condizioni iniziali quasi identiche producano evoluzioni completamente diverse.

## Collegamenti

- [[Caos deterministico]] - L'effetto farfalla è la caratteristica distintiva del caos.
- [[Esponenti di Lyapunov]] - Misurano quantitativamente l'amplificazione delle perturbazioni.
- [[Nonlinearità]] - La sorgente matematica dell'effetto farfalla.
- [[Previsione]] - L'effetto farfalla pone limiti fondamentali alla previsione.
- [[Modello di Lorenz]] - Il sistema in cui Lorenz scoprì l'effetto farfalla.
