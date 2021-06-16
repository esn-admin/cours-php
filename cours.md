Ligne de commande a ouvrir dans le bon dossier.
    -> Clique droit -> Gui Bash 
    -> Ouvrir le dossier dans visual studio code -> Terminal -> new terminal
    -> Si besoin, se placer dans le bon fichier en utilant cd 

# Uniquement la premiere fois

    -> git config --global user.name "Votre nom"
    -> git config --global user.email "Votre mail"
    -> git config --list -> Pour verifier si le nom et le mail sont ajouté correctement

# Relier notre dossier au repository 

    -> Si vous voulez ignorer des fichiers, creer un .gitignore
    -> git init 
    -> git add . -> git add . permet d'ajouter tout les fichiers (qui serons ajoutés apres)
    -> git status -> Permet de visualiser tout les fichiers et dossier qui sont pris en compte par git
        -> Si un fichier est bien pris en compte, il apparait en vert
        -> S'il n'est pas pris en compte, il apparait en rouge
    -> git commit -m "nom_de_mon_commit"

# Visualiser l'historique

    -> Git log -> Cette commande nous permet d'avoir accès a tout l'historique des commits. Nous avons des infos spécifiques a chaque commit tel que l'auteur, la date, le nom du commit, et l'identifiant du commit 
    -> Git show numero-de-version -> Permet de visualiser un fichier a un moment précis
    -> git reset --hard numero-de-version -> Permet de revenir brutalement a la version antérieur choisie


