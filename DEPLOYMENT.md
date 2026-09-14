# Deployment su GitHub

Comandi esatti da eseguire nella root del progetto:

```bash
git init
git branch -M main
git remote add origin https://github.com/M4ttiz/Web.dev_guide.git
git add index.html style.css app.js README.md LICENSE DEPLOYMENT.md
git commit -m "Initial release of Web.dev Guide"
git push -u origin main
```

Se il remote `origin` esiste già:

```bash
git remote set-url origin https://github.com/M4ttiz/Web.dev_guide.git
git add index.html style.css app.js README.md LICENSE DEPLOYMENT.md
git commit -m "Update Web.dev Guide"
git push -u origin main
```

Per gli aggiornamenti successivi:

```bash
git add .
git commit -m "Update course content"
git push origin main
```

Dopo il primo push, abilita GitHub Pages da **Settings** > **Pages**, scegliendo il branch `main` e la directory `/ (root)` come sorgente.
