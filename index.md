---
title: Page principale
nav_order: 1
---

# Mnesios

Mnesios ([https://www.mnesios.com/](https://www.Mnesios.com/)<i class="intextlogo"></i>) est un logiciel gratuit d'auto-apprentissage, qui vous aide à apprendre par cœur ce que vous voulez, comme le vocabulaire d'une langue étrangère, des capitales, des dates historiques, des formules mathématiques, etc.

Mnesios est basé sur le principe des cartes d'apprentissage : la face avant d'une carte indique une question, et la face arrière contient la réponse. Un apprentissage consiste à regarder la question, formuler pour soi-même une réponse, regarder la réponse, et décider si on avait bon. Et bien sûr Mnesios [gère pour vous](heaping.md) les intervalles entre les vérifications de connaissances, de façon croissante au fur et à mesure des répétitions.

Wikipédia a une [page dédiée aux cartes d'apprentissage](https://fr.wikipedia.org/wiki/Carte_m%C3%A9moire_(apprentissage))&nbsp;<i class="fas fa-external-link-alt"></i>.

## Nouvel utilisateur : démarrage rapide

1. Créez un [compte utilisateur](account.md) en suivant le lien de la page d'accueil ou en cliquant [ici](https://www.mnesios.com/Identity/Account/Register)<i class="intextlogo"></i>.
1. Ouvrez la [page de recherche de cartes](search.md) (menu `Cartes`/`Parcourir`).
1. Choisissez des critères de sélection, par exemple un [label](tags.md) ou une [évaluation moyenne](rating.md).
1. Lancez la recherche avec le bouton `Exécuter`.
1. Sélectionnez les cartes qui vous intéressent en cochant leurs cases.
1. Ajoutez ces cartes à votre [paquet](deck.md) en utilisant le bouton <i class="fas fa-inbox"></i> et `Ajouter à votre paquet`.
1. Revenez à la [page de démarrage](https://www.Mnesios.com/)<i class="intextlogo"></i> (en cliquant sur le nom _Mnesios_, en haut).
1. Dans la page de démarrage, cliquez sur le lien des cartes non apprises : vous arrivez dans [l'apprentissage](learn.md).
1. Carte par carte, testez vos connaissances. Quand vous connaissez une réponse, la question ne vous sera plus posée avant deux jours (et cet intervalle augmentera dans les révisions suivantes). Quand vous ne connaissez pas la réponse, la carte est remise sous le tas des cartes non apprises.

## Utilisez les cartes existantes

Vous pouvez **sélectionner des choses à apprendre parmi la base de données des cartes disponibles**. Le menu `Cartes`/`Parcourir` vous amène sur la [page de recherche](search.md). De là, vous pouvez en particulier ajouter des cartes à votre paquet.

Pour en savoir plus sur la recherche de cartes, lisez la [documentation spécifique](search.md).

## Créez vos cartes

Il est très facile d'écrire vos propres carte : ça se passe dans la [page dédiée](authoring.md). Vous contrôlez la [visibilité](authoring.md#visibilité-des-cartes) des cartes que vous créez : _strictement privées_, _visibles seulement par des utilisateurs choisis_, _publiques_.

## L'apprentissage

Votre sélection de cartes s'appelle un [paquet de cartes](deck.md). Dans un paquet, les cartes sont réparties par **tas** selon l'état de vos connaissances.
Lorsque vous ajoutez une carte dans votre paquet, elle est dans le tas nommé _cartes non apprises_.

Lorsque vous [apprenez](learn.md) une carte, si vous indiquez que vous connaissiez la réponse, la carte est déplacée dans le tas supérieur, et si vous aviez faux, la carte est remise dans le tas des non apprises.

[Chaque tas a sa période d'expiration](heaping.md), dont la formule est deux élevé à la puissance le numéro du tas (2<sup>tas</sup>). Ainsi, une carte qui est dans le tas numéro un vous sera soumise à nouveau deux jours après qu'elle y soit arrivée. Dans le tas numéro deux, cet intervalle est de quatre jours, etc. Une carte qui est dans le tas numéro 10 ne vous sera présentée à nouveau qu'au bout de 2 ans et 9 mois !

Un aspect majeur de l'auto-apprentissage est que **vous** indiquez si vous connaissiez la réponse, à votre guise. Par exemple, si une fiche de la catégorie `Science physique`{:.mnesiostag} vous demande [la densité de l'or](https://www.Mnesios.com/Authoring?CardId=534b3214-5880-47a0-d8f0-08d7eba1e1a5)<i class="intextlogo"></i>, c'est vous qui validez ou non votre réponse selon la précision que vous souhaitez avoir : vous pouvez considérer que "environ 20" est une réponse satisfaisante, ou au contraire exiger de vous-même une précision au dixième.

## Documentation

Le bouton `❓`, dans le menu de Mnesios, est un lien vers de la documentation relative au contexte de la page en cours.

## Gratuit, collaboratif, évolutif

Mnesios est une solution coopérative : les cartes publiques peuvent être modifiées par tous les utilisateurs, dans le but d'amélioration continue ([elles sont en licence Creative Commons](rules.md)).

Pas de panique : quand quelqu'un modifie une carte, il s'agit d'une nouvelle version et l'historique est conservé, permettant de ne pas perdre d'information. Si un utilisateur malveillant dégrade une carte, on peut restorer la verion précédente.

Vous pouvez [suivre des cartes](following.md), et recevoir des notifications quand elles sont modifiées (et même suivre une recherche).

Le logiciel Mnesios lui-même est ouvert, vous pouvez consulter son code source, suggérer des changements ou apporter des améliorations dans [le repository MemCheck sur GitHub](https://github.com/VoltanFr/memcheck)&nbsp;<i class="fas fa-external-link-alt"></i>.

## Règles, contact

[Règles d'utilisation, droit d'auteur, licence](rules.md).

Vous pouvez contacter les administrateurs de l'application à l'adresse `Mnesios.Adm@gmail.com`.
