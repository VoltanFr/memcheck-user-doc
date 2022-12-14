# L'algorithme de montée dans les tas

Dans la [page d'apprentissage](/learn), lorsque vous indiquez que vous connaissez une réponse en cliquant sur le bouton vert `Je le savais`, la carte monte dans le tas de rang supérieur. Elle vous sera présentée à nouveau en révision après un délai : on dira à ce moment-là que la carte a _expiré_.

Actuellement, un seul algorithme vous est proposé. D'autres sont envisagés pour plus tard (voir [Offer other heaping algorithms](https://github.com/VoltanFr/memcheck/issues/349)&nbsp;<i class="fas fa-external-link-alt"></i>).

## L'algorithme par défaut (quadratique)

Dans cet algorithme, le délai d'expiration dans le tas `t` est `nᵗ` (`n puissance t`).

Exemples

- Si le jour j vous apprenez une carte non apprise avec succès, elle passe dans le tas 1, et vous sera présentée à nouveau 2¹ jours plus tard, c'est à dire le surlendemain (j+2).
- Si le jour j vous apprenez une carte du tas 3 avec succès, elle passe dans le tas 4, et vous sera présentée à nouveau 2⁴ jours plus tard, c'est à dire en j+16.

Un inconvénient de cet formule est que des cartes ajoutées en même temps tendent à être présentées pour répétition en même temps. C'est gênant dans le cas de cartes connexes : si on vous demande la traduction d'un mot en français, puis juste après la traduction inverse, la deuxième question perd une bonne partie de son intérêt.
Pour diminuer ce problème, une petite durée est ajoutée aléatoirement au délai d'expiration. Vous pouvez aussi choisir d'éloigner les cartes manuellement en les changeant de tas (voir [Changer les cartes de tas manuellement](/deck/#changer-les-cartes-de-tas-manuellement)).

<br/>
<br/>
<br/>

---

[Retour à la page d'accueil de la documentation](/)

[Mnesios](https://www.mnesios.com/)&nbsp;🐘
