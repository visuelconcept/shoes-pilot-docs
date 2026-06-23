# Déclarer un rebut

<span class="role-badge">Opérateur</span>

Pendant un pointage, l'opérateur peut déclarer une ou plusieurs pièces non
conformes. Le système distingue **trois types** de rebut et déclenche
automatiquement la récupération de la chaussure valide quand c'est possible.

## Les trois types de rebut

| Type | Code | Signification |
|------|:----:|---------------|
| **Paire complète** | P | Les deux chaussures (gauche + droite) sont défectueuses — aucune récupération |
| **Gauche** | G | Seule la chaussure gauche est défectueuse → la **droite** part au stock de réintégration |
| **Droite** | D | Seule la chaussure droite est défectueuse → la **gauche** part au stock de réintégration |

## Déclarer le rebut

1. Pendant le pointage, dans la section **Rebuts**, cliquez sur **Ajouter**.

    <figure class="screenshot terminal" markdown>
    ![Section Rebuts](../assets/screenshots/fr/rebut-section.png)
    <figcaption>Section Rebuts pendant le pointage</figcaption>
    </figure>

2. Sélectionnez le **type** : G, D ou P.

    <figure class="screenshot terminal" markdown>
    ![Choix du type de rebut](../assets/screenshots/fr/rebut-type.png)
    <figcaption>Choix du type de rebut (gauche, droite, paire)</figcaption>
    </figure>

3. Ajustez la **quantité** avec les boutons +/− et sélectionnez le **motif**.

    <figure class="screenshot terminal" markdown>
    ![Quantité et motif](../assets/screenshots/fr/rebut-motif.png)
    <figcaption>Quantité et motif de non-conformité</figcaption>
    </figure>

4. Cliquez sur **Ajouter le rebut**.

    <figure class="screenshot terminal" markdown>
    ![Rebut ajouté](../assets/screenshots/fr/rebut-ajoute.png)
    <figcaption>Compteurs mis à jour après ajout du rebut</figcaption>
    </figure>

## Récupération automatique

Lorsqu'un rebut **Gauche** ou **Droite** est déclaré :

- la chaussure défectueuse est comptabilisée comme rebut ;
- **la chaussure opposée (valide) est automatiquement ajoutée au stock de
  réintégration** ;
- elle pourra servir plus tard à reconstituer une paire (même OF / même taille).

!!! example "Exemple"
    Vous déclarez **1 rebut Gauche** (motif : défaut cuir) sur un lot de
    10 paires. La chaussure **droite** correspondante rejoint le stock de
    réintégration. Sur un autre lot, un rebut Droite pourra être compensé en
    réintégrant cette droite — et reconstituer ainsi une paire complète.

## Calcul des quantités

Le système garantit que la **quantité sortante est toujours en paires
complètes** :

```text
Entrée : 10 paires
- Rebuts paires   : -2
- Rebuts gauches  : -1  (→ 1 droite au stock)
- Rebuts droites  : -1  (→ compensé par réintégration)
+ Réintégrations  : +1 droite
= Sortie : 7 paires
→ Stock réintégration : +1 droite restante
```

> La réintégration des chaussures orphelines fait l'objet d'un parcours dédié,
> ajouté ultérieurement.
