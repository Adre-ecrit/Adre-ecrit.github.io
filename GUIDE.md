# Guide du site d'Adré

Ce guide explique les mots techniques et les gestes à connaître. Il sera complété au fur et à mesure.

## Les mots à connaître

HTML : le langage qui décrit le contenu d'une page (titres, paragraphes, images, liens). Chaque page du site est un fichier `.html`.

CSS : le langage qui décrit l'apparence (couleurs, police, marges). Tout est dans le fichier `style.css`.

Site statique : un site fait de fichiers fixes, sans base de données. Il est gratuit à héberger, rapide et très peu exposé au piratage.

Hébergement : le service qui garde les fichiers du site sur un ordinateur toujours allumé, pour que les visiteurs puissent le consulter.

Dépôt Git : un dossier dont l'historique des modifications est conservé. On peut toujours revenir à une version précédente.

Commit : l'enregistrement d'une modification dans le dépôt, avec un petit message qui dit ce qui a changé.

Déploiement : l'envoi de la dernière version vers l'hébergeur. Il est automatique après chaque commit.

Nom de domaine : l'adresse que les gens tapent (par exemple `adre.fr`). C'est la seule dépense, environ dix à quinze euros par an.

DNS : l'annuaire qui indique à quel serveur correspond un nom de domaine. On y renseigne quelques lignes pour relier le nom de domaine à l'hébergeur.

## Ajouter une rencontre (une fois le site en ligne)

1. Ouvrir le dépôt du site sur github.com et se connecter.
2. Ouvrir le dossier `images`. Cliquer sur « Add file », puis sur « Upload files ». Déposer la photo, puis cliquer sur « Commit changes ».
3. Revenir à la racine du dépôt, cliquer sur `rencontres.html`, puis sur l'icône en forme de crayon (« Edit this file »).
4. Copier un bloc de rencontre en entier. Il commence par `<div class="entree">` et finit par `</div>`. Coller ce bloc sous le commentaire « AJOUTER UNE RENCONTRE ». Changer la date, le titre et le texte. Changer aussi le nom de la photo.
5. Cliquer sur « Commit changes ». Le site se met à jour en une à deux minutes.

Une erreur n'est jamais grave : l'onglet « History » du fichier permet de revenir à la version précédente.

## Modifier un texte

Même procédure : ouvrir le fichier de la page, cliquer sur le crayon, changer le texte entre les balises, puis « Commit changes ». Ne change pas ce qui est entre les signes `<` et `>`, sauf si tu sais ce que tu fais.
