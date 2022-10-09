# Mnesios

Mnesios ([https://www.mnesios.com/](https://www.Mnesios.com/)) est un logiciel d'auto-apprentissage, qui vous aide à apprendre par cœur ce que vous voulez, comme le vocabulaire d'une langue étrangère, des capitales, des dates importantes, des formules mathématiques, etc.  
Mnesios est basé sur le principe des cartes d'apprentissage : la face avant d'une carte indique une question, et la face arrière contient la réponse. Un apprentissage consiste à regarder la question, formuler pour soi-même une réponse, regarder la réponse, et décider si on avait bon. Et bien sûr Mnesios gère pour vous les intervalles entre les vérifications de connaissances, de façon croissante au fur et à mesure des répétitions.  
Wikipédia a une [page dédiée aux cartes d'apprentissage](https://fr.wikipedia.org/wiki/Carte_m%C3%A9moire_(apprentissage)).

## Démarrage rapide

1. Créez un compte en suivant le lien de la page d'accueil.
1. Ouvrez la page de recherche (menu `Cartes`/`Parcourir`).
1. Choisissez des critères de sélection, par exemple un [label](/tags) ou une [évaluation moyenne](/rating).
1. Lancez la recherche avec le bouton `Exécuter`.
1. Sélectionnez toutes les cartes en cochant la case tout en haut à gauche, au-dessus de la liste (ou sélectionnez juste les cartes qui vous intéressent en cochant leurs cases).
1. Ajoutez les cartes à votre [paquet](/deck) en utilisant le bouton <i class="fa fa-inbox"></i> et `Ajouter à votre paquet`.
1. Revenez à la [page de démarrage](https://www.Mnesios.com/) (en cliquant sur le nom _Mnesios_, en haut).
1. Cliquez sur le lien des cartes non apprises dans la page.
1. Carte par carte, testez vos connaissances. Quand vous connaissez une réponse, la question ne vous sera plus posée avant deux jours (et cet intervalle augmentera dans les révisions suivantes). Quand vous ne connaissez pas la réponse, la carte est remise sous le tas des cartes non apprises.

## Utilisez les cartes existantes

Vous pouvez **sélectionner des choses à apprendre parmi la base de données des cartes disponibles**.
Le menu `Cartes`/`Parcourir` vous amène sur la [page de recherche](https://www.Mnesios.com/Search/Index).  
Le menu à trois points <i class="fa fa-ellipsis-v"></i> sert à plier ou déplier la zone des critères de recherche.  
Par exemple, si voulez apprendre à identifier les régions françaises, spécifiez comme [label](/tags) requis `Régions françaises`{:.mnesiostag}.  
Un autre critère de sélection particulièrement intéressant est l'[évaluation moyenne des utilisateurs](/rating).  
Dans la liste, vous pouvez cocher des cartes (cases à gauche), puis les ajouter à votre [paquet](/deck) en utilisant le bouton en forme de paquet en haut à gauche <i class="fa fa-inbox"></i>.  
Pour en savoir plus sur la recherche de cartes, lisez la [documentation spécifique](/search).

## Créez vos cartes

Il est très facile d'écrire vos propres carte : ça se passe dans la [page dédiée](https://www.mnesios.com/Authoring/Index).  
Vous contrôlez la visibilité des cartes que vous créez (_strictement privées_, _visibles seulement par des utilisateurs choisis_, _publiques_).
Pour en savoir plus sur la création et la modification de cartes, lisez la [documentation spécifique](/Authoring).

## L'apprentissage

Votre sélection de cartes s'appelle un [paquet de cartes](https://www.Mnesios.com/Decks/Index). Dans un paquet, les cartes sont réparties par **tas** selon l'état de vos connaissances.  
Lorsque vous ajoutez une carte dans votre paquet, elle est dans le tas nommé _cartes non apprises_.  
Lorsque vous apprenez une carte, si vous indiquez que vous connaissiez la réponse, la carte est déplacée dans le tas supérieur, et si vous aviez faux, la carte est remise dans le tas des non apprises.  
Chaque tas a sa période d'expiration, dont la formule est deux élevé à la puissance le numéro du tas (2<sup>tas</sup>). Ainsi, une carte qui est dans le tas numéro vous sera soumise à nouveau deux jours après qu'elle y soit arrivée. Dans le tas numéro deux, cet intervalle est de quatre jours, etc. Une carte qui est dans le tas numéro 10 ne vous sera présentée à nouveau qu'au bout de 2 ans et 9 mois !  
**Un aspect majeur est que _vous_ indiquez si vous connaissiez la réponse, à votre guise**. Par exemple, si une fiche de la catégorie `Science physique`{:.mnesiostag} vous demande [la densité de l'or](https://www.Mnesios.com/Authoring?CardId=534b3214-5880-47a0-d8f0-08d7eba1e1a5), c'est vous qui validez ou non votre réponse selon la précision que vous souhaitez avoir. Vous pouvez considérer que "environ 20" est une réponse satisfaisante, ou au contraire exiger de vous-même une précision au dixième.   
Pour en savoir plus sur les paquets, lisez la [documentation spécifique](/deck).

## Gratuit, collaboratif, évolutif

Mnesios est une solution coopérative : les cartes publiques peuvent être modifiées par tous les utilisateurs, dans le but d'amélioration continue.  
Pas de panique : quand quelqu'un modifie une carte, il s'agit d'une nouvelle version et l'historique des versions est conservé, permettant de ne pas perdre d'information. Si un utilisateur malveillant dégrade une carte, on peut restorer la verion précédente.  
Vous pouvez [suivre des cartes](/following), et recevoir des notifications quand elles sont modifiées.  
Le logiciel Mnesios lui-même est ouvert, vous pouvez consulter son code source ou apporter des améliorations sur la [page dédiée du site GitHub](https://github.com/VoltanFr/memcheck).
