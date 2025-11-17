# Mini Application Web en Python avec Flask

Ce projet permet de créer une petite application web en Python avec deux pages HTML et un fichier CSS.

## Objectif

Apprendre :

* à créer un serveur web minimal avec Flask
* à organiser un projet (app.py, templates, static)
* à utiliser HTML et CSS
* à lancer une application web locale

## Ce qu'il manque

* une base de données connectée avec une 

---

## 📁 Structure du projet

```
mon_app/
│
├── app.py
│
├── templates/
│   ├── base.html
│   ├── index.html
│   └── about.html
│
└── static/
    └── style.css
```

---

## 🧰 Prérequis

* Python installé (version 3.10+)
* Un terminal (macOS, Linux ou Windows)
* Flask installé dans un environnement virtuel

---

## 1️⃣ Créer et activer un environnement virtuel

Dans votre dossier de projet :

```bash
python3 -m venv venv
```

Puis activez-le :

```bash
source venv/bin/activate
```

*(Sur Windows : `venv\Scripts\activate`)*

---

## 2️⃣ Installer Flask

```bash
pip install flask
```

---

## 3️⃣ Créer les fichiers du projet

Créez les dossiers et fichiers suivants :

* `app.py`
* `templates/base.html`
* `templates/index.html`
* `templates/about.html`
* `static/style.css`

Le contenu de chaque fichier est fourni par l'enseignant.

---

## 4️⃣ Lancer l'application

Dans le terminal (environnement virtuel actif) :

```bash
python app.py
```

Ensuite, ouvrir un navigateur :

* Page d'accueil : [http://127.0.0.1:5000/](http://127.0.0.1:5000/)
* Page "À propos" : [http://127.0.0.1:5000/about](http://127.0.0.1:5000/about)

---

## 5️⃣ A vérifier

* Les deux pages HTML s'affichent correctement
* Le menu permet de naviguer entre les pages
* Le fichier CSS modifie bien l'apparence du site
* Le serveur reste actif dans le terminal

---

## 6️⃣ Exercices possibles (optionnel)

* Modifier les couleurs dans `style.css`
* Ajouter une troisième page HTML
* Ajouter une image dans le dossier `static/`
* Ajouter un style différent pour les titres
* Personnaliser le texte de chaque page

---

## Conseils

* Il faut **toujours activer l'environnement virtuel** avant de lancer l'application.
* Encourager l'exploration HTML/CSS, car Flask recharge automatiquement la page.
* Montrer comment lire les messages dans le terminal (erreurs, rechargements).

---

Bonne création d'applications web ! 🚀
