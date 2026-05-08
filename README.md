###### README.md * markdown / Projet final réorganisé :
###### 🛠️ Badge GitHub Actions
> 🛠️ Intégration Continue
<p align="right">
  
![Action Workflow](https://github.com/teremuhamblin/.github_action/actions/workflows/hello.yml/badge.svg)
<p/>



---

# 📄 .github_action
###### Remis au propre, structuré, cohérent et professionnel.
> 🚀 Ce projet contient un exemple minimaliste d’un workflow GitHub Actions.  
- À chaque git push, le workflow se déclenche automatiquement et affiche un simple message dans les logs.
- 📘 Voir le CHANGELOG complet : [docs/CHANGELOG.md](docs/CHANGELOG.md)

---

### ▶️ Exécution
>À chaque git push, GitHub Actions lance automatiquement le workflow et affiche :
```md
Hello
```

---

### 🎯 Objectif
>Ce projet sert d’exemple pour comprendre :
- la structure .github/workflows/
- le fonctionnement d’un workflow GitHub Actions
- l’exécution d’un job simple

---

### 📁 Structure du projet
>Ce message apparaît dans les logs du job `test`.
```text
.github_action/
│
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug.md
│   │   ├── feature.md
│   │   └── task.md
│   │
│   ├── PULL_REQUEST_TEMPLATE/
│   │   ├── general.md
│   │   ├── bugfix.md
│   │   └── feature.md
│   │
│   ├── .gitkeeps
│   ├── SECURITY.md 
│   ├── CODE_OF_CONDUCT.md
│   ├── CONTRIBUTING.md
│   ├── CODEOWNERS
│   ├── dependabot.yml
│   └── workflows/
│       └── hello.yml
├── docs/
│   ├── .gitkeeps
│
├── milestone.md
├── issue.md
├── release.md
├── README.md 
└── .gitkeeps
```

---

### 📄 Contenu du workflow :
##### .github/workflows/hello.yml
```yaml
name: Hello

on:
  push:

jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - name: Print Hello
        run: echo "Hello"
```

### 🤝 Contribution
>Les contributions sont les bienvenues.  
Merci de suivre les règles définies dans :
- CONTRIBUTING.md
- les templates de Pull Request
- les templates d’issues

---

### 🔐 Sécurité
Pour signaler une faille :  
👉 Voir SECURITY.md

---

### 👮 Code de conduite
👉 Voir CODEOFCONDUCT.md

---

### 👑 Propriétaires du code
👉 Voir CODEOWNERS

---

### 📜 Licence
>Ce projet peut être utilisé librement à titre d’exemple pédagogique.

---

### 🎯 Résultat et mise à jour
```md
Ton projet est maintenant :
- propre
- cohérent
- structuré
- professionnel
- prêt à être poussé sur GitHub
- prêt à être mise à jour 
```

---
