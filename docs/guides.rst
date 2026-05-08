===========================
🧭 Guides Pratiques
===========================

Cette page regroupe les guides essentiels pour comprendre, utiliser et
étendre le projet ``.github_action``.

---------------------------
🚀 Démarrer avec le projet
---------------------------

1. Cloner le dépôt  
2. Consulter le fichier ``README.md``  
3. Explorer les workflows dans ``.github/workflows/``  
4. Lire la documentation dans ``docs/``  

---------------------------
⚙️ Comprendre les Workflows
---------------------------

Chaque workflow est déclenché automatiquement selon des événements GitHub
(push, pull request, release…).

Les logs permettent de vérifier :

- l’exécution correcte des jobs  
- les erreurs éventuelles  
- les étapes automatisées  

---------------------------
🛠 Ajouter un Workflow
---------------------------

1. Créer un fichier dans ``.github/workflows/``  
2. Définir les déclencheurs (``on:``)  
3. Ajouter les jobs  
4. Tester via un push  

---------------------------
📦 Publier une Release
---------------------------

1. Créer un tag  
2. Pousser le tag  
3. Le workflow ``release.yml`` génère automatiquement la release  
4. Le changelog est mis à jour dans ``docs/CHANGELOG.md``  

---------------------------
🤝 Contribuer au Projet
---------------------------

- Lire ``CONTRIBUTING.md``  
- Suivre les templates d’issues et de PR  
- Respecter le ``CODE_OF_CONDUCT.md``
