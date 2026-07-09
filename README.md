# VERDACHT

Das Social-Deduction-Trinkspiel im Undercover-Stil. Ein Wort. Ein Spion. Kein Erbarmen — für 3 bis 10 Spieler.

**Live spielen:** https://leandrow114.github.io/Sauf2/

## So funktioniert's

1. Jedes Mal sieht eine Person heimlich ein leicht anderes Wort als der Rest.
2. Reihum sagt jeder am Tisch genau EIN Wort, das zu seinem Begriff passt.
3. Der Impostor muss faken und versuchen, nicht aufzufallen.
4. Nach der Diskussion stimmt jeder geheim in der App ab. Wer die meisten Stimmen kassiert, steht am Pranger — und dann wird abgerechnet!

## Features

- Vier Kategorien: **Standard**, **Mittel**, **Extrem**, **Intim 18+** — je 10 Wortpaare
- Spielernamen-Eingabe vor jeder Runde
- Pass-the-Phone-Modus mit verdeckter Wortübergabe (Wort-Screen invertiert in Acid-Lime)
- 90-Sekunden-Countdown mit animiertem Fortschritts-Ring
- Geheime In-App-Abstimmung: Jeder tippt verdeckt, wen er für den Spion hält
- Auflösung mit Stimmen-Tally, Erwischt/Entkommen-Verdikt und namentlicher Sauf-Abrechnung
- Sound (Web Audio API) und Haptik (Vibration API)
- Dark-Mode-Design mit Acid-Akzent, Film-Grain und Laufband-Ticker, optimiert für Smartphones

## Technik

Eine einzige `index.html` — HTML, CSS und JavaScript inline, **zero externe Abhängigkeiten**. Funktioniert offline, sobald die Seite einmal geladen wurde.

## Deployment

Die Seite wird bei jedem Push auf `main` automatisch per GitHub Actions auf GitHub Pages deployt (`.github/workflows/deploy-pages.yml`). Der Workflow aktiviert GitHub Pages beim ersten Lauf selbst; alternativ lässt er sich unter *Actions → Deploy to GitHub Pages → Run workflow* manuell starten.
