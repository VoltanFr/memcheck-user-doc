---
nav_order: 7
permalink: /media.html
---

# Les images

La base de données Mnesios stocke des images, afin de les utiliser dans les faces des cartes. Chaque image est identifiée par son nom (qui est donc unique).

## Insérer une image dans une carte

Une balise d'image dans le texte d'une carte est de la forme `![Mnesios:<nom de l'image>,size=<small|medium|big>]`.

Voir la page [Créer ou modifier des cartes](authoring.md#images).

## Parcourir la liste des images

Vous pouvez accéder à la page de listing par le menu `Media/Parcourir les images` (qui vous amène sur la page [Liste des images](https://www.mnesios.com/Media/Index)<i class="intextlogo"></i>).

Le filtre de recherche vous permet de cibler pour trouver l'image voulue.

## Ajouter une image dans Mnesios 

L'ajout d'une image dans la base de données de Mnesios se passe dans [la page Ajouter une image](https://www.mnesios.com/Media/Upload)<i class="intextlogo"></i> (accessible par le menu _Médias_).

Conseil : dans le champ `Description`, mettez tous les mots-clés qui pourront faciliter la recherche, mais pas plus. Par exemple, la description de l'image [Appareil digestif simplifié](https://www.mnesios.com/Media/Index/?ImageId=400f50f8-065c-45be-3697-08d94a841337)<i class="intextlogo"></i> contient tous les mots qui figurent sur l'image : si quelqu'un cherche une image pour illustrer une carte sur l'estomac, il la trouvera facilement.

Attention...

- Les images sont forcément [publiques](rules.md#contenu-public).
- Une image ne peut être supprimée que si elle n'est utilisée par aucune carte.
- Une image ne peut pas être renommée simplement, parce que le changement de nom nécessite une intervention sur toutes les cartes utilisant l'image, y compris les cartes privées. Vous pouvez demander aux administrateurs de faire ce changement, mais la demande sera probablement refusée, vu que le nom n'est pas très important).
- La même image ne peut pas être ajoutée deux fois dans la base de données (ceci se base simplement sur une somme de contrôle calculée sur le fichier uploadé).
- Vous devez respecter [les règles](rules.md#droits-dauteur-et-autres-règles). En particulier, vous devez vous assurer que la licence d'utilisation de l'image que vous ajoutez permet son utilisation, et cette information doit être vérifiable avec ce que vous mettez dans le champ _Source_.
