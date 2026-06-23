# Rôles & accès

Shoes Pilot distingue quatre profils. Le rôle détermine les écrans accessibles
et les actions autorisées.

| Rôle | Tableaux de bord | Terminal de pointage | Configuration |
|------|:---:|:---:|:---:|
| **Administrateur** | ✅ | ✅ | ✅ |
| **Admin fonctionnel** | ✅ | — | ✅ (données métier) |
| **Superviseur** | ✅ | ✅ | — |
| **Opérateur** | — | ✅ | — |

## Ce que fait chaque rôle

=== "Opérateur"

    Travaille exclusivement sur le **terminal tactile**. Il scanne les bacs,
    pointe le début et la fin des opérations, déclare les rebuts et réintègre
    les chaussures orphelines. Connexion par **badge**.

=== "Superviseur"

    Suit la production en temps réel via les **tableaux de bord** (par
    opération, équipe, modèle, ligne, opérateur) et peut utiliser le
    **terminal**. Il n'accède pas à la configuration métier.

=== "Admin fonctionnel"

    Configure les **données métier** : opérations, lignes, postes, équipes,
    modèles, motifs de rebut, templates d'étiquettes. Accède aux tableaux de
    bord mais **pas au terminal**.

=== "Administrateur"

    Accès complet : configuration, tableaux de bord, terminal et gestion des
    **utilisateurs**.

!!! info "Authentification"
    Les comptes Admin / Superviseur se connectent par **identifiant + mot de
    passe** (jeton valable 24 h). Les opérateurs se connectent par **badge**
    sur le terminal (jeton valable 12 h).

## Comptes de démonstration

| Identifiant | Mot de passe | Rôle |
|-------------|--------------|------|
| `admin` | `demo123` | Administrateur |
| `functional` | `demo123` | Admin fonctionnel |
| `superviseur` | `demo123` | Superviseur |
| `operateur` | `demo123` | Opérateur |

Badges opérateurs de démonstration : `OP001` à `OP008`.
