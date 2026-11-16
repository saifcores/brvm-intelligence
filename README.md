# BRVM Intelligence

**Understand. Analyze. Invest.**

BRVM Intelligence est une plateforme personnelle d'apprentissage et
d'analyse dédiée à la **Bourse Régionale des Valeurs Mobilières
(BRVM)**.

Le projet poursuit deux objectifs : 

1. **Apprendre à investir :**
comprendre le marché financier de l'UEMOA, découvrir les sociétés
cotées, lire leurs informations financières et suivre un portefeuille
virtuel.

2. **Construire un produit FinTech :** développer
progressivement une application fiable, documentée et évolutive, qui
pourra à terme être utile à d'autres investisseurs de l'UEMOA.

> **Statut :** cadrage et développement du MVP.\
> **Public initial :** usage personnel, niveau débutant en
> investissement.\
> **Périmètre :** éducation financière, consultation de données, analyse
> et simulation.\
> **Limite :** l'application ne passe pas d'ordres de Bourse et ne
> fournit pas de conseil financier personnalisé.

## Sommaire

-   [Objectifs](#-objectifs)
-   [Fonctionnalités](#-fonctionnalités)
-   [Périmètre du MVP](#-périmètre-du-mvp)
-   [Architecture et technologies](#-architecture-et-technologies)
-   [Structure du projet](#-structure-du-projet)
-   [Prérequis](#-prérequis)
-   [Installation et démarrage](#-installation-et-démarrage)
-   [Configuration](#-configuration)
-   [Données financières](#-données-financières)
-   [Principes métier](#-principes-métier)
-   [Tests et qualité](#-tests-et-qualité)
-   [Roadmap](#-roadmap)
-   [Sécurité et limites](#-sécurité-et-limites)
-   [Contribution](#-contribution)
-   [Licence](#-licence)
-   [Sources utiles](#-sources-utiles)

------------------------------------------------------------------------

## 🎯 Objectifs

BRVM Intelligence vise à rendre le marché financier régional plus
compréhensible pour un investisseur débutant.

L'application doit permettre de :

-   Comprendre le fonctionnement de la BRVM et les acteurs du marché
    financier de l'UEMOA.
-   Apprendre les notions essentielles : actions, obligations,
    dividendes, ordres de Bourse et risques.
-   Consulter les sociétés cotées et les informations disponibles à leur
    sujet.
-   Suivre les cours et les indices à partir de données datées et
    sourcées.
-   Découvrir les principaux indicateurs financiers.
-   Simuler des achats et des ventes sans engager d'argent réel.
-   Suivre la performance d'un portefeuille virtuel.
-   Documenter ses analyses et ses décisions.

### Principes du produit

-   **Education first :** expliquer les concepts avant de présenter les
    indicateurs.
-   **Data transparency :** afficher la source, la période et la date
    des données.
-   **No false real-time data :** ne jamais présenter une donnée
    ancienne comme une cotation en temps réel.
-   **No blind recommendations :** un ratio ou une performance ne
    constitue pas à lui seul une recommandation d'investissement.
-   **Personal first :** valider l'utilité du produit par un usage
    personnel avant de l'ouvrir à d'autres utilisateurs.

------------------------------------------------------------------------

## ✨ Fonctionnalités

  -----------------------------------------------------------------------
  Module                  Description             Priorité
  ----------------------- ----------------------- -----------------------
  Dashboard               Vue d'ensemble du       MVP
                          marché et du            
                          portefeuille virtuel    

  BRVM Academy            Cours, glossaire,       MVP
                          exercices et quiz pour  
                          débutants               

  Market Watch            Sociétés cotées, cours  MVP
                          disponibles, variations 
                          et watchlist            

  Company Explorer        Fiches sociétés,        MVP
                          données financières et  
                          ratios                  

  Portfolio Simulator     Portefeuille fictif,    MVP
                          achats, ventes et       
                          performances            

  Dividend Tracker        Historique et suivi des Évolution
                          dividendes              

  Investment Journal      Notes, analyses et      Évolution
                          historique des          
                          décisions               

  AI Assistant            Explications            Évolution
                          pédagogiques basées sur 
                          des données sourcées    
  -----------------------------------------------------------------------

### Dashboard

Le tableau de bord présente la dernière situation connue du marché, les
indices et statistiques disponibles, les sociétés suivies, les derniers
cours disponibles et leurs dates, ainsi que la valeur et la performance
du portefeuille virtuel.

### BRVM Academy

Un parcours pédagogique progressif :

1.  Découvrir la BRVM et le marché financier de l'UEMOA.
2.  Comprendre les actions, les obligations et les dividendes.
3.  Comprendre le rôle des SGI et le fonctionnement des transactions.
4.  Apprendre à lire les états financiers.
5.  Comprendre les ratios et les méthodes de valorisation.
6.  Découvrir la diversification et la gestion des risques.

Chaque leçon peut comprendre une explication, des exemples, un
glossaire, un quiz et un exercice pratique.

### Market Watch

-   Catalogue des sociétés et instruments suivis.
-   Consultation des cours disponibles et de leur historique.
-   Variations et volumes, lorsque les données sont disponibles.
-   Recherche, filtres et watchlist personnelle.

### Company Explorer

Une fiche par société avec les informations disponibles : nom, symbole,
pays, secteur, activité, chiffre d'affaires, résultat net, capitaux
propres, endettement, bénéfice par action et dividende par action.

Les ratios calculables peuvent inclure le PER, le rendement du
dividende, le ROE et la marge nette. Chaque indicateur doit afficher sa
formule, sa période de référence et une explication accessible.

### Portfolio Simulator

Le simulateur permet de créer un portefeuille avec un capital virtuel,
d'enregistrer des achats et ventes fictifs, de configurer des frais
estimés, de suivre les quantités et liquidités, de calculer le coût
moyen et de distinguer les plus-values réalisées et latentes.

**Aucun argent réel n'est transféré et aucun ordre n'est envoyé à une
SGI.**

### Dividend Tracker

Module prévu pour suivre les dividendes annoncés, estimés et payés,
leurs dates et les revenus théoriques associés aux positions virtuelles.

### Investment Journal

Espace personnel pour consigner l'entreprise étudiée, la date de
l'analyse, les éléments qui motivent une décision, les risques
identifiés, les hypothèses retenues et les résultats observés lors d'un
suivi ultérieur.

### AI Assistant

Fonctionnalité envisagée après le MVP. L'assistant pourra expliquer des
notions et des données sourcées, signaler les informations manquantes et
aider à comprendre les états financiers. Il ne devra pas fabriquer de
données ni formuler de recommandations personnalisées d'achat ou de
vente.

------------------------------------------------------------------------

## 🚀 Périmètre du MVP

### Inclus dans le MVP

-   Dashboard de marché.
-   Import contrôlé de données de marché.
-   Catalogue des sociétés.
-   Historique des cours disponibles.
-   Watchlist.
-   Fiches entreprises.
-   Ratios fondamentaux lorsque les données sont suffisantes.
-   Simulateur de portefeuille virtuel.
-   Premiers contenus pédagogiques et quiz.
-   Tests des règles métier essentielles.

### Prévu après le MVP

-   Suivi avancé des dividendes.
-   Journal d'investissement enrichi.
-   Assistant IA pédagogique.
-   Automatisation supplémentaire des imports de données.
-   Application mobile éventuelle.
-   Fonctionnalités publiques et modèle économique, après validation.

### Hors périmètre

-   Passage d'ordres réels.
-   Connexion transactionnelle à une SGI.
-   Conservation ou gestion de fonds pour des tiers.
-   Recommandations personnalisées d'achat ou de vente.
-   Cotations temps réel sans source et droits adaptés.

------------------------------------------------------------------------

## 🏗️ Architecture et technologies

Le choix initial est une architecture **Modular Monolith**. Elle
conserve une base de code simple à développer et à déployer, tout en
séparant les domaines métier.

  -----------------------------------------------------------------------
  Couche                  Technologie cible       Utilisation
  ----------------------- ----------------------- -----------------------
  Frontend                Next.js, React,         Interface utilisateur
                          TypeScript              

  Backend                 Java 21, Spring Boot 3+ API REST et logique
                                                  métier

  Sécurité                Spring Security         Authentification et
                                                  autorisation

  Persistance             Spring Data JPA         Accès aux données

  Traitements             Spring Batch            Imports et traitements

  Modularité              Spring Modulith         Organisation des
                                                  modules

  Base de données         PostgreSQL              Données métier et
                                                  historiques

  Cache                   Redis                   Cache, si nécessaire

  Conteneurs              Docker, Docker Compose  Environnement
                                                  reproductible

  CI/CD                   GitHub Actions          Compilation et tests
                                                  automatisés

  Observabilité           OpenTelemetry           Traces et métriques,
                                                  selon le déploiement
  -----------------------------------------------------------------------

Les versions et dépendances exactes seront définies dans les fichiers de
build du projet.

### Modules backend envisagés

-   `identity` : identité et accès utilisateur.
-   `academy` : cours, leçons et quiz.
-   `market` : instruments, cotations et sources de données.
-   `company` : sociétés et informations financières.
-   `analytics` : calcul et présentation des indicateurs.
-   `portfolio` : portefeuilles et transactions virtuelles.
-   `dividend` : événements et revenus de dividendes.
-   `journal` : analyses et notes personnelles.
-   `shared` : composants techniques communs strictement nécessaires.

### Flux de données simplifié

``` mermaid
flowchart TD
    SOURCE["Sources officielles et fichiers autorisés"]
    IMPORT["Import et validation"]
    MARKET["Module Market Data"]
    COMPANY["Module Company & Analytics"]
    DB[("PostgreSQL")]
    API["Spring Boot REST API"]
    WEB["Next.js Frontend"]
    USER["Utilisateur"]

    SOURCE --> IMPORT
    IMPORT --> MARKET
    MARKET --> DB
    COMPANY --> DB
    DB --> API
    API --> WEB
    WEB --> USER
```

------------------------------------------------------------------------

## 📁 Structure du projet

Structure cible proposée pour le dépôt :

``` text
brvm-intelligence/
├── apps/
│   ├── backend/
│   │   ├── src/
│   │   ├── pom.xml
│   │   └── README.md
│   └── frontend/
│       ├── app/
│       ├── public/
│       ├── package.json
│       └── README.md
├── infrastructure/
│   ├── docker/
│   └── monitoring/
├── docs/
│   ├── product/
│   │   ├── PRD.md
│   │   └── ROADMAP.md
│   ├── architecture/
│   │   ├── C4.md
│   │   └── DATA_MODEL.md
│   └── decisions/
├── scripts/
├── .env.example
├── .gitignore
├── compose.yaml
└── README.md
```

Cette structure est une cible d'organisation. Elle pourra être ajustée
selon les fichiers réellement créés pendant les premiers jalons.

------------------------------------------------------------------------

## 🧰 Prérequis

Pour développer localement, prévoir :

-   Git.
-   Java 21.
-   Maven, ou le Maven Wrapper du backend.
-   Node.js, version LTS compatible avec la version de Next.js retenue.
-   npm, pnpm ou le gestionnaire de paquets choisi.
-   Docker et Docker Compose.
-   Un éditeur de code.

Vérifier les installations :

``` bash
git --version
java -version
docker --version
docker compose version
node --version
npm --version
```

------------------------------------------------------------------------

## ⚙️ Installation et démarrage

Les commandes ci-dessous décrivent le parcours de démarrage cible. Elles
supposent que les applications, le fichier Compose et les scripts
correspondants ont été créés. Adapter les chemins si l'organisation du
dépôt évolue.

### 1. Récupérer le projet

``` bash
git clone <URL_DU_DEPOT>
cd brvm-intelligence
```

### 2. Configurer les variables d'environnement

``` bash
cp .env.example .env
```

Renseigner les valeurs locales dans `.env`. Ne jamais committer ce
fichier.

### 3. Démarrer les dépendances

Si `compose.yaml` configure PostgreSQL et les autres dépendances locales
:

``` bash
docker compose up -d
docker compose ps
```

### 4. Démarrer le backend

Avec Maven Wrapper, depuis le dossier backend :

``` bash
cd apps/backend
./mvnw spring-boot:run
```

Sous Windows :

``` powershell
mvnw.cmd spring-boot:run
```

### 5. Démarrer le frontend

Dans un second terminal :

``` bash
cd apps/frontend
npm install
npm run dev
```

### 6. Accéder à l'application

Par défaut, Next.js démarre généralement sur `http://localhost:3000`,
sauf configuration différente.

L'URL du backend et son éventuelle documentation API seront indiquées
dans la configuration et la documentation technique une fois les
endpoints créés.

------------------------------------------------------------------------

## 🔐 Configuration

Le fichier `.env.example` doit documenter les variables nécessaires sans
contenir de secret réel.

Exemple indicatif à adapter à la configuration effective :

``` dotenv
# Application
APP_ENV=local

# Database
POSTGRES_DB=brvm_intelligence
POSTGRES_USER=brvm_user
POSTGRES_PASSWORD=change_me
POSTGRES_HOST=localhost
POSTGRES_PORT=5432

# Backend
BACKEND_PORT=8080

# Frontend
NEXT_PUBLIC_API_URL=http://localhost:8080
```

Les noms de variables doivent rester cohérents entre Docker Compose,
Spring Boot et Next.js.

**Sécurité :** - Utiliser des secrets différents en local et en
production. - Ne jamais publier de mots de passe, clés API ou tokens. -
Ajouter `.env` aux fichiers ignorés par Git. - Préférer un gestionnaire
de secrets pour les environnements déployés.

------------------------------------------------------------------------

## 📊 Données financières

La qualité et la traçabilité des données sont essentielles.

### Sources à privilégier

-   BRVM : https://www.brvm.org/
-   Bulletins officiels de la cote :
    https://www.brvm.org/fr/bulletins-officiels-de-la-cote
-   Données de fin de journée :
    https://www.brvm.org/fr/donnees-de-fin-de-journee
-   BCEAO : https://www.bceao.int/
-   AMF-UMOA : https://www.amf-umoa.org/

### Règles de gestion des données

Chaque donnée de marché doit conserver, dans la mesure où l'information
est disponible :

-   L'instrument concerné.
-   La date de séance ou la période de référence.
-   La valeur.
-   L'unité et la devise.
-   La source.
-   La date d'importation.
-   Le statut de validation.
-   Le niveau de fraîcheur ou de retard connu.

Les imports doivent être contrôlés, traçables et idempotents autant que
possible.

### Catégories de données

L'application doit distinguer explicitement :

1.  **Donnée officielle :** publiée par une source identifiée.
2.  **Donnée importée :** intégrée depuis un fichier ou une source
    autorisée.
3.  **Donnée calculée :** produite par l'application à partir de données
    identifiées.
4.  **Donnée fictive :** utilisée uniquement pour les démonstrations et
    les tests.

Ne jamais présenter une donnée fictive comme une donnée réelle.

### Accès et réutilisation

Avant d'automatiser une collecte ou de publier des données, vérifier les
conditions d'accès, de licence, de réutilisation et de redistribution
auprès de la source concernée. Le fait qu'une information soit
consultable sur un site ne signifie pas nécessairement qu'elle peut être
redistribuée librement.

Le MVP doit pouvoir fonctionner avec des données historiques autorisées
et importées manuellement. Le temps réel n'est pas une dépendance du
lancement.

------------------------------------------------------------------------

## 🧮 Principes métier

### Calcul des ratios

Les ratios ne doivent être calculés que lorsque les données nécessaires
sont disponibles, cohérentes et comparables.

**PER :**

``` text
PER = Cours de l'action / Bénéfice par action
```

**Rendement du dividende :**

``` text
Rendement du dividende = Dividende annuel par action / Cours de référence × 100
```

**ROE :**

``` text
ROE = Résultat net / Capitaux propres moyens × 100
```

La période, les unités, les conventions et les données sources doivent
être documentées. Les formules peuvent nécessiter des adaptations selon
la disponibilité des états financiers et les spécificités sectorielles.

### Portefeuille virtuel

Le simulateur doit notamment :

-   Distinguer les transactions virtuelles des opérations réelles.
-   Vérifier les liquidités disponibles avant un achat.
-   Empêcher la vente d'une quantité supérieure à la position détenue.
-   Prendre en compte les frais configurés.
-   Conserver l'historique des transactions.
-   Distinguer les plus-values réalisées des plus-values latentes.
-   Utiliser un cours daté pour la valorisation.
-   Documenter la méthode de calcul du coût de revient.

Les règles de calcul doivent être testées avec des scénarios métier
reproductibles.

------------------------------------------------------------------------

## 🧪 Tests et qualité

La qualité des calculs financiers est prioritaire.

### Tests backend

-   Tests unitaires des services métier.
-   Tests des calculs de ratios.
-   Tests du prix moyen pondéré.
-   Tests des achats, ventes et frais.
-   Tests de validation des imports.
-   Tests d'intégration avec PostgreSQL.
-   Tests des contrôles d'accès.

### Tests frontend

-   Tests des composants essentiels.
-   Tests des formulaires.
-   Tests des états de chargement et d'erreur.
-   Tests des parcours principaux.

### Scénario minimal du simulateur

1.  Acheter 10 actions à 5 000 FCFA.
2.  Acheter 5 actions à 6 000 FCFA.
3.  Vérifier le prix moyen pondéré : 5 333,33 FCFA, hors frais.
4.  Vendre 5 actions.
5.  Vérifier la quantité restante et la plus-value réalisée selon la
    méthode retenue.
6.  Vérifier la valorisation des positions restantes.
7.  Vérifier les frais et les liquidités.

### Qualité attendue

-   Code lisible et documenté lorsque nécessaire.
-   Règles métier séparées des contrôleurs et de l'interface.
-   Migrations de base de données versionnées.
-   Tests automatisés sur les règles financières.
-   Aucune donnée sensible dans le dépôt.
-   Pipeline CI exécutant au minimum la compilation et les tests.

------------------------------------------------------------------------

## 🗺️ Roadmap

La roadmap indicative du MVP est organisée en jalons.

  Jalon   Objectif                                     Durée indicative
  ------- ------------------------------------------ ------------------
  M0      Cadrage produit et backlog                        Préparation
  M1      Fondations techniques et architecture               1 semaine
  M2      Import et API Market Data                           1 semaine
  M3      Dashboard et Market Watch                           1 semaine
  M4      Company Explorer et analyse fondamentale            1 semaine
  M5      Portfolio Simulator                                 1 semaine
  M6      BRVM Academy                                        1 semaine
  M7      Dividend Tracker et Investment Journal              1 semaine
  M8      Tests, stabilisation et déploiement                 1 semaine
  M9      Validation par usage personnel                     4 semaines

Chaque jalon doit produire un résultat vérifiable et satisfaire ses
critères de sortie avant de débloquer le suivant.

### Priorités après le MVP

-   Améliorer la qualité et l'automatisation des données.
-   Enrichir le suivi des dividendes.
-   Développer l'assistant pédagogique IA.
-   Étudier une éventuelle application mobile.
-   Évaluer les besoins des autres investisseurs avant toute ouverture
    publique.

------------------------------------------------------------------------

## 🔒 Sécurité et limites

BRVM Intelligence est initialement un outil personnel d'apprentissage,
d'analyse et de simulation.

Le projet :

-   Ne détient pas de fonds.
-   Ne reçoit pas d'argent pour investir.
-   Ne passe pas d'ordres de Bourse.
-   Ne remplace pas une SGI.
-   Ne garantit aucun rendement.
-   Ne fournit pas de recommandation personnalisée d'achat ou de vente.

Toute évolution vers l'exécution d'ordres, la gestion de fonds, le
conseil en investissement ou la distribution de services financiers
devra faire l'objet d'une analyse réglementaire préalable et, si
nécessaire, d'autorisations appropriées auprès des autorités
compétentes.

------------------------------------------------------------------------

## 🤝 Contribution

Le projet commence comme un projet personnel. Les contributions externes
sont examinées par le mainteneur.

-   [CONTRIBUTING.md](CONTRIBUTING.md) : proposer un correctif ou une
    évolution.
-   [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) : règles de la communauté.
-   [SECURITY.md](SECURITY.md) : signaler une vulnérabilité en privé.
-   [CHANGELOG.md](CHANGELOG.md) : journal des modifications.

Les modèles d'issue et de pull request sont dans `.github/`.

------------------------------------------------------------------------

## 📄 Licence

Copyright (c) 2026 Saïfoulaye Diallo. Tous droits réservés.

Le code et la documentation de ce dépôt ne peuvent pas être réutilisés,
modifiés ou redistribués sans autorisation écrite préalable. Le texte
complet figure dans [LICENSE.md](LICENSE.md).

------------------------------------------------------------------------

## 🔗 Sources utiles

-   [BRVM --- Bourse Régionale des Valeurs
    Mobilières](https://www.brvm.org/)
-   [BRVM --- Bulletins officiels de la
    cote](https://www.brvm.org/fr/bulletins-officiels-de-la-cote)
-   [BRVM --- Données de fin de
    journée](https://www.brvm.org/fr/donnees-de-fin-de-journee)
-   [BCEAO --- Banque Centrale des États de l'Afrique de
    l'Ouest](https://www.bceao.int/)
-   [AMF-UMOA --- Autorité des marchés financiers de
    l'UMOA](https://www.amf-umoa.org/)

------------------------------------------------------------------------

## 📌 Note finale

BRVM Intelligence doit rester simple, pédagogique et fiable.

La priorité n'est pas de multiplier les fonctionnalités, mais de
construire une chaîne cohérente :

**Comprendre le marché → consulter les données → analyser les
entreprises → simuler les investissements → suivre et apprendre.**

La fiabilité des données, la transparence des calculs et la qualité de
l'expérience d'apprentissage guideront les décisions produit et
techniques.
