---
nav_order: 3
permalink: /authoring.html
---

# Créer ou modifier des cartes

La création de cartes ou la modification d'une carte existante se font dans la [page dédiée de Mnesios](https://www.mnesios.com/Authoring/)<i class="intextlogo"></i>.

## Les faces

Une carte Mnesios a quatre faces...

- `Avant` (obligatoire) : c'est la question, la face qui est montrée pour qu'on demande à l'utilisateur _Le saviez-vous ?_
- `Arrière` (obligatoire) : c'est la réponse, la première face qui est montrée quand l'utilisateur a répondu.
- `Infos supplémentaires` (optionnelle) : des informations libres, généralement pour permettre de mieux comprendre la carte au-delà de la question et de la réponse.
- `Références` (optionnelle) : cette face sert à indiquer des sources qui permettent de vérifier les informations, ou d'en savoir plus.

### Format du texte

Vous pouvez utiliser le format [MarkDown](https://fr.wikipedia.org/wiki/Markdown)&nbsp;<i class="fas fa-external-link-alt"></i> dans le texte. Par exemple, encadrez des mots avec deux étoiles pour les mettre en gras, ou avec le caractère souligné pour les mettre en italique. MarkDown est un format standard très répandu, dont vous trouverez par exemple une documentation simple [ici](https://github.com/luong-komorebi/Markdown-Tutorial/blob/master/README_fr.md)&nbsp;<i class="fas fa-external-link-alt"></i>.

La barre de boutons en haut de la face offre différents services pratiques pour modifier votre texte, et le bouton <i class="fab fa-markdown"></i> vous permet de visualiser la version finalisée de votre texte.

Au moment de l'enregistrement, Mnesios supprime les caractères invisibles (espaces, lignes vides) au début et à la fin des textes des faces.

### Images

Les faces des cartes peuvent contenir des images en plus du texte.

#### Les images de la base de données Mnesios

La base de données de Mnesios contient une [liste d'images](media.md). Vous pouvez insérer une de ces images dans votre texte en utilisant une balise sur le modèle `![Mnesios:Afrique australe,size=small]`.

Dans la [liste des images](media.md), vous trouverez sur chaque image un bouton <i class="far fa-copy"></i> qui vous permet de copier dans votre presse-papier le lien vers l'image dans ce format, afin de le coller dans une face de carte.

Avantages d'une image stockée dans le site Mnesios :

- facilité d'utilisation ;
- sa disponibilité est garantie, vous ne risquez pas une suppression ou un changement d'adresse ;
- Mnesios les télécharge en arrière plan dans la [page d'apprentissage](learn.md).

#### Les images provenant d'autres sites

Les images peuvent aussi ne pas être dans la base de données de Mnesios, mais venir d'internet. Le format est alors `![Légende](URL)`. Par exemple : `![Gorgonopsiens](https://upload.wikimedia.org/wikipedia/commons/2/2a/Inostrancevia_alexandri_-_MUSE.jpg)`.

## La langue

Vous pouvez ici indiquer dans quelle langue votre carte est rédigée, ce qui permettra aux utilisateurs de sélectionner des cartes dans la langue de leur choix.

Pour l'instant toutes les cartes sont en français, et la [recherche](search.md) avec choix de langue n'est pas encore implémentée.

## Les labels

C'est ici que vous pouvez catégoriser les cartes en leur attachant un ou des [labels](tags.md). C'est un critère majeur de recherche. En cas de doute sur l'utilisation d'un label, vous pouvez aller voir sa description dans la [liste des labels](https://www.mnesios.com/Tags/)<i class="intextlogo"></i>.

Vous pouvez en particulier labelliser les cartes strictement privées avec [le label Perso](tags.md#le-label-perso).

## Visibilité des cartes

La section _Utilisateurs_ de la page vous permet de choisir la liste des utilisateurs qui ont accès aux cartes...

- Par défaut lors de la création d'une carte, vous seul pouvez la voir : elle est alors dite `strictement privée`. Les autres utilisateurs ne peuvent même pas savoir qu'elle existe. Vous pouvez donc l'utiliser comme vous voulez, vous n'avez pas besoin de respecter un certain style, etc. Nous vous recommandons pour l'instant de ne pas mettre dans Mnesios d'informations confidentielles sensibles, même dans des cartes strictement privées (en attendant que l'application ait été validée par un audit de sécurité tiers).
- En cliquant sur les étiquettes de noms d'utilitateurs vous les supprimez. Si vous les supprimez tous, la carte devient `publique`, c'est-à-dire accessible à tout utilisateur de Mnesios (même sans compte). Les autres utilisateurs peuvent alors l'ajouter dans leur paquet, ou la modifier (cf ci-dessous, [Modification](#modification)).
- Vous pouvez sélectionner des utilisateurs et rendre la carte visible seulement par ces utilisateurs choisis ; on appelle cela `visibilité limitée`.

⚠ Attention : lorsqu'une carte n'est pas strictement privée, si quelqu'un d'autre l'ajoute dans son paquet ou en crée une nouvelle version, vous ne pourrez plus la rendre privée (ce qui créerait une incohérence dans le paquet de l'autre utilisateur).

## Le choix d'ajout au paquet

La case à cocher _Ajouter à votre paquet_ a pour effet, comme son nom l'indique, de mettre la carte dans votre [paquet](deck.md), dans le tas des cartes non apprises.

## Modification

Vous pouvez ouvrir une carte Mnesios pour modification depuis deux endroits : la [page d'apprentissage](learn.md) et la [page de recherche](search.md). Cette même page de création de carte est alors ouverte mais en mode édition ([exemple](https://www.mnesios.com/Authoring?CardId=a862f9b0-4ed9-4be0-d267-08d7ebb03fda)<i class="intextlogo"></i>), et trois fonctionnalités supplémentaires vous y sont offertes...

- **Le bouton 🛈** vous donne accès à des informations générales sur la carte.
- **Le bouton <i class="fas fa-history"></i>** permet d'ouvrir l'historique de la carte, et de voir des informations sur les versions. En effet, dans Mnesios toutes les opérations sur les cartes sont historisées, ce qui permet de tracer les évolutions et si nécessaire de revenir en arrière.
- **Le bouton d'évaluation** vous montre votre [évaluation](rating.md) de la carte, vous permet de la modifier, et indique aussi l'évaluation moyenne par les utilisateurs.

Les versions précédentes des cartes modifiées sont conservées, et tout [l'historique des versions](card-history.md) peut être consulté.

## Conseils pour une bonne carte publique

Une bonne carte publique intéressera d'autres utilisateurs qui la mettront dans leur paquet, et la feront éventuellement évoluer (dans l'esprit de service collaboratif et d'amélioration continue). Elle aura une bonne [évaluation moyenne](rating.md), ce qui lui apportera de la popularité. Il s'agit ici des cartes publiques : les cartes privées sont plus une affaire de choix personnel.

Quelques conseils...

- Ne dupliquez pas d'autre carte : vérifiez par une [recherche](search.md) s'il n'en existe pas déjà une pour apprendre votre sujet.
- La question doit être précise, et généralement fermée, c'est à dire bien guider l'utilisateur vers une réponse sans ambiguïté. Par exemple...
  - Plutôt que `Où la Seine prend-elle sa source ?`, préférez `Dans quel département la Seine prend-elle sa source ?`.
  - Même si votre carte a le label `Vocabulaire anglais`{:.mnesiostag}, rédigez la question : plutôt que `Rouge ?`, préférez `Anglais pour Rouge ?`.
- La réponse devrait être précisément ce qu'on attend par rapport à la question, et pas plus. En revanche c'est une bonne idée de donner des informations supplémentaires dans la face dédiée. Par exemple...
  - À la question [En quelle année Napoléon Bonaparte fut-il couronné empereur ?](https://www.mnesios.com/Authoring?CardId=437bb2d9-37ba-43b2-dc93-08d7eba1e1a5)<i class="intextlogo"></i>, la réponse devrait être simplement `1804` (ne pas donner une date précise si elle n'est pas demandée).
- Écrivez correctement (pas de fautes d'orthographe, pas d'utilisation abusive de majuscules, paragraphes bien dimensionnés), sans tomber dans l'excès d'un style trop soutenu.
- Utilisez à bon escient le [formatage Markdown](#format-du-texte).
- [Ne plagiez pas !](rules.md) Par exemple, beaucoup de cartes ont des informations supplémentaires inspirées de Wikipédia : il s'agit alors de savoir simplifier, raccourcir.
- Restez concis : MemCheck n'a pas vocation à devenir une encyclopédie.
- Donnez des références crédibles, vérifiables.
- Ajoutez des labels bien choisis.

Critères de qualité...

- Face avant : la question doit être claire et précise, sans ambiguïté. Exemple : 
- Face arrière : elle apporte une réponse précise à la question de la face avant. C'est l'information que l'utilisateur devrait connaître pour pouvoir considérer qu'il a la bonne réponse. La face arrière ne dervait pas donner plus d'information que cette réponse : on utilise la face des Informations supplémentaires pour ça.
- Face des informations supplémentaires : elle doit être équilibrée entre donner de bonnes informations, utiles, sans aller trop loin.
- La face des références : il s'agit de donner des sources, des preuves, des informations de la carte. Il s'agit presque toujours de liens vers des pages internet, Wikipédia par exemple. Bien sûr il est souhaitable que les références elles-mêmes soient des sources de qualité.

Images
Si une image apporte une information directe sur la réponse, elle devrait être attachée à la face arrière de la carte. Si l'image apporte une information complémentaire, elle devrait plutôt être attachée à la face Informations supplémentaires.

Par exemple, prenons [la carte qui a pour question `Qu'ont de particulier les diagonales d'un parallélogramme ?`](https://www.mnesios.com/Authoring?CardId=9759c1db-c3d1-4468-e341-08d7eba1e1a5)<i class="intextlogo"></i> et pour réponse `Elles se coupent en leurs milieux`. Si l'image prouve cette propriété avec des codages qui rendent la figure parlante, elle devrait être attachée à la face arrière.

Mon habitude est de commencer par créer une carte en privé, puis la rendre publique après quelques jours de recul qui me permettent de la faire évoluer.

Voir aussi les conseils sur [les évaluations](rating.md).

## Suivi de la carte

Il y a dans les [réglages de votre compte utilisateur](account.md) une option intitulée `Abonnement aux notifications lorsque vous créez ou modifiez une carte` : lors de la création d'une nouvelle carte, selon cette option, vous serez éventuellement automatiquement abonné aux notifications sur modification de la carte.

Voir la page [Suivre des cartes ou des recherches](following.md#suivre-des-cartes) pour plus d'informations.

## Droit d'auteur, règles

En publiant une contribution dans Mnesios, vous acceptez de la placer irrévocablement sous [licence Creative Commons Attribution 4.0 International - CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.fr)&nbsp;<i class="fas fa-external-link-alt"></i>. Vous acceptez que votre [nom d'utilisateur](account.md) soit associé à cette contribution. Voir [la page dédiée](rules.md).
