# gestion-projet-rabatel

# Gestion de projet

## 1.1 Démarrer un projet

### Enjeux

motivations ?
critères de réussite ?

éviter risque échec !

### Plus :

Jour homme : 20 jh = 10 jours si 2 développeurs

## 1.2 Élaborer le projet

### Dimensionner le projet

prévoir quel ressources / sur quel duré / sur quel tâche

materiel : ordi / serveur / logiciels / licences logiciel

### Constitution de l'équipe

chef de projet obligatoire

### Déclencher le projet

chef de projet
calendrier du projet
coût du projet

### Plus :

SAAS : Software as a Service

### 1.3 L'apport de la conduite de projet (gestion de projet)

### Utilité de la gestion de projet ?

Economiser les ressources (temps, argent)

## 2 Les aspects financiers

### 2.1 Le coût du projet

### Plus :

Coût développeur 2000€/mois
Coût développeur pour l'entreprise = 2000€/mois + charges sociales
salaires negociables

# Mercredi 13 nov :

## Les aspects financiers et juridiques :

### Salaires et prestations :

- salaire interne (+ 60% charges)
- Prestations SSII (markup - 60%)
- Variables : competences, experience, modalité

### Modes de facturation :

#### Regles :

- Facturation mensuelle
- Negociation durée d'engagement
- 30-60 jours de paye

#### Forfait :

- Payement échelonné
- 10-30% à la commande
- 20-30% à la recette

### Infrastructure :

#### Hébergement :

- Solutions virtualisées
- Cloud
- Tarification selon usage

#### Maintenance :

- Gestion utilisateur
- Supervition systéme
- Sauvegardes

### Support et Services :

#### Support utilisateur :

- Niveau 1, 3, 3 (1 = petit ticket / 3 = grosse modification rapidre(prestataire externe))
- SLA definis
- Facturation selon volume

#### Coût additionnels :

- Formations
- Marketing
- Documentation
- Frais commerciaux

### Struture et Indicateurs :

#### Structure temporelle :

- Vision semestrielle / annuelle
- Buisness case multi-périodes
- Consolidation par catégories

### Indicateurs Clés :

#### Engagement :

- % utilisation budget
- Suivi rythme dépences

#### Dépassement :

- Montant > Budget initial

#### Econommies :

- Montant non utilisé
- Budget restitué

## Gestion Financières des projets :

### Les compte rendus d'activité (CRA) :

#### Responsabilité du chef de Projet :

- Sencibilisation aux aspects financiers
- Maitrise des coûts (qualité, delait)

### La reconnaissance des Chiffres :

#### Principe :

- Modèle comptable specifiques pour les entreprises de R&D
- Lissage du chiffre d'affaires selon le rythme des investissements

#### Rôle du Chef de Projet ;

- Décompte des activités de développement
- Evaluation de l'apport

## Protection des Données Personnelles :

### principes Fondamentaux :

- Application du RGPD depuis 2016 dans l'UE
- Propriété des données par les individues
- Responssabilisation des organisations

#### Acteurs clés :

- Data subject (individuel)
- Data controllet (Organisme de contrôle)
- Data Processor

### Droits et Obligations :

#### Droits des individues :

- Consultation des données
- Rectifications
- Suppression
- Informations en cas de validation

#### Obligations des Organisations

- Limitation de la collecte aux besoins légitimes

### Résumé RGPD :

- Règlement 2016/679 définissant le cadre technique de protection des données
- Implémentation obligatoire des mesures techniques depuis le 25/05/2018
- API et interfaces requises pour l'export/portabilité des données
- Mise en place de processus de traitement documentés (registres)
- Intégration de mécanismes de consentement dans les systèmes
- Sanctions jusqu'à 4% du CA mondial ou 20M€
- DPO obligatoire pour +250 employés ou données sensibles
- Documentation technique des flux de données et traitements
- Système de notification d'incidents avec délai de 72h max
- Conformité technique requise pour tout système traitant des données EU

## Prise en compte des risques :

### Axe du temps (développement) :

- Expression des besoins
- Phases de développement
- Livraison
- Maintenance
- ⚠️ Sans cet axe :
  - Non conformité au besoins
  - Dérives du projet
  - Tests insufisants

### Axe d'Analyse (Abstraction) :

- Du conceptuel au concret
- Niveau d'abstraction variable selon les phases
- Compatible avec UML et Merise
- ⚠️ Dans cet axe :
  - Code non optimal
  - Fonctions majeures oubliées
  - Difficulté d'évolution

### L'importance de l'intgration :

- Les méthodes doivent fonctionner ensemble
- Eviter l'application isolée des methodes
- Rechercher l'armonie

## Le modèle de développement :

### Le modèle cascade :

#### Structure :

- Progression linéaire
- Chaque étape suit la prècèdente
- Pas de retour en arrière facile

#### Etapes clés :

1. Idée - démmarage
2. Expression des besoins
3. Spécifications
4. Développement
5. Tests unitaires
6. Tests d'intégration
7. Tests fonctionnalité
8. Installation

#### Point d'attention

- Coût expodentiel des modifications tardives
- "Effet cascade" : difficile de remonter le courant

### Le modèle en V :

#### Caracteristique :

- Evolution du modele en cascade
- Anticipation des tests
- Symetrie entre conception et validation

#### Avantages :

- Tests sous-traité et objectfs
- Vérifications précoce de la couverture fonctionnelle
- Limitation des erreurs de conception

#### Inconvenient :

- Durée augmenté de 30 à 40 %

### Le modéle Itératif :

#### Principes :

- Succession de mini-cascades
- Focus sur les risques techniques
- Evolution constante des périmètres

#### Organisation :

- Debut pas les parties complèxes
- Phases de stabilisation
- Phase d'industrialisation
