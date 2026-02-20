#README – Projet Article Phishing
Initialisation

git init
git add .
git commit -m "Initial commit"
git remote add origin URL_DU_REPO
git push -u origin main

Création du README

Créer README.md en local

git add README.md
git commit -m "Ajout README"
git push

Création d’une branche

git switch -c nom_branche
git push -u origin nom_branche

Travailler sur une branche

git add .
git commit -m "Message clair"
git push

Voir les branches

git branch
git branch -r

Fusionner dans main

git switch main
git merge nom_branche
git push
