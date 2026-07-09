# IMPOSTOR

Das Social-Deduction-Trinkspiel im Undercover-Stil. Ein Handy, ein Spion, ein Wort — für 3 bis 10 Spieler.

**Live spielen:** https://leandrow114.github.io/Sauf2/

## So funktioniert's

1. Jedes Mal sieht eine Person heimlich ein leicht anderes Wort als der Rest.
2. Reihum sagt jeder am Tisch genau EIN Wort, das zu seinem Begriff passt.
3. Der Impostor muss faken und versuchen, nicht aufzufallen.
4. Diskutiert, stimmt ab und zeigt nach Ablauf der Zeit alle gleichzeitig auf den Spion!

## Features

- Vier Kategorien: **Standard**, **Mittel**, **Extrem**, **+18 Intim** — je 10 Wortpaare
- Pass-the-Phone-Modus mit verdeckter Wortübergabe
- 90-Sekunden-Diskussions-Timer
- Sauf-Abrechnung mit kategorieabhängigen Strafen
- Sound (Web Audio API) und Haptik (Vibration API)
- Brutalistischer Dark Mode, optimiert für Smartphones

## Technik

Eine einzige `index.html` — HTML, CSS und JavaScript inline, **zero externe Abhängigkeiten**. Funktioniert offline, sobald die Seite einmal geladen wurde.

## Deployment

Die Seite wird bei jedem Push auf `main` automatisch per GitHub Actions auf GitHub Pages deployt (`.github/workflows/deploy-pages.yml`). Der Workflow aktiviert GitHub Pages beim ersten Lauf selbst; alternativ lässt er sich unter *Actions → Deploy to GitHub Pages → Run workflow* manuell starten.
