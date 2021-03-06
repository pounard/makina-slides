# Gestion et maintenance d'un parc d'équipements industriels

--------------------------------------------------------------------------------

> La gestion de maintenance assistée par ordinateur est une méthode de gestion assistée d'un logiciel destiné aux services de maintenance d'une entreprise afin de l'aider dans ses activités.

<cite> — http://fr.wikipedia.org/wiki/GMAO</cite>

.fx: quoteslide

--------------------------------------------------------------------------------

# Introduction à la GMAO

.fx: alternate

--------------------------------------------------------------------------------

# La GMAO en quelques mots

* Référencer ses équipements en entrant dans le détail de leur architecture technique
* Assurer le suivi et la maintenance de ces équipements
* Piloter l'activité de maintenance via des tableaux de bords
* Accessible en mode web 24h/24
* Interconnexion avec les applications du SI
* Utilisée par tous les services de l'entreprise
* Mais aussi par les clients et partenaires
* Accès sécurisé : identifiant/mot de passe, HTTPS, LDAP

--------------------------------------------------------------------------------

# Une GMAO développée pour la société ALMA Services

.fx: alternate

--------------------------------------------------------------------------------

# La société ALMA Services > Le métier

* Secteur des équipements, installations et services pour la distribution des produits pétroliers en aval des raffineries
* Maintenance des camions citernes et dépôts pétroliers
* 10 établissements, 90 personnes

![ALMA Services - Camions et dépôts](images/alma-depot-camion.jpg)

![ALMA Services](images/alma-logo.png)

--------------------------------------------------------------------------------

# La société ALMA Services > Le besoin initial

* Automatiser son processus métier de gestion des interventions
* Modéliser dans le détail l'architecture techniques des équipements
* Assurer la traçabilité de toutes les interventions techniques
* Impliquer tous les services
* Offrir à ses clients un accès sécurisé
* Produire des tableaux de bord et bilans pour suivre et piloter l'activité
* Connecter l'outil aux autres applications du SI (clients, stocks, ...)
* Application web : mobilité, ergonomie, évolutivité

![Marketing et Statégie](images/marketing-strategy.jpg)

--------------------------------------------------------------------------------

# La société ALMA Services > Les contraintes

*   Importance de l'ergonomie
*   Récupération de l'historique des données des anciennes GMAO  :
    * 1 GMAO en PHP
    * 7 GMAO "quasi" identiques en Access

![ALMA Services](images/contraintes.jpg)

--------------------------------------------------------------------------------

# Un développement utilisant uniquement des outils <br />et logiciels libres

.fx: alternate

--------------------------------------------------------------------------------

# Quels avantages par rapports aux logiciels propriétaires existants ?

*   Pas de coût d'acquisition de licence mais coût de développement initial
*   Indépendance totale vis à vis de l'éditeur/prestataire
    * Accès au code source
    * Formations internes pour les développements futurs
* Aide et pérennité des outils grâce aux communautés d'utilisateurs et de développeurs
*   Le principal : adapter la solution aux besoins du client

--------------------------------------------------------------------------------

# Des outils Open Source de plus en plus utilisés

* Pour répondre à tous les besoins : de la conception du logiciel à sa mise en production et son hébergement
* Des projets d'envergure les adoptent (exemples pour le framework Django) :

![Autolib](images/autolib-logo.png)

![Oscaro](images/oscaro-logo.png)

mais aussi : La Nasa, le Washington Times, Google App Engine, ...

--------------------------------------------------------------------------------

# GMAO, les principales fonctionnalités

.fx: alternate

--------------------------------------------------------------------------------

# GMAO > Connexion sécurisée à l'application

![GMAO : Écran de connexion](images/screenshots/00-ecran-de-connexion.png)
<div class="img_legend">Écran de connexion</div>

.fx: gmao_image

--------------------------------------------------------------------------------

# GMAO > Tableau de bord métier : piloter l'activité

Vue d'ensemble des interventions et des missions ; alertes sur les équipements et les contrats

![GMAO : Tableau de bord](images/screenshots/01-tableau-de-bord-1.png)
<div class="img_legend">Tableau de bord</div>

.fx: gmao_image

--------------------------------------------------------------------------------

# GMAO > Constitution technique des équipements

Description des équipements faisant l'objet d'interventions de maintenance (ex : camion, dépôt pétrolier, station service)

![GMAO : Camion](images/screenshots/02-equipement-camion.png)
<div class="img_legend">Fiche d'un camion citerne</div>

.fx: gmao_image

--------------------------------------------------------------------------------

# GMAO > Constitution technique des équipements

