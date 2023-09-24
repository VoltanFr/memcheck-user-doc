---
nav_order: 12
permalink: /account.html
---

# Votre compte utilisateur

## Profil

Vous pouvez configurer votre compte utilisateur par la [page dédiée de Mnesios](https://www.mnesios.com/Identity/Account/Manage)<i class="intextlogo"></i>.

- Votre **adresse électronique** est une information strictement privée, et n'est jamais affichée ou accessible pour quelqu'un d'autre que vous, à part les administrateurs de Mnesios. L'application Mnesios l'utilise pour vous contacter si vous vous êtes [abonné pour recevoir des notifications](following.md).
- Votre **nom d'utilisateur** est une information publique, visible par tous. Choisi au moment de votre inscription, vous ne pouvez pas le changer par la suite (c'est une [amélioration envisagée](https://github.com/VoltanFr/memcheck/issues/381)&nbsp;<i class="fas fa-external-link-alt"></i>). Nous vous recommandons que ce soit un pseudonyme, et qu'il ne contienne pas d'information personnelle telle que votre nom de famille.
- Vous pouvez choisir la **langue d'affichage de Mnesios** en utilisant le bouton du menu : `Fr` signifie langue française, `En` signifie anlais.
- **Abonnement aux notifications lorsque vous créez ou modifiez une carte** : cette option change le comportement de la [page de création de carte](authoring.md) : selon votre choix, vous serez ou non abonné pour [suivre une carte](following.md#suivre-des-cartes) que vous créez.
- L'option **notifications par mail** indique si vous souhaitez que l'application Mnesios vous envoie des courriers électroniques. Les seuls messages qu'envoie automatiquement Mnesios concernent vos abonnements pour [suivre des cartes ou des recherches](following.md) : si vous décochez cette case, vos abonnements seront inopérants puisque vous ne recevrez plus aucun mail automatique. Lorsque cette case est cochée, vous pouvez indiquer à quelle fréquence vous souhaitez recevoir des notifications (permet par exemple de ne pas recevoir de message plus qu'une fois par semaine).

## Vos données

Vous disposez d'un droit d'accès, de modification, de rectification et de suppression des données qui vous concernent. Contactez les administrateurs si vous voulez en savoir plus (adresse électronique en bas de la [page principale](index.md)).

Voir aussi [la page Règles d'utilisation, droit d'auteur](rules.md).

### Mot de passe

Mnesios n'enregistre dans sa base de données qu'une version [hachée](https://fr.wikipedia.org/wiki/Fonction_de_hachage)&nbsp;<i class="fas fa-external-link-alt"></i> de votre mot de passe, c'est-à-dire _non-réversible_. Personne ne pourra jamais le retrouver à partir de cette information.

### Téléchargement

Vous pouvez télécharger toutes vos informations stockées dans la base de données de Mnesios. L'implémentation actuelle est très incomplète et n'inclut que des données très minimalistes et de peu d'intérêt. Une [amélioration est prévue](https://github.com/VoltanFr/memcheck/issues/160) pour que l'intégralité de vos données soit accessible par ce moyen.

### Suppression de compte

Voir la [page dédiée](delete-personal-data.md).

## Abonnements

La [page de gestion des abonnements](https://www.mnesios.com/Identity/Account/Manage/Subscriptions)<i class="intextlogo"></i> vous permet de lister, modifier et supprimer vos [abonnements](following.md). Actuellement il ne s'agit que des _recherches_ suivies.
