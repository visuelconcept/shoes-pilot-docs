# Ajouter une workstation

<span class="role-badge">Admin fonctionnel</span>

Créez un poste de travail et rattachez-le à une opération sur une ligne.

## 1. Ouvrir les postes

Menu **Administration → Postes de travail**, puis **Nouveau Poste**.

<figure class="screenshot" markdown>
![Liste des postes](../assets/screenshots/fr/poste-liste.png)
<figcaption>Postes de travail</figcaption>
</figure>

## 2. Configurer le poste

| Champ | Rôle |
|-------|------|
| **Nom** | Libellé du poste (le **code** est généré automatiquement) |
| **Ligne de production** | La ligne du poste, ou **Toutes** pour un poste partagé |
| **Opération** | L'opération gérée — la liste dépend de la ligne choisie |
| **Machine pilotée** | *(optionnel)* machine associée |

<figure class="screenshot" markdown>
![Formulaire poste](../assets/screenshots/fr/poste-form.png)
<figcaption>Configuration du poste</figcaption>
</figure>

!!! info "Ligne puis opération"
    Choisissez d'abord la **ligne** : la liste des **opérations** se limite alors
    à celles configurées sur cette ligne. « Toutes les lignes » propose les
    opérations communes (poste partagé).

!!! tip "Machine pilotée"
    Renseigner une machine active le bouton **Télécharger la recette** sur le
    terminal et transmet la recette à la machine.

## 3. Enregistrer

Touchez **Enregistrer** : le poste est prêt à être sélectionné à la connexion
par badge.

<figure class="screenshot" markdown>
![Poste créé](../assets/screenshots/fr/poste-cree.png)
<figcaption>Poste ajouté</figcaption>
</figure>
