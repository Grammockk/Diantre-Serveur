# Diantre-Serveur
projet Ynov B2B

Doc Installation cas Client

Dans le cas ou un client voudrais obtenir un serveur de jeu , le client devra se rendre sur le site https://DiantreServeur.fr/location.

Ensuite , ce dernier doit s'enregistrer , entrer ses coordonnées bancaires , puis choisir l'offre qui lui conviens le mieux.

Une fois cela fait , le serveur sera envoyer sur la boite mail du client , avec l'ip et les logs pour accéder au pannel de controle.


---------------------------------------------------------------------------------------------------------------------------------------------------

Doc installation cas Admin

Dans le cas ou un admin voudrait s'ocuper de creer un nouveau serveur il faudra commencer par démarrer une nouvelle VM , qui hébergera le serveur de jeu , il pourra utiliser VirtualBox , l'allocation de mémoire devra être de 8 GO , tandis que l'espace disque devra être d'au moins 10 GO , Si le client demande une offre personnalisée , il faudra augmenter ces valeurs.

une fois la VM lancée , il faudra se diriger sur le site de minecraft offciel : https://minecraft.net et récupérer les executable pour serveur.

dès que les executables seront récupérer , l'admin devra les installer dans un dossier qui hébergera le serveur , il faut bien penser a ouvrir les ports pour permettre une connexion entrante.

dès que le serveur est fonctionnel , il faut lié le dossier au panel de controle du site web , pour permettre au client de changer les sauvegardes ainsi que de pouvoir utiliser l'invité de commande lié au serveur.
