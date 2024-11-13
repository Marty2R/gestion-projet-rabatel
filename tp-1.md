## Partie 1 : Analyse des Enjeux :

### Identifiez et classez les enjeux startégiques :

1. Enjeux 1 :

- Établir la position de leader : Ameliorer la position de leader sur le marché pour obtenir un maximum de parts de marché face aux concurents.

2. Enjeux 2 :

- Accélération de la transformation des opportunités en ventes : Réduire le temps nécessaire pour convertir des opportunités en ventes afin d'augmenter le volume d'affaires plus rapidement.

3. Enjeux 3 :

- S'étendre à un nouveau marché du conseil : Conquérir un nouveau secteur de conseil pour diversifier les revenus et augmenter la base de clients.

### Identifiez et classez les enjeux opérationnels :

1. Enjeux 1 :

- Efficacité de la gestion de la relation client : Automatiser et optimiser le traitement des contacts pour réduire le temps de traitement manuel.

2. Enjeux 2 :

- Suivi et analyse des opérations : Développer des outils de suivi permettant une visibilité de l'avancement des affaires et des opportunités.

3. Enjeux 3 :

- Intégrer des outils : Assurer la compatibilité du CRM avec les outils existants pour faciliter au utilisateurs l’adoption et l’efficacité au quotidien.

### Justifiez votre classification :

- Les enjeux stratégiques sont liés aux objectifs globaux de croissance et de positionnement sur le marché, tandis que les enjeux opérationnels concernent l'efficacité des processus internes pour atteindre ces objectifs.

## Partie 2 : Définition des Objectifs :

- Objectif de positionnement : Augmenter la part de marché dans le nouveau secteur d'ici un an.

- Optimisation du processus de vente : Réduire le temps de conversion des opportunités en ventes en six mois.

- Amélioration de la gestion des contacts : Atteindre 90 % de contacts qualifiés dans la base de données d'ici huit mois.

- Adoption de l'outil CRM : Former les utilisateurs cibles.

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
