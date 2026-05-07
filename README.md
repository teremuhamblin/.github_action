###### README.md * markdown
###### 🚀 Projet :
## .github_action

### ▶️ Exécution
>À chaque git push, GitHub Actions lance automatiquement le workflow et affiche :
```md
Hello
```

### 🎯 Objectif
>Ce projet sert d’exemple minimal pour comprendre :
```md
- la structure .github/workflows/
- le fonctionnement d’un workflow GitHub Actions
- l’exécution d’un job simple
```

---
###  📁 Structure de base du projet :
```text
Hello.yml/
│
├── .github/
│   └── workflows/
│       └── hello.yml
│
└── README.md
```

---

### 📄 .github/workflows/hello.yml
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

---
