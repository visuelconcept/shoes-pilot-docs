# Superviser la production

<span class="role-badge">Superviseur</span> <span class="role-badge">Admin</span>

Les tableaux de bord offrent une vue temps réel de la production. Ils se
rafraîchissent automatiquement (toutes les 15 à 30 secondes) et se déclinent en
plusieurs axes d'analyse.

## Vue globale

Le tableau de bord principal résume la journée : sous-OF **en cours**,
opérations **terminées aujourd'hui**, **paires produites** et **rebuts**, ainsi
qu'un graphique de production horaire.

<figure class="screenshot" markdown>
![Tableau de bord global](../assets/screenshots/fr/dash-global.png)
<figcaption>Vue d'ensemble de la production du jour</figcaption>
</figure>

## Par opération

Suivi de chaque étape du flux : sous-OF en attente et en cours sur chaque
opération.

<figure class="screenshot" markdown>
![Dashboard par opération](../assets/screenshots/fr/dash-operation.png)
<figcaption>Production par opération</figcaption>
</figure>

## Par équipe

Performance de chaque équipe et classement des opérateurs.

<figure class="screenshot" markdown>
![Dashboard par équipe](../assets/screenshots/fr/dash-equipe.png)
<figcaption>Performance par équipe</figcaption>
</figure>

## Par modèle

État de la production pour chaque modèle de chaussures.

<figure class="screenshot" markdown>
![Dashboard par modèle](../assets/screenshots/fr/dash-modele.png)
<figcaption>Production par modèle</figcaption>
</figure>

## Par ligne

Performance de chaque ligne de production, avec filtres temporels.

<figure class="screenshot" markdown>
![Dashboard par ligne](../assets/screenshots/fr/dash-ligne.png)
<figcaption>Performance par ligne de production</figcaption>
</figure>

**Filtres temporels disponibles :**

| Filtre | Période couverte |
|--------|------------------|
| Équipe en cours | Depuis le début de l'équipe actuelle |
| Équipe précédente | L'équipe précédente |
| Dernières 24 h | Les 24 dernières heures |

**Indicateurs par ligne :** sous-OF actifs, en cours, terminés, paires
produites, **efficacité** (sortie / entrée × 100) et **taux de rebuts**.

## Par opérateur

Classement et indicateurs individuels : paires produites, taux d'efficacité,
taux de rebuts et comparaison à la moyenne de l'équipe.

<figure class="screenshot" markdown>
![Dashboard par opérateur](../assets/screenshots/fr/dash-operateur.png)
<figcaption>Performance par opérateur</figcaption>
</figure>

!!! info "Mise à jour temps réel"
    Les tableaux de bord se mettent à jour automatiquement via WebSocket. En cas
    d'absence de rafraîchissement, vérifiez la connexion réseau du poste.
