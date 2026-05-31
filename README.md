# 📊 Régression Polynomiale & Validation Croisée (K-Fold) en R

Ce projet contient une application interactive **Shiny** compilée grâce à `shinylive` (WebAssembly). Elle permet de visualiser en temps réel l'impact du choix du degré d'un polynôme lors d'une validation croisée (K-Fold Cross-Validation).

---

## 🚀 Lancer l'application en ligne

### 🌍 Option 1 : Via GitHub Pages (Lien direct)
Clique sur le lien ci-dessous pour accéder à l'application hébergée directement dans ton navigateur :
👉 [https://mmmjenhi.github.io/regression-R/edit/](https://mmmjenhi.github.io/regression-R/edit/)

### ⚡ Option 2 : Lien de secours (Interface Shinylive)
Si ton navigateur bloque le chargement des scripts de sécurité locaux (Service Workers), clique sur ce bouton pour forcer l'ouverture de l'application via le moteur officiel :

[![Lancer l'App Shiny](https://img.shields.io/badge/Shiny-Ouvrir%20l'application-blue?style=for-the-badge&logo=r)](https://shinylive.io/r/app/#code=https://github.com/MMMJENHI/regression-R)

---

## 🛠️ Exécuter localement dans RStudio

Tu n'as pas besoin de télécharger les fichiers sur ton ordinateur. Tu peux exécuter l'application originale directement dans ta console **RStudio** avec cette commande unique :

```R
shiny::runGitHub("regression-R", "MMMJENHI")
