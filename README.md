# SN-projet-de-GIT
#  Mini-site de Présentation d’Entreprise

Ce projet est un mini-site statique développé dans le cadre du cours de Développement Web (HTML/CSS/JS/WordPress) et de l’épreuve de GIT.

---

## 📝 Objectif du projet

- Appliquer les **bonnes pratiques Git** sur un projet web concret.
- Utiliser une **stratégie de branches Git** bien définie.
- Créer un **site vitrine** présentant une entreprise fictive ou réelle.
- Intégrer progressivement les fonctionnalités du site via différentes branches.
- Tester et finaliser le projet dans une branche stable.

---

## 🧩 Technologies utilisées

- **HTML5** – Structure des pages
- **CSS3** – Mise en page, design responsive
- **JavaScript** – Interactions dynamiques (carrousel, menu burger, etc.)
- (Optionnel) **WordPress** – si le projet est sous CMS

---

## 📁 Structure du projet

```
projet-site-entreprise/
├── index.html
├── services.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
│   └── logo.png
└── README.md
```

---

## 🔀 Stratégie Git utilisée

### 🌿 Branches principales :

| Branche       | Rôle                                          |
|---------------|-----------------------------------------------|
| `main`        | Version stable et prête à être mise en ligne  |
| `dev`         | Intégration globale des fonctionnalités       |
| `test/*`      | Tests visuels et fonctionnels                 |
| `feature/*`   | Développement de fonctionnalités              |

### 🔁 Flux de travail :

```
feature/* → test/* → dev → main
```

---

## 🚧 Détail des branches `feature/*`

- `feature/html-structure` : structure HTML des pages
- `feature/css-theme` : charte graphique CSS
- `feature/js-interactions` : interactions dynamiques (menu, carrousel, animations)

---

## 🧪 Détail des tests

Branche `test/frontend` :
- Test d'intégration HTML + CSS
- Vérification de la cohérence visuelle
- Test des effets interactifs (JS)

---

## 🧰 Commandes Git utilisées

```bash
git init
git branch nom-branche
git checkout nom-branche
git add .
git commit -m "Message clair"
git merge branche-source
git push origin nom-branche
git pull origin nom-branche
```

---

## ✅ État d’avancement

- [x] Structure HTML terminée
- [x] Charte graphique CSS appliquée
- [x] Interactions JavaScript intégrées
- [x] Tests effectués
- [x] Fusion finale vers `main` prête pour mise en ligne

---

## 📌 Auteur

- Nom & Prénom :[TAMBA NGAH RAYAN SCOTT]  
- Classe : B1A
- École : Keyce Informatique & Intelligence Artificielle  
- Année académique : 2024-2025

---
