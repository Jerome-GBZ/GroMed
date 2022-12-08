# GroMed
[Wiki notion](https://shared-spur-7db.notion.site/Wiki-GroMed-bbffbb9eeffb40169bb655cb8887fdc7)

# Planning
[ ] [11 janvier: Livrable modèle données & processus (AFMP)](#aspect-modélisation)  
[ ] [12 janvier: Livrable modèle de tâche (IHM)](#aspect-ihm)  
[ ] [18 janvier: Livrable document BD (BD)](#aspect-bd)  
[ ] [27 janvier: Démo première version. Revue de code](#aspect-pc)  
[ ] 2 février: Livrable Rapport final (dépôt Git, déploiement e-Cloud)

## Fonctionnalité

Aspect FrontOffice (client)
1. S'authentifier / gérer son profil lié à un établissement
2. Constituer et gérer son panier
3. Afficher ses commandes

Aspect BackOffice (GroMed)
1. Statistiques clients et produits
2. Gestion basique des produits

# Aspect modélisation

- Modèle de données
  - Conception (données sources + cahier des charges)
  - Traduction en modèle relationnel
- Modèle de processus (BPMN):
  - Ajouter un élément au panier
  - valider un panier
  
#### Livrable : description des modèles

# Aspect IHM

- Modèle de tâches
  - Constitution du panier(client)
- Ergonomie
  - Pages pour constuire son panier
  - De manière "Responsive"
  - Et surtout efficiente
- Conception des interfaces utilisateurs:
  - Qualité du code

#### Livrable : description du modèle de tâches + Persona

# Aspect BD

- Initialisation des données
  - Intégration des données sources (open data)
  - Données synthétiques (tests)
- Gestion des transactions : concurrence d’accès sur le stock de produits.
- Gestion des contraintes : prise en compte des contraintes métiers au bon niveau (Front, Back, Triggers BD).
- Optimisation : index, requêtes

#### Livrable : modèle de données opérationnel, liste desprincipales contraintes métiers, scenarios deconcurrence type

# Aspect PC
- Accès aux données 
  - architecture en couches (patron DAO par exemple pour isoler la partie métier de la couche persistance).
- Architecture générale
  - schémas d’architecture (diagrammes de classes, de sequence et/ou diagrammes de composants).
- Qualité du code coté serveur

#### Revue de code à mi-parcours.

# Rendu final

- Document résumant les objectifs du projet, ce qui a
été fait et pas fait (avec justifications), MàJ sur les
rapports précédents, l'organisation équipe,
heuristiques ergonomiques sur la constitution du
panier, un bilan sur le projet.
- Le code source sera accessible via GitLab / Github
- L’application sera déployée sur un serveur de
production (serveur UFR)
