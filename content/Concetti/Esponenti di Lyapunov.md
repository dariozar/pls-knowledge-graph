---
title: Esponenti di Lyapunov
date: 2024-05-02
tags:
  - concetto
  - caos
  - sistemi-complessi
  - matematica
  - misura
aliases:
  - Lyapunov Exponents
  - Esponente di Lyapunov
source: SLIDES/Lezione_PLS_FIS-STAT-SIST-COMPL_03.pptx
---

# Esponenti di Lyapunov

> [!definition] Esponenti di Lyapunov
> Gli esponenti di Lyapunov sono grandezze che misurano il tasso di divergenza esponenziale di traiettorie infinitesimamente vicine nello spazio delle fasi. L'esponente $\lambda$ corrisponde alla massima dilatazione dello spazio delle fasi e determina il tempo di predicibilità di un sistema caotico.

## Definizione matematica

Se il sistema è caotico, un'incertezza inizialmente molto piccola cresce esponenzialmente nel tempo:

$$|\delta x(t)| \sim e^{\lambda t} |\delta x(0)|$$

dove $\lambda$ è l'esponente di Lyapunov.

## Tempo di predicibilità

Il sistema può essere predetto con una tolleranza $\Delta$ solo fino al tempo di predicibilità $T$:

$$T \sim \frac{1}{\lambda} \ln\left(\frac{\Delta}{|\delta x(0)|}\right)$$

Poiché la funzione logaritmo cresce molto lentamente:
- $\ln(5) \approx 1.609$
- $\ln(10) \approx 2.302$
- $\ln(20) \approx 2.995$
- $\ln(40) \approx 3.688$

il tempo di predicibilità è determinato sostanzialmente dall'esponente di Lyapunov e, poco, dallo sforzo per determinare le condizioni iniziali con grande precisione.

## Interpretazione

- Se $\lambda > 0$: il sistema è caotico — traiettorie vicine divergono esponenzialmente.
- Se $\lambda < 0$: il sistema è stabile — traiettorie vicine convergono.
- Se $\lambda = 0$: il sistema è marginalmente stabile.

## Connessione con l'entropia

Gli esponenti di Lyapunov hanno a che fare con l'evoluzione probabilistica del sistema caotico. Il [[Teorema di Pesin]] collega direttamente l'entropia alla somma degli esponenti di Lyapunov positivi:

$$h = \sum_{\lambda_i > 0} \lambda_i$$

## Collegamenti

- [[Caos deterministico]] - Gli esponenti di Lyapunov quantificano il caos.
- [[Effetto farfalla]] - Misurano l'amplificazione delle perturbazioni.
- [[Nonlinearità]] - La nonlinearità genera esponenti di Lyapunov positivi.
- [[Entropia]] - Connessa tramite il teorema di Pesin.
- [[Previsione]] - Determinano il limite temporale di predicibilità.
