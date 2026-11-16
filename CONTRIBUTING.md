# Contribuer à BRVM Intelligence

Merci de l'intérêt porté au projet. BRVM Intelligence est, au départ, un
outil personnel d'apprentissage sur la Bourse Régionale des Valeurs
Mobilières. Les contributions externes sont examinées par le mainteneur,
Saïfoulaye Diallo.

En proposant une contribution, vous acceptez le
[code de conduite](CODE_OF_CONDUCT.md) et vous confirmez avoir le droit
de soumettre le contenu proposé. Le mainteneur peut l'intégrer au dépôt
selon les termes de [LICENSE.md](LICENSE.md).

## Avant de commencer

1. Lire le [README](README.md), en particulier le périmètre du MVP, les
   principes métier et les limites du produit.
2. Chercher si une issue décrit déjà le même sujet.
3. Ouvrir une issue avant une modification large : nouveau module,
   changement de modèle de données, ou évolution du parcours utilisateur.

Le produit ne passe pas d'ordres de Bourse et ne fournit pas de conseil
en investissement. Une contribution ne doit pas présenter un ratio, une
performance ou un texte pédagogique comme une recommandation d'achat ou
de vente.

## Signaler un problème

Utiliser le modèle d'issue « Rapport de bogue » et indiquer :

- le comportement observé et le comportement attendu ;
- les étapes de reproduction ;
- la version, la branche et l'environnement (système, Java, Node) ;
- des captures ou journaux utiles, sans secret ni donnée personnelle.

Pour une faille de sécurité, suivre [SECURITY.md](SECURITY.md). Ne pas
ouvrir d'issue publique.

## Proposer un changement

1. Créer une branche à partir de la branche principale :
   `type/sujet-court`. Types usuels : `feat`, `fix`, `docs`, `test`,
   `refactor`.
2. Limiter la pull request à un seul sujet.
3. Ajouter ou mettre à jour les tests dès que le dépôt contient une
   suite de tests.
4. Mettre à jour la documentation si le comportement visible, l'installation
   ou une règle métier change.
5. Ajouter une entrée dans [CHANGELOG.md](CHANGELOG.md), section
   « Non publié », lorsque le changement concerne les utilisateurs ou
   les personnes qui contribuent.

### Contrôles avant la revue

- Les noms de classes, méthodes et variables expliquent leur rôle.
- Les règles financières restent dans des composants métier testables.
- Les calculs de ratios ne s'exécutent que si les données requises sont
  présentes, datées et sourcées.
- Aucune donnée ancienne n'est présentée comme une cotation en temps réel.
- Le diff ne contient ni secret, ni fichier `.env`, ni donnée personnelle,
  ni export brut de données de marché dont la redistribution n'est pas
  autorisée.
- Les dépendances circulaires entre modules sont évitées.

## Environnement local

Les prérequis et le démarrage sont décrits dans le README : Java 21,
Maven, Node.js LTS, Docker et Docker Compose. Les commandes exactes
dépendent des applications réellement présentes dans `apps/backend` et
`apps/frontend`.

Ne jamais committer de secret. Partir de `.env.example` lorsqu'il existe.

## Données et contenu tiers

Les cours, indices, états financiers et documents de sociétés restent
soumis aux conditions de leurs sources. Ne pas ajouter au dépôt un jeu
de données dont la licence de réutilisation n'est pas claire. Préférer
des fixtures réduites, anonymisées et suffisantes pour les tests.

## Revue

Le mainteneur peut demander des ajustements, refuser une proposition hors
périmètre, ou reporter un sujet à un jalon ultérieur. Une pull request
sans description du problème, du comportement attendu et du plan de test
sera renvoyée pour complément.
