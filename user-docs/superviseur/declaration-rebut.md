# Déclarer un rebut

<span class="role-badge">Superviseur</span>

En général, le **superviseur** reprend l'opération en cours sur le terminal pour
saisir les rebuts. Trois types :

| Type | Code | Signification |
|------|:----:|---------------|
| Paire | **P** | Les deux chaussures sont défectueuses |
| Gauche | **G** | Gauche défectueuse → la droite part au stock de réintégration |
| Droite | **D** | Droite défectueuse → la gauche part au stock de réintégration |

!!! note "Qui déclare les rebuts ?"
    Par défaut, seul le **superviseur** (ou l'admin) saisit les rebuts. Sur les
    opérations configurées en conséquence, l'**opérateur** peut les déclarer
    lui-même, directement depuis son pointage.

## Ajouter le rebut

1. Section **Rebuts** → **Ajouter**.

    <figure class="screenshot terminal" markdown>
    ![Section Rebuts](../assets/screenshots/fr/rebut-section.png)
    <figcaption>Section Rebuts pendant le pointage</figcaption>
    </figure>

2. Choisissez le **type** (G / D / P).

    <figure class="screenshot terminal" markdown>
    ![Type de rebut](../assets/screenshots/fr/rebut-type.png)
    <figcaption>Type : gauche, droite ou paire</figcaption>
    </figure>

3. Réglez la **quantité** et choisissez le **motif**.

    <figure class="screenshot terminal" markdown>
    ![Quantité et motif](../assets/screenshots/fr/rebut-motif.png)
    <figcaption>Quantité et motif</figcaption>
    </figure>

4. Touchez **Ajouter le rebut**. Les compteurs se mettent à jour.

    <figure class="screenshot terminal" markdown>
    ![Rebut ajouté](../assets/screenshots/fr/rebut-ajoute.png)
    <figcaption>Compteurs mis à jour</figcaption>
    </figure>

!!! info "Récupération automatique"
    Pour un rebut **G** ou **D**, la chaussure valide opposée part
    automatiquement au stock de réintégration : elle pourra reconstituer une
    paire plus tard (même OF, même taille). La sortie reste toujours en **paires
    complètes**.
