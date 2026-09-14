# Web.dev Guide - Corso Interattivo HTML/CSS

Web.dev Guide è un corso interattivo, statico e senza dipendenze per imparare HTML e CSS direttamente nel browser.

## Apri il corso online

<p align="center">
	<a href="https://m4ttiz.github.io/Web.dev_guide/">
		<strong>🚀 Apri Web.dev Guide</strong>
	</a>
</p>

Per seguire il corso, studiare la teoria, svolgere gli esercizi e usare il Live Playground **non è necessario clonare o scaricare questa repository**: apri direttamente il [sito web live](https://m4ttiz.github.io/Web.dev_guide/) in un browser moderno.

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

## Uso online

Apri il [sito pubblico](https://m4ttiz.github.io/Web.dev_guide/) per iniziare subito. Il corso funziona direttamente dal browser e salva i progressi, le risposte ai quiz, le bozze e la preferenza del tema nel `localStorage` del dispositivo.

## Sviluppo e contributi

Clona o scarica il codice **solo se vuoi modificare il sorgente, lavorare in locale o contribuire al progetto**.

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

Per proporre modifiche, aggiorna i file sorgente, verifica il comportamento in locale e invia un commit o una pull request.

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