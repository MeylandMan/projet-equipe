# Projet d'équipe

Ce dépôt est présent juste pour apprendre les bonnes pratiques du travail en équipe sur github.

## Équipe
Etudiant B : Jean-Paul ANGUILLET
Etudiant A : NGNARE DIOP Allan Meyland Gédéon

## Commandes Git utilisés

### Etudiant A (MeylandMan)
* ``git init``
* ``git add .``
* ``git commit -m "Initialisation du projet equipe"``
* ``git remote add origin https://github.com/MeylandMan/projet-equipe.git``
* ``git branch -M main``
* ``git push -u origin main``
* ``git checkout -b feature/etudiant-a-contenu``
* ``git add .``
* ``git commit -m "Ajout du contenu principal par Etudiant A"``
* ``git push origin feature/etudiant-a-contenu``
* ``git checkout stable``
* ``git merge feature/meyland-contenu``
* ``git fetch origin``
* ``git merge origin/feature/etudiant-b-style``
* ``git push origin stable``

### Etudiant B (Jean Paul)
* ``git clone https://github.com/MeylandMan/projet-equipe.git``
* ``git checkout -b feature/etudiant-b-style``
* ``git add .``
* ``git commit -m "Ajout CSS par Etudiant B"``
* ``git push origin feature/etudiant-b-style``
