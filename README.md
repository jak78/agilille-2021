# AgiLille

Comment contribuer ?

Le site est construit avec Jekyll et publié sur GitHub Pages.

## Pour tester ses modifs en local

- Installer Docker.
- Lancer un terminal
- Se positionner dans le répertoire racine du repository 
- Puis lancer la commande suivante :


    ./server.sh

Après quelques secondes (quelques minutes au 1er lancement) vous pourrez alors saisir l'URL suivante dans votre navigateur :

    http://localhost:4000

Et voilà, votre AgiLille.fr local !

## Workflow

Pour publier, pousser vos modifications sur `master`:

    git checkout master
    # make your changes
    git add .
    git commit -m "Added: Something funny"
    git push