Possibilité de développer de nouveaux types d'équipements (ex : éolienne, pipeline, station de mesure, téléphérique, ascenseur, ...)

![GMAO : Dépôt](images/screenshots/03-equipement-depot.png)
<div class="img_legend">Fiche d'un dépôt pétrolier</div>

.fx: gmao_image

--------------------------------------------------------------------------------

# GMAO > Les clients

Synchronisation de la DB clients avec la BD ERP/CRM (ex : Ciel Quantum, Sage, ERP maison, SugarCRM...)

![GMAO : Gestion des clients](images/screenshots/04-client-1.png)
<div class="img_legend">Fiche client</div>

.fx: gmao_image

--------------------------------------------------------------------------------

# GMAO > Les clients

Possibilité de compléter la fiche client (adresses, instructions particulières, documentations, ...)

![GMAO : Gestion des clients](images/screenshots/04-client-2.png)
<div class="img_legend">Suite de la fiche client</div>

.fx: gmao_image

--------------------------------------------------------------------------------

# GMAO > Les contrats

Des contrats en lien avec les clients, les équipements et les interventions. Alertes et bilans.

![GMAO : Gestion des contrats](images/screenshots/05-contrat.png)
<div class="img_legend">Gestion de contrat</div>

.fx: gmao_image

--------------------------------------------------------------------------------

# GMAO > Organisation mono ou multi-agences

Organisation des responsables et des techniciens par agence

![GMAO : Gestion des agences](images/screenshots/06-agence-1.png)
<div class="img_legend">Liste des agences</div>

.fx: gmao_image

--------------------------------------------------------------------------------

# GMAO > Organisation mono ou multi-agences

Tableau de bord, planning et bilans par agence

![GMAO : Fiche agence](images/screenshots/06-agence-2.png)
<div class="img_legend">Détail d'une fiche agence</div>

.fx: gmao_image

--------------------------------------------------------------------------------

# GMAO > Les intervenants

Liste des intervenants réalisant les opérations de maintenance

![GMAO : Liste des intervenants](images/screenshots/07-intervenant-1.png)
<div class="img_legend">Liste des intervenants</div>

.fx: gmao_image

--------------------------------------------------------------------------------

# GMAO > Les intervenants

Saisie des rapports d'intervention par les intervenants

![GMAO : Fiche intervenant](images/screenshots/07-intervenant-2.png)
<div class="img_legend">Détail d'une fiche intervenant</div>

.fx: gmao_image

--------------------------------------------------------------------------------

# GMAO > Les pièces détachées

Module « Articles » : Synchronisation de la DB pièces détachées avec la BD ERP

![GMAO : Gestion des agences](images/screenshots/08-article.png)
<div class="img_legend">Détail d'une fiche article</div>

.fx: gmao_image

--------------------------------------------------------------------------------

# GMAO > Les stocks de pièces détachées

Module « Stocks » : Visualiser le contenu des stocks issu de l'ERP

![GMAO : Consultation des stocks](images/screenshots/09-stocks-1.png)
<div class="img_legend">Consultation des stocks de pièces détachées</div>

.fx: gmao_image img_w75percent

--------------------------------------------------------------------------------

# GMAO > Aide à la feuille de temps

Suivi des heures réalisées en intervention

![GMAO : Aide à la feuille](images/screenshots/10-aide-a-la-feuille-de-temps.png)
<div class="img_legend">Consulter ses heures réalisées en intervention</div>

.fx: gmao_image

--------------------------------------------------------------------------------

# GMAO > Aide à la planification

Planifier en avance les interventions récurrentes

![GMAO : Aide à la planification](images/screenshots/11-aide-a-la-planification-1.png)
<div class="img_legend">Planifications d'interventions récurrentes</div>

.fx: gmao_image img_w85percent

--------------------------------------------------------------------------------

# GMAO > Planning

Suivi des interventions par agence, équipe et intervenant. Synchronisation avec des agendas du marché.

![GMAO : Planning](images/screenshots/12-planning-2.png)
<div class="img_legend">Interventions planifiées à venir</div>

.fx: gmao_image img_w90percent

--------------------------------------------------------------------------------

# GMAO > Le rapport d'intervention

Revue de contrat, préparation, planification, rapport PDF, pré-facturation

