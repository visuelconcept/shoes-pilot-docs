# Bienvenue dans Shoes Pilot

**Shoes Pilot** est le système de pilotage de production (MES) des usines de
chaussures : il suit chaque paire depuis la réception de l'ordre de fabrication
jusqu'à l'emballage final, gère les rebuts et les réintégrations, et alimente
des tableaux de bord temps réel.

Ce guide est organisé en **parcours** : chaque page raconte un cas d'usage de
bout en bout, illustré par des captures d'écran réelles de l'application.

## Par où commencer ?

<div class="grid cards" markdown>

-   :material-account-key: **Rôles & accès**

    ---

    Comprendre les quatre profils (Admin, Admin fonctionnel, Superviseur,
    Opérateur) et ce que chacun peut faire.

    [:octicons-arrow-right-24: Rôles & accès](prise-en-main/roles-et-acces.md)

-   :material-login: **Se connecter**

    ---

    Connexion par identifiant ou par badge sur le terminal tactile.

    [:octicons-arrow-right-24: Se connecter](prise-en-main/se-connecter.md)

-   :material-gesture-tap-button: **Pointer une opération**

    ---

    Le parcours quotidien de l'opérateur : scanner un bac, démarrer, valider.

    [:octicons-arrow-right-24: Pointage opérateur](parcours/operateur-pointage.md)

-   :material-alert-octagon: **Déclarer un rebut**

    ---

    Gauche, droite ou paire complète — et la récupération automatique de
    l'orpheline.

    [:octicons-arrow-right-24: Déclaration de rebut](parcours/declaration-rebut.md)

-   :material-monitor-dashboard: **Superviser la production**

    ---

    Les tableaux de bord par opération, équipe, modèle, ligne et opérateur.

    [:octicons-arrow-right-24: Supervision](parcours/supervision.md)

</div>

## À qui s'adresse ce guide

| Profil | Ce que vous y trouverez |
|--------|-------------------------|
| **Opérateur** | Parcours de pointage, déclaration de rebut, réintégration sur le terminal tactile |
| **Superviseur** | Lecture des tableaux de bord, suivi des lignes et des opérateurs |
| **Administrateur** | Configuration des OF, opérations, lignes, postes et étiquettes |

!!! tip "Les captures d'écran sont toujours à jour"
    Les images de ce guide sont générées automatiquement à partir de
    l'application en fonctionnement (tests end-to-end Playwright). Elles
    reflètent donc l'état réel du produit à chaque publication.
