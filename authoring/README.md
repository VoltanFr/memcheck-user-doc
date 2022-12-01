# Créer ou modifier des cartes

La création de nouvelles cartes ou la modification d'une carte existante se font dans la [page dédiée de Mnesios](https://www.mnesios.com/Authoring/).

## Les faces

Une carte Mnesios a quatre faces...

- `Avant` (obligatoire) : c'est la question, la face qui est montrée pour qu'on demande à l'utilisateur _Le saviez-vous ?_
- `Arrière` (obligatoire) : c'est la réponse, la première face qui est montrée quand l'utilisateur a répondu à la question _Le saviez-vous ?_
- `Infos supplémentaires` (optionnelle) : des informations libres, généralement pour permettre de mieux comprendre la carte au-delà de la question et de la réponse.
- `Références` (optionnelle) : cette face sert à indiquer des sources qui permettent de vérifier les informations de la carte, ou d'en savoir plus.

### Format du texte

Vous pouvez utiliser le format [MarkDown](https://fr.wikipedia.org/wiki/Markdown) dans le texte des cartes. Par exemple, encadrez des mots avec deux étoiles pour les mettre en gras, ou avec le caractère souligné pour les mettre en italique. MarkDown est un format standard très répandu, dont vous trouverez par exemple une documentation [ici](https://github.com/luong-komorebi/Markdown-Tutorial/blob/master/README_fr.md).

La barre de boutons en haut de la face offre différent services pratiques pour modifier votre texte, et le bouton <i class="fab fa-markdown"></i> vous permet de visualiser la version finalisée de votre texte.

Au moment de l'enregistrement, Mnesios supprime les caractères invisibles (espaces, lignes vides) au début et à la fin des textes des faces.

### Images

Les faces des cartes peuvent aussi contenir des images en plus du texte.

#### Les images de la base de données Mnesios

La base de données de Mnesios contient une [liste d'images](/media). Vous pouvez insérer une de ces images dans votre texte en utilisant une balise sur le modèle `![Mnesios:Afrique australe,size=small]`.

Dans la [liste des images](/media), vous trouverez sur chaque image un bouton qui vous permet de copier dans votre presse-papier le lien vers l'image dans ce format, afin de le coller dans une face de carte.

Avantages d'une image stockée dans le site Mnesios :

- sa disponibilité est garantie, vous ne risquez pas une suppression ou un changement d'adresse ;
- Mnesios les télécharge en arrière plan dans la [page d'apprentissage](/learn).

#### Les images provenant d'autres sites

Les images peuvent aussi ne pas être dans la base de données de Mnesios, mais venir d'internet. Le format est alors `![Légende](URL)`. Par exemple : `![Gorgonopsiens](https://upload.wikimedia.org/wikipedia/commons/2/2a/Inostrancevia_alexandri_-_MUSE.jpg)`.

## La section _Langue_

Vous pouvez ici indiquer dans quelle langue votre carte est rédigée, ce qui permettra aux utilisateurs de sélectionner des cartes dans la langue de leur choix.

Pour l'instant toutes les cartes sont en français, et la [recherche](/search) avec choix de langue n'est pas encore implémentée.

## La section _Labels_

C'est ici que vous pouvez catégoriser les cartes en leur attachant un ou des [labels](/tags). C'est un critère majeur de recherche. En cas de doute sur l'utilisation d'un label, vous pouvez aller voir sa description dans la [liste des labels](https://www.mnesios.com/Tags/).

Vous pouvez en particulier labelliser les cartes privées avec [le label Perso](/tags/#le-label-perso).

## La section _Utilisateurs_ : visibilité des cartes

Vous choisissez la liste des utilisateurs qui ont accès aux cartes...

- Par défaut lors de la création d'une carte, vous seul pouvez la voir : elle est alors dite _strictement privée_. Les autres utilisateurs ne peuvent même pas savoir qu'elle existe. Vous pouvez donc l'utiliser comme vous voulez, vous n'avez pas besoin de respecter un certain style, etc. Nous vous recommandons pour l'instant de ne pas mettre dans Mnesios d'informations confidentielles sensibles, même dans des cartes strictement privées (en attendant que l'application ait été validée par un audit de sécurité tiers).
- En cliquant sur les étiquettes de noms d'utilitateurs vous les supprimez. Si vous les supprimez tous, la carte devient _publique_, c'est-à-dire accessible à tout utilisateur de Mnesios (même sans compte). Les autres utilisateurs peuvent alors l'ajouter dans leur paquet, ou la modifier (cf ci-dessous, [Modification](#modification)).
- Vous pouvez sélectionner des utilisateurs et rendre la carte visible seulement par ces utilisateurs choisis ; on appelle cela _visibilité limitée_.

⚠ Attention : lorsqu'une carte n'est pas strictement privée, si quelqu'un d'autre ajoute dans son paquet ou en crée une nouvelle version, vous ne pourrez plus la rendre privée (ce qui créerait une incohérence dans le paquet de l'autre utilisateur).

## Le choix d'ajout au paquet

La case à cocher _Ajouter à votre paquet_ a pour effet, comme son nom l'indique, de mettre la carte dans votre [paquet](/deck) (dans le tas des cartes non apprises).

## Modification

Vous pouvez ouvrir une carte Mnesios pour modification depuis deux endroits : la [page d'apprentissage](/learn) et la [page de recherche](/search). Cette même page de création de carte est alors ouverte mais en mode édition ([exemple](https://www.mnesios.com/Authoring?CardId=a862f9b0-4ed9-4be0-d267-08d7ebb03fda)), et trois fonctionnalités supplémentaires vous y sont offertes...

- **Le bouton 🛈** vous donne accès à des informations générales sur la carte.
- **Le bouton <i class="fas fa-history"></i>** permet d'ouvrir l'historique de la carte, et de voir des informations sur les versions. En effet, dans Mnesios toutes les opérations sur les cartes sont historisées, ce qui permet de tracer les évolutions et si nécessaire de revenir en arrière.
- **Le bouton d'évaluation** vous montre votre [évaluation](/rating) de la carte, vous permet de la modifier, et indique aussi l'évaluation moyenne par les utilisateurs.

## Conseils pour une bonne carte publique

Une bonne carte publique intéressera d'autres utilisateurs qui la mettront dans leur paquet, et la feront éventuellement évoluer. Elle aura une bonne évaluation, ce qui lui apportera de la popularité parmi les utilisateurs de Mnesios. Voir les conseils sur la [page de documentation des évaluations](/rating).

Il s'agit ici avant tout des cartes publiques : les cartes privées sont plus une affaire de choix personnel.

Mnesios est un service collaboratif, dans lequel tous les utilisateurs peuvent contribuer aux cartes, les améliorant plus ou moins rapidement selon le sujet.

Mon habitude est de commencer par créer une carte en privé, puis la rendre publique après quelques jours de recul qui me permettent de la faire évoluer.

## Suivi de la carte

Il y a dans les [réglages de votre compte utilisateur](/account) une option intitulée `Abonnement aux notifications lorsque vous créez ou modifiez une carte` : lors de la création d'une nouvelle carte, selon cette option, vous serez éventuellement automatiquement abonné aux notifications sur modification de la carte.

Voir la page [Suivre des cartes ou des recherches](/following#suivre-des-cartes) pour plus d'informations.

## Droit d'auteur, règles

Voir [la page dédiée](/rules).

<br/>
<br/>
<br/>

---

[Retour à la page d'accueil de la documentation](/)

[Mnesios](https://www.mnesios.com/)
