-Creation du repository Exercice2_GitHub sur git hub sans fichier readme.md par defaut.

-Creation du repository en local sur la machine :git init pour activer le dissier en tant que repository git.git status pour verifier qu'on se trouve bien dans un repository git


-Creation et ajout du fichier README.txt par la commande touch Readme.txt  git add pour indexer le fichier.Puis on effectue un commit par la commande git commit -m "ajout du fichier readme."

-Envoi vers le remote (github) , il a fallu specifier le remote comme origin par la commande "git remote add origin https://github.com/nom_utilisateur/nomrepository ; en effet au départ je n'arrivais pas a faire un git push origin master : il y avait un message d'erreur comme si il ne reconnaissait pas le remote (ou la branche)

-Entre chaque étape bien verifier avec la commande git status pour verifier si on doit faire un commit et  si le fichier est bien indexé

**1 ere Modification fichier , ajout 2 fichiers style.css et page.html

-Creation puis commit de 2 fichiers :page.html et style.css :commanndes utilisées touch pour la creation , vim pour editer , ensuite commande git add pour indexer et git commit pour enregistrer les commits avec messages.

-Envoi vers le remote avec la commande " git push origin master"

