# Configurer un ordre de fabrication

<span class="role-badge">Admin</span> <span class="role-badge">Admin fonctionnel</span>

Un **OF** est une commande de production (modèle/coloris, quantités par taille).
Il se découpe en **sous-OF** (les bacs suivis sur le terminal).

!!! info "OF importés de l'ERP"
    En production, les OF arrivent de l'ERP (fichiers XML PRIOS). La création
    manuelle se fait depuis **Articles** ou **Ordres de fabrication**.

## 1. Liste des OF

Statut, priorité et échéance de chaque OF.

<figure class="screenshot" markdown>
![Liste des OF](../assets/screenshots/fr/of-liste.png)
<figcaption>Ordres de fabrication</figcaption>
</figure>

## 2. Détail d'un OF

Produit, répartition par taille et liste des sous-OF.

<figure class="screenshot" markdown>
![Détail d'un OF](../assets/screenshots/fr/of-detail.png)
<figcaption>Détail : produit, tailles, sous-OF</figcaption>
</figure>

## 3. Générer les sous-OF

Ouvrez le détail et touchez **Générer les sous-OF** : les lots sont créés selon
la configuration de subdivision.

<figure class="screenshot" markdown>
![Sous-OF générés](../assets/screenshots/fr/of-sous-of.png)
<figcaption>Sous-OF générés</figcaption>
</figure>

## Référentiels métier

L'administration définit le flux et les référentiels : **opérations**, **lignes**,
**postes**, **équipes**, **modèles**, **motifs de rebut**, **étiquettes**…

<div class="grid" markdown>

<figure class="screenshot" markdown>
![Opérations](../assets/screenshots/fr/admin-operations.png)
<figcaption>Opérations</figcaption>
</figure>

<figure class="screenshot" markdown>
![Lignes de production](../assets/screenshots/fr/admin-lignes.png)
<figcaption>Lignes de production</figcaption>
</figure>

</div>
