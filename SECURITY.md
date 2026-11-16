# Politique de sécurité

BRVM Intelligence est un outil d'apprentissage, d'analyse et de
simulation. Le projet ne détient pas de fonds, ne reçoit pas d'argent à
investir et ne passe pas d'ordres de Bourse.

## Versions concernées

Aucune version stable n'est publiée. Le dépôt est au stade du cadrage et
du MVP. Un signalement concerne le code et la configuration présents
sur la branche principale, ainsi que toute version identifiée par une
étiquette Git une fois des publications existantes.

## Signaler une vulnérabilité

Ne pas ouvrir d'issue publique, ne pas en discuter dans une pull request
et ne pas publier de démonstration exploitable.

Utiliser le signalement privé de la forge, si elle le propose
(sur GitHub : Security → Report a vulnerability). À défaut, envoyer un
message privé au mainteneur, Saïfoulaye Diallo.

Inclure, lorsque c'est possible :

- une description du problème et de son impact ;
- le composant concerné (`apps/backend`, `apps/frontend`,
  infrastructure, configuration) ;
- la version, la branche ou le commit ;
- les étapes nécessaires pour reproduire le problème, sans code
  d'exploitation inutile ;
- toute piste de correction déjà identifiée.

Le mainteneur accuse réception dès que possible, puis indique si le
signalement est accepté, s'il faut un complément, ou s'il est hors
périmètre. Merci de laisser un délai raisonnable avant toute divulgation.

## Dans le périmètre

- Authentification, sessions et contrôle d'accès.
- Exposition de données personnelles ou de secrets.
- Injection, falsification de requêtes et accès non autorisé aux API.
- Configuration Docker, variables d'environnement et pipeline d'intégration.
- Calculs financiers qui affichent un résultat trompeur à partir de
  données pourtant valides.

## Hors périmètre

- Exactitude, fraîcheur ou disponibilité des données publiées par la
  BRVM, la BCEAO, l'AMF-UMOA ou une autre source tierce.
- Contenu pédagogique interprété comme un conseil en investissement.
- Absence de rendement, de cotation en temps réel ou d'exécution d'ordres.
- Problèmes relevant uniquement d'une dépendance tierce, sans impact
  démontré sur ce projet. Les signaler d'abord au projet concerné.

## Bonnes pratiques pour les contributions

- Ne jamais committer de secret, de jeton, de fichier `.env` ou de donnée
  personnelle.
- Ne pas désactiver un contrôle d'authentification pour « faire passer »
  un test.
- Signaler une dépendance vulnérable connue plutôt que d'élargir sa
  surface dans le produit.
