# La page de parcours des cartes

La [page de parcours des cartes](https://www.mnesios.com/Search/Index)&nbsp;🐘, aussi appelée _Page de recherche de cartes_, vous permet de parcourir la base de données des cartes. C'est une page majeure, puisque c'est ici que vous pourrez trouver les cartes qui vous intéressent, que ce soit parmi les cartes publiques ou parmi vos cartes privées.

Pour l'utiliser :

- accédez aux filtres (ou cachez-les) grâce au bouton **&#x22EE;** en haut ;
- faites votre choix de filtrage (cf ci-dessous, [Filtrage : critères de recherche](#filtrage--critres-de-recherche)) ;
- lancez la recherche avec le bouton _Exécuter_ ;
- explorez la liste obtenue et exploitez-la (cf ci-dessous, [Les actions disponibles sur la liste obtenue](#les-actions-disponibles-sur-la-liste-obtenue)).

## Filtrage : critères de recherche

Les critères de recherche vous permettent de définir comment vous souhaitez sélectionner des cartes. Cette section de la page peut s'afficher ou s'escamoter avec le bouton **&#x22EE;** en haut à gauche.

- [Paquet](/deck) : vous pouvez choisir de ne chercher que parmi les cartes qui sont ou ne sont pas dans votre paquet.
  - _Exclure les cartes_ qui sont déjà dans votre paquet est principalement utile lorsque vous en cherchez des nouvelles à y ajouter.
  - _Inclure les cartes_ de votre paquet signifie que la recherche ne portera que sur les cartes qui y sont. Utile par exemple pour changer une carte de tas, pour en supprimer, ou ajouter des labels.  
    Avec ce filtre, vous pouvez aussi préciser dans quel tas vous souhaitez chercher, ou les dates d'ajout ou d'expiration.  
    _La sélection de la date se fait avec un contrôle pas très pratique, dont le remplacement est prévu : pour changer une valeur (année, mois ou jour), cliquez au-dessus ou en-dessous_.
- [Labels](/tags) : vous permet de rechercher les cartes qui ont ou qui n'ont pas un ou des label(s).  
  Par exemple, si voulez apprendre à identifier les régions françaises, spécifiez comme [label](/tags) requis `Régions françaises`{:.mnesiostag}.  
  Ou bien si vous vous intéressez à la navigation maritime mais pas à celle en eaux intérieures, vous pouvez indiquer comme _label requis_ `Marine`{:.mnesiostag} et comme _label exclus_ `Permis bateau fluvial`{:.mnesiostag} et `Vocabulaire fluvial`{:.mnesiostag}.  
  Le label requis est le critère le plus utilisé, typiquement pour trouver des cartes à apprendre sur le thème qui vous intéresse. Il faut bien comprendre que [les labels ne sont que des indicateurs](/tags#des-indicateurs).
- [Propriétaire](/account) indique que l'utilisateur sélectionné doit être auteur d'au moins une version de la carte. Ce critère vous permet par exemple de trouver les cartes auxquelles vous avez participé, ou un utilisateur que vous appréciez.
- [Visibilité](/authoring#visibilit-des-cartes) sert à filtrer selon l'accessibilité des cartes.
  - _Au-delà du propriétaire_ sélectionne les cartes publiques, c'est-à-dire vos cartes auxquelles d'autres utilisateurs peuvent accéder, ou les cartes d'autres utilisateurs que vous avez le droit de voir.
  - _Privées_ sélectionne les cartes qui ne sont visibles que par leur auteur. Autrement dit, ce sont vos cartes privées.
- [Texte](/authoring#les-faces) sert à sélectionner les cartes qui contiennent les caractères indiqués. Ce critère ne tient pas compte de la casse (majuscules ou minuscules) ou des espaces au début ou à la fin.  
  Par exemple, si vous cherchez les cartes à propos du _Ph_ (Potentiel hydrogène), vous pouvez faire une recherche avec le label `Chimie`{:.mnesiostag} et le texte _ph_.
- [Références](/authoring#références)
  - _Aucune_ séléctionne des cartes dont la face _Références_ est vide, par exemple pour les améliorer en renseignement cette face.
  - _Non vide_ sélectionne les cartes qui ont des informations à propos de la source, ce qui est un indicateur de qualité.
- [Évaluation moyenne](/rating) sert à filtrer les cartes selon la moyenne des évaluations que leur ont donné les utilisateurs. Pratique pour trouver des cartes de qualité, ou des cartes à améliorer.
- [Notifications](/following) permet de lister les cartes que vous suivez ou ne suivez pas.
- _Taille de la page_ n'est pas un critère de recherche, mais vous permet de choisir combien de cartes sont affichées dans la liste de résultats de la recherche (vous pourrez naviguer entre les pages de cette liste grâce aux boutons numérotés, en haut).

À propos du bouton `Abonnement`, voir [ci-dessous](/search#le-bouton-abonnement-de-la-zone-de-filtrage).

## Les actions disponibles sur la liste obtenue

Le résultat de la recherche s'affiche sous forme de liste, dans laquelle vous pouvez cocher (_sélectionner_) des cartes. Quand vous avez sélectionné des cartes, les opérations suivantes deviennent possibles...

### Actions relatives au paquet, par le bouton <i class="fas fa-inbox"></i>

- **Ajouter dans votre [paquet](/deck)** si les cartes choisies n'y sont pas encore, en utilisant le menu _Ajouter à votre paquet_.
- **Enlever de votre paquet** si les cartes choisies y sont, en utilisant le menu _Enlever votre paquet_. Cette opération ne supprime pas la carte de Mnesios, mais seulement de votre paquet.
- **Changer les cartes de tas** (voir [Changer les cartes de tas manuellement](/deck/changer-les-cartes-de-tas-manuellement)).

### Actions sur les cartes, par le bouton <i class="fas fa-ellipsis-h"></i>

- **Vous abonner aux notifications** ou vous **désabonner** pour les cartes sélectionnées, afin d'être prévenu par mail lors de modifications des cartes. Voir la [page dédiée](/followingcards) pour plus d'informations.
- **Supprimer les cartes** de Mnesios : à ne pas confondre avec l'opération qui consiste à l'enlever d'un paquet. Il s'agit ici de supprimer complètement une carte de Mnesios, elle ne sera plus accessible par aucun utilisateur. Cette suppression n'est possible que si :
  - personne d'autre que vous n'a la carte dans un paquet ;
  - personne d'autre que vous n'est auteur d'une version de la carte.
- **Ouvrir dans des onglets** sert à afficher la page d'édition de chaque carte sélectionnée dans un nouvel onglet de votre navigateur, ce qui est pratique quand vous voulez modifier plusieurs cartes. Cette fonctionnalité nécessite que vous autorisiez les _fenêtres popup_ pour le site Mnesios dans votre navigateur.

### Ajout de label, par le bouton <i class="fas fa-tags"></i>

Cette fonctionnalité vous permet d'ajouter un label sur toutes les cartes sélectionnées (les cartes qui ont déjà le label sont ignorées).

### Navigation entre les pages de résultats

Une recherche renvoie parfois plus de cartes que la page n'en affiche. Des boutons de pagination sont alors affichés en haut de la page, vous permettant de naviguer dans les pages de résultats.

## Le bouton abonnement de la zone de filtrage

Dans la zone de filtrage, il y a un bouton intitulé `Abonnement` : il vous permet d'enregistrer cette recherche dans Mnesios pour être prévenu par mail lorsque les résultats changent. Cette fonctionnalité est très pratique quand vous vous intéressez à un sujet et souhaitez être au courant des modifications, par exemple quand quelqu'un ajoute une carte avec le label en question.

Vous configurez l'envoi de mails par Mnesios dans la [page de gestion de votre compte](/account).

À ne pas confondre avec [l'abonnement à des cartes](/followingcards), qui vous permet de suivre les modifications de ces cartes.

<br/>
<br/>
<br/>

---

[Retour à la page d'accueil de la documentation](/)

[Mnesios](https://www.mnesios.com/)&nbsp;🐘
