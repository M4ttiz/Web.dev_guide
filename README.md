# Web.dev Guide - Corso Interattivo HTML/CSS

Web.dev Guide è un corso interattivo, statico e senza dipendenze per imparare HTML e CSS direttamente nel browser.

## Funzionalità

- Single-page application realizzata con JavaScript vanilla.
- 17 lezioni progressive con teoria, esempi, esercizi e soluzioni.
- Live Playground con editor HTML e CSS separati.
- Anteprima live isolata in un iframe sandbox.
- Quiz a scelta multipla con feedback immediato.
- Sblocco progressivo delle lezioni.
- Salvataggio di progressi, quiz, bozze e preferenza del tema tramite `localStorage`.
- Progress bar globale e indicatori di completamento nella sidebar.
- Modalità chiara/scura persistente.
- Navigazione da tastiera con frecce sinistra/destra.
- Layout responsive per desktop, tablet e smartphone.
- Syntax highlighting personalizzato senza librerie esterne.

## Requisiti

È sufficiente un browser moderno. Non sono necessari Node.js, un bundler o dipendenze da installare.

## Avvio locale

1. Clona la repository:

	```bash
	git clone https://github.com/M4ttiz/Web.dev_guide.git
	cd Web.dev_guide
	```

2. Avvia un server HTTP locale. Con Python:

	```bash
	python3 -m http.server 8000
	```

3. Apri `http://localhost:8000` nel browser.

## Pubblicazione con GitHub Pages

1. Esegui i comandi elencati in [DEPLOYMENT.md](DEPLOYMENT.md).
2. Apri la repository su GitHub.
3. Vai in **Settings** > **Pages**.
4. Seleziona **Deploy from a branch**, il branch `main` e la cartella `/ (root)`.
5. Premi **Save** e attendi il completamento della pubblicazione.

L'applicazione è statica: GitHub Pages pubblica direttamente `index.html` dalla root del branch `main`.

## Struttura del progetto

```text
Web.dev_guide/
├── index.html
├── style.css
├── app.js
├── README.md
├── LICENSE
└── DEPLOYMENT.md
```

## Aggiornare il sito pubblicato

```bash
git add .
git commit -m "Update course content"
git push origin main
```

## Licenza

Il progetto è distribuito con licenza MIT. Consulta [LICENSE](LICENSE).