![GMAO : Rapport d'intervention](images/screenshots/13-intervention-1.png)
<div class="img_legend">Rapport d'intervention : iniation de la mission et revue de contrat</div>

.fx: gmao_image img_w65percent

--------------------------------------------------------------------------------

# GMAO > Préparation de facture

Imprimable en PDF, transmission à l'ERP pour facturation

![GMAO : Préparation de facture](images/screenshots/14-preparation-de-facture-1.png)
<div class="img_legend">Préparation de facture</div>

.fx: gmao_image img_w75percent

--------------------------------------------------------------------------------

# GMAO > Bilans et statistiques

![GMAO : Bilans et indicateurs](images/screenshots/15-bilans-3.png)
<div class="img_legend">Bilans et indicateurs par agences</div>

.fx: gmao_image img_w70percent

--------------------------------------------------------------------------------

# GMAO > Bilans et statistiques

![GMAO : Bilans et indicateurs](images/screenshots/15-bilans-2.png)
<div class="img_legend">Bilans par profil d'intervention</div>

.fx: gmao_image

--------------------------------------------------------------------------------

# GMAO > Bilans et statistiques

![GMAO : Carte des équipements et des agences](images/screenshots/15-bilans-6-carte.png)
<div class="img_legend">Carte des équipements et des agences</div>

.fx: gmao_image img_w85percent

--------------------------------------------------------------------------------

# GMAO > Utilisation en mobilité

![GMAO : Utilisation depuis une tablette](images/screenshots/18-mobilite-tablette.jpg)
<div class="img_legend">Utilisation depuis une tablette</div>

.fx: gmao_image img_w80percent

--------------------------------------------------------------------------------

# GMAO > Utilisation en mobilité

![GMAO : Utilisation depuis un smartphone](images/screenshots/18-mobilite-smartphone.jpg)
<div class="img_legend">Utilisation depuis une smartphone</div>

.fx: gmao_image img_w90percent

--------------------------------------------------------------------------------

# Les outils Open Source utilisés > Pour le développement

*   Interface utilisateur :
    * [Twitter Bootstrap](http://getbootstrap.com/)
    * [JQuery](http://jquery.com/)
    * CSS3, HTML5
*   Framework de développement : [Django](https://www.djangoproject.com/), écrit en [Python](http://python.org/) et BDD [PostgreSQL](http://www.postgresqlfr.org/)
*   Modules Django issus de la communauté : gestion de workflow, génération de PDF, support LDAP, etc.
*   Tests automatisés : [Jenkins](http://jenkins-ci.org/)
*   Déploiements automatisés : [Fabric](http://fabric.readthedocs.org/)
*   Worflow de développement avec [Git](http://git-scm.com/), un gestionnaire de code source décentralisé

En savoir plus sur le blog de Makina Corpus : [les outils](http://makina-corpus.com/blog/metier/2013/les-technologies-utilisees-dans-notre-gmao-job), [le workflow de développement avec Git](http://makina-corpus.com/blog/metier/2014/un-workflow-git-efficace-pour-les-projets-a-moyen-long-terme)

--------------------------------------------------------------------------------

# Les outils Open Source utilisés > Côté système

* Système d'exploitation : [Debian](http://www.debian.org/)
* Gestion des machines virtuelles : [KVM](http://www.linux-kvm.org) (Kernel-based Virtual Machine)
* Redondance des machines virtuelles hébergées sur deux serveurs miroirs : [DRBD](http://www.drbd.org/) (Distributed Replicated Block Device)
* Supervision : [Nagios](http://www.nagios.org/)
* Gestion centralisée des comptes utilisateurs et de l’authentification aux applications : [OpenLDAP](http://www.openldap.org/), [FusionDirectory](http://www.fusiondirectory.org/)

--------------------------------------------------------------------------------

# Contribuer en retour

Bonne pratique : redistribuer tout module réutilisable à la communauté, alimenter le cercle vertueux.

Deux contributions issues du projet :

* [django-db-faker](https://github.com/fle/django-db-faker) : Module façilitant l'anonymisation des données d'une base de données Django.
* [django-jsignature](https://github.com/fle/django-jsignature) : Module intégrant le module JQuery [jSignature](https://github.com/brinley/jSignature) pour la capture d'une signature manuelle réalisée via le navigateur.

![django-jsignature](images/django-jsignature.jpg)

.fx: img_w75percent

--------------------------------------------------------------------------------

# Gestion de projet Agile

*   Réunion hebdomadaire :
    * Démonstrations
    * Validations
    * Écriture du cahier des charges
    * Choix des prochaines tâches à traiter
* Mises en production régulières et reccueil des retours utilisateurs au plus tôt
* Prise en compte du changement

<p style="padding-top:30px;font-size:130%">=> Obtenir une solution optimale correspondant aux besoins de ses utilisateurs</p>

--------------------------------------------------------------------------------

# Merci ! <br /><br /> 09 53 73 22 74 <br /> sylvain.boureliou@makina-corpus.com <br /> http://makina-corpus.com

