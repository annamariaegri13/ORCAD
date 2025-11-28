Proiect Tehnici CAD – Senzor de nivel

Acest proiect realizează proiectarea și simularea unui sistem de control al nivelului de apă într-un rezervor, utilizând un senzor rezistiv de nivel, amplificare, comparare și comandă prin releu.

Descriere:

Sistemul măsoară nivelul apei folosind un senzor cu rezistență variabilă (4–19 kΩ), transformă semnalul în tensiune, îl amplifică diferențial și îl compară cu două praguri pentru a comanda o pompă printr-un releu. Starea pompei este indicată printr-un LED portocaliu.

Etapele circuitului:

Senzor + sursă de curent: convertirea rezistenței în tensiune (0–13 V).
Repetor tensiune (LM358): eliminarea pierderilor.
Amplificator diferențial: normalizarea semnalului cu referința VREF1.
Comparator cu histerezis: prag jos ≈ 1.23 V, prag sus ≈ 11.04 V.
Driver + releu: tranzistor NPN 2N2222 pentru comanda pompei.
LED semnalizare: modelare și conectare prin rezistoare calculate.

Simulări incluse:

Analiză parametrică, Monte Carlo (toleranțe componente), Worst-Case, DC Sweep
