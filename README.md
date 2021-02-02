# toto

## Je met un sous titre 

Ceci est un Github de test (ça ne veut rien dire ^^)


Nouveau commit

## Configuration de git en local

Dans le terminal, avec la commande git config, on va pouvoir configurer certaines informations afin de signer correctement les commits. 
On a ajouté le nom d'utilisateur : git config --global user.name "nom_user"
On a ajouté l'adresse email : git config --global user.email "notre@email"

Pour vérifier que ces informations ont été bien enregistrées, on peut les lister dans le terminal : git config --global --list

## git clone

Cette commande permet de récupérer une copie d'un dépot distant sur notre machine. 
On peut ainsi travailler en local avec VS code, ce qui est plus pratique que de travailler directement sur github.


## git pull

Avec cette commande on va pouvoir récupérer le projet distant mis à jour dans notre dépot local.

## git add

Dans VScode on peut ajouter une nouvelle version d'un fichier à la zone de surveillance en cliquant sur le bouton + dans la section "contrôle de code source".

## git commit

Avec cette commande, on enregistre dans l'historique une nouvelle version de notre application. Dans VScode, dans la section "Contrôle de code source", on a une zone de saisie pour indiquer le message du commit (message le plus précis possible afin de retrouver facilement différentes versions du projet)

## git push

Afin de garder aussi ressemblant que possible le dépot local et le dépot distant, on va envoyer les modifications sur github avec la commande push.