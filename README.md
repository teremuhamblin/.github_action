###### README.md * markdown / Projet final réorganisé : 

# 📄 .github_action
###### Remis au propre, structuré, cohérent et professionnel.
> 🚀 Ce projet contient un exemple minimaliste d’un workflow GitHub Actions.  
- À chaque git push, le workflow se déclenche automatiquement et affiche un simple message dans les logs.

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
```text
.github_action/
│
├── .github/
│   └── workflows/
│       └── hello.yml
│
└── README.md
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
