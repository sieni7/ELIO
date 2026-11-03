# ROADMAP DES CYCLES DE DÉCISION — ELIO

**Fichier :** `00_ROADMAP_CYCLES.md`  
**Version :** 0.1  
**Statut :** Validé par le responsable du projet  
**Emplacement :** `02-docs/decisions/`  
**Objet :** Organiser les cycles de réflexion, d'arbitrage, de documentation et de vérification du projet ELIO.

---

## 1. Objet et principes de gouvernance

Ce document constitue le tableau de pilotage des cycles de décision du projet ELIO.

Il permet de :
- structurer les sujets à examiner avant leur mise en œuvre ;
- conserver une vision globale de l'évolution du projet ;
- distinguer les orientations proposées des décisions effectivement validées ;
- identifier les dépendances entre les différents sujets ;
- assurer la traçabilité des arbitrages et de leurs évolutions.

### Principes directeurs

1. **Validation explicite :** aucun arbitrage n'est considéré comme validé sans approbation explicite du responsable du projet.
2. **Traçabilité :** toute décision importante validée doit être documentée et pouvoir être retrouvée.
3. **Réversibilité :** une décision antérieure peut être réexaminée si de nouveaux éléments le justifient. Son historique doit être conservé.
4. **Protection du corpus :** les documents de référence déjà validés ne sont pas modifiés sans approbation explicite.
5. **Cohérence globale :** les décisions doivent rester cohérentes avec les objectifs pédagogiques, les contraintes opérationnelles et les capacités réelles des plateformes utilisées.
6. **Évolution maîtrisée :** la roadmap peut évoluer, mais toute modification de son organisation doit être explicitement arbitrée.

---

## 2. Vue d'ensemble des cycles

La roadmap comprend huit cycles numérotés de 0 à 7.

| Cycle | Intitulé | Finalité |
|---|---|---|
| 0 | Onboarding et vulgarisation | Rendre ELIO accessible aux utilisateurs non techniques |
| 1 | Arbitrage documentaire | Stabiliser les documents de référence, les instructions et leur organisation |
| 2 | Fiabilisation pédagogique | Garantir la cohérence et la qualité de l'accompagnement pédagogique |
| 3 | Fiabilité et maîtrise des erreurs de l'IA | Maîtriser les hallucinations, les incertitudes et les réponses incorrectes |
| 4 | Continuité et mémoire | Définir la persistance, la reprise et la transmission de l'état de travail |
| 5 | Sécurité, qualité et cadre légal | Protéger les utilisateurs et encadrer les risques |
| 6 | Mesure d'impact pédagogique | Évaluer les progrès réels et l'utilité d'ELIO |
| 7 | Validation multiplateforme | Vérifier la portabilité et les limites des différentes plateformes |

### État initial du pilotage

Les huit périmètres de cycle ont été examinés et validés par le responsable du projet.

Cette validation porte sur les sujets à traiter et les objectifs poursuivis. Elle ne signifie pas que les arbitrages internes, les livrables ou les tests sont déjà réalisés.

Le statut d'avancement opérationnel de chaque cycle doit donc être suivi séparément.

---

## 3. Définition détaillée des cycles

### Cycle 0 — Onboarding et vulgarisation

**Question centrale :** Comment permettre à un parent ou à un enseignant non technicien de comprendre, installer et utiliser ELIO ?

**Travaux à examiner :**
- guide de création et de configuration du projet ;
- procédure d'intégration des documents de référence ;
- paramétrage des instructions ;
- première interaction avec ELIO ;
- guide de prise en main et exemples d'utilisation ;
- limites et précautions à expliquer aux utilisateurs ;
- autonomie de l'utilisateur dans l'utilisation courante.

**Livrables envisagés :**
- guide de démarrage ;
- guide d'utilisation ;
- parcours de première prise en main.

**Emplacements possibles :**
- `02-docs/guides/`
- `03-landing/`

**Principe directeur :** l'utilisateur doit pouvoir comprendre, configurer et utiliser ELIO sans connaissances techniques particulières.

Le guide devra rester actualisable en fonction des évolutions des interfaces et des plateformes.

### Cycle 1 — Arbitrage documentaire

**Question centrale :** Quels documents constituent la référence officielle d'ELIO et comment garantir leur cohérence ?

**Travaux à examiner :**
- organisation des documents ;
- rôle respectif des instructions du projet et des fichiers de référence ;
- hiérarchie documentaire en cas de contradiction ;
- versionnement et validation ;
- règles de modification et de maintenance ;
- distinction entre documents de référence, documents opérationnels et documents de pilotage.

**Livrables envisagés :**
- corpus documentaire validé ;
- règles de gouvernance documentaire ;
- structure documentaire stabilisée.

**Emplacement principal :** `01-project/`

**Principe directeur :** tous les fichiers du dépôt ne possèdent pas nécessairement le même statut ni la même autorité. Leur hiérarchie et leur fonction doivent être explicites.

### Cycle 2 — Fiabilisation pédagogique

**Question centrale :** Comment garantir que les réponses et les interventions d'ELIO respectent la démarche pédagogique retenue ?

**Travaux à examiner :**
- enseignement explicite ;
- remédiation et progression ;
- adaptation au niveau de l'élève ;
- vérification des acquis ;
- distinction entre réussite accompagnée et autonomie ;
- cohérence des exercices, consignes et évaluations.

**Livrables envisagés :**
- règles pédagogiques consolidées ;
- scénarios pédagogiques de référence ;
- critères de validation pédagogique.

**Emplacements possibles :**
- `01-project/`
- `06-qa/`

**Principe directeur :** ELIO ne doit pas confondre réussite accompagnée et apprentissage effectif.

L'évaluation doit permettre de distinguer :
- ce que l'élève sait déjà faire ;
- ce qu'il réussit avec l'aide d'ELIO ;
- ce qu'il parvient ensuite à réaliser seul ;
- ce qui nécessite encore une remédiation.

### Cycle 3 — Fiabilité et maîtrise des erreurs de l'IA

**Question centrale :** Comment prévenir, détecter et traiter les réponses erronées ou insuffisamment fondées d'ELIO ?

**Travaux à examiner :**
- ancrage des réponses dans les documents de référence ;
- reconnaissance et expression de l'incertitude ;
- vérification des calculs et des raisonnements ;
- traitement des questions ambiguës ;
- résistance aux fausses prémisses et aux sollicitations trompeuses ;
- comportement en cas d'information absente ou contradictoire.

**Livrables envisagés :**
- protocole de fiabilité ;
- scénarios de tests de robustesse ;
- résultats et critères d'acceptation ;
- règles de signalement et de correction des erreurs.

**Emplacement principal :** `06-qa/`

**Principe directeur :** ELIO ne doit pas présenter comme certaine une réponse insuffisamment vérifiée, ni prétendre avoir consulté une source qu'il n'a pas effectivement pu consulter.

Deux catégories d'erreurs seront notamment examinées :

1. **Erreurs factuelles ou pédagogiques :** calcul incorrect, règle inventée, contenu contraire aux références.
2. **Erreurs de comportement :** certitude injustifiée, invention d'une source, réponse malgré une information insuffisante ou abandon des consignes.

Les tests devront être reproductibles et accompagnés de critères d'acceptation.

### Cycle 4 — Continuité et mémoire

**Question centrale :** Comment garantir la continuité du travail d'ELIO entre les conversations, les sessions, les agents et les plateformes ?

**Travaux à examiner :**
- carnet de bord manuel ;
- rôle et limites de `state.md` ;
- pertinence d'un état structuré `state.json` ou `agent_state.json` ;
- complémentarité entre état lisible par l'humain et état exploitable par les agents ;
- source de vérité et gestion des divergences ;
- synchronisation et versionnement ;
- reprise du travail ;
- portabilité de l'état.

**Livrables envisagés :**
- décision d'architecture sur la mémoire ;
- schéma de données éventuel ;
- protocole de mise à jour et de reprise.

**Emplacements possibles :**
- `02-docs/architecture/`
- `02-docs/decisions/`

**Principe directeur :** la mémoire doit répondre à trois besoins complémentaires :

1. **Mémoire humaine :** permettre au responsable du projet de comprendre rapidement l'état du travail.
2. **Mémoire opérationnelle :** permettre à un agent de reprendre le travail sans perdre les décisions, les tâches et les contraintes.
3. **Mémoire interplateforme :** permettre le transfert du contexte vers une autre plateforme sans dépendre exclusivement d'un mécanisme propriétaire.

Le couple `state.md` + `state.json` (ou `agent_state.json`) constitue une hypothèse architecturale à examiner. Il ne doit pas être considéré comme définitivement adopté avant l'arbitrage du cycle.

### Cycle 5 — Sécurité, qualité et cadre légal

**Question centrale :** Quelles garanties sont nécessaires pour utiliser ELIO dans un contexte impliquant des enfants ?

**Travaux à examiner :**
- protection des mineurs ;
- protection des données personnelles ;
- cadre juridique ivoirien, notamment la loi n° 2013-450 du 19 juin 2013 relative à la protection des données à caractère personnel ;
- autres cadres juridiques éventuellement applicables selon les utilisateurs, les plateformes et les lieux de traitement ;
- information et consentement des responsables légaux ;
- conservation, accès et suppression des données ;
- sécurité des échanges ;
- limites d'utilisation et gestion des situations sensibles ;
- assurance qualité globale.

**Livrables envisagés :**
- cadre de sécurité et de confidentialité ;
- règles de gestion des données ;
- protocole de contrôle qualité ;
- registre des risques et mesures de réduction.

**Emplacements possibles :**
- `07-admin/privacy/`
- `07-admin/legal/`
- `06-qa/`

**Principe directeur :** la conformité juridique, la sécurité technique et la protection pédagogique de l'enfant sont trois dimensions complémentaires, mais distinctes.

Le RGPD européen ne doit pas être présenté comme la législation ivoirienne. Son applicabilité éventuelle devra être examinée selon le contexte réel des traitements.

Aucune conformité juridique ne sera présumée sans analyse appropriée.

### Cycle 6 — Mesure d'impact pédagogique

**Question centrale :** Comment démontrer qu'ELIO contribue réellement aux apprentissages ?

**Travaux à examiner :**
- définition d'indicateurs pédagogiques ;
- mesure initiale des acquis ;
- évaluation après apprentissage ;
- mesure différée de la rétention ;
- évaluation de l'autonomie ;
- évaluation du transfert ;
- protocole d'expérimentation ;
- conditions éthiques des tests impliquant des enfants ;
- exploitation des retours des enseignants et des familles.

**Livrables envisagés :**
- protocole de mesure d'impact ;
- indicateurs et critères d'évaluation ;
- grille de suivi ;
- rapport d'expérimentation.

**Emplacements possibles :**
- `07-admin/roadmap/`
- `06-qa/results/`

#### Les quatre niveaux de résultats pédagogiques

L'évaluation des apprentissages reposera sur quatre niveaux complémentaires.

**Niveau 1 — Acquisition (immédiateté)**

L'élève réussit l'exercice à la fin de la séance avec l'accompagnement d'ELIO.

Indicateur : pourcentage d'élèves ayant réussi l'évaluation immédiate.

**Niveau 2 — Rétention (mémoire)**

L'élève réussit un exercice similaire quelques jours plus tard.

Indicateur : pourcentage d'élèves ayant réussi l'évaluation différée.

**Niveau 3 — Autonomie (indépendance)**

L'élève réussit sans assistance d'ELIO, par exemple sur son cahier, son ardoise ou face à son enseignant.

Indicateur : pourcentage d'élèves ayant réussi sans assistance.

**Niveau 4 — Transfert (généralisation)**

L'élève réutilise la notion apprise dans un contexte différent ou une situation nouvelle.

Indicateur : pourcentage d'élèves ayant correctement mobilisé la notion dans une situation nouvelle.

#### Précautions méthodologiques

- La rétention ne doit pas être confondue avec l'autonomie.
- L'évaluation de l'autonomie doit se dérouler sans assistance d'ELIO, sans correction préalable ni indice révélant directement la méthode attendue.
- Le transfert doit changer le contexte, sans nécessairement augmenter la difficulté.
- Les résultats doivent préciser le nombre d'élèves effectivement évalués à chaque niveau.
- Une progression constatée après utilisation d'ELIO ne prouve pas automatiquement qu'ELIO en est seul responsable.

**Principe directeur :** l'évaluation ne doit pas seulement mesurer la réussite immédiate de l'élève, mais également sa capacité à conserver, mobiliser et réutiliser ses acquis de manière autonome.

Les quatre niveaux constituent une grille commune d'évaluation des apprentissages, réutilisable dans les différentes disciplines. Ils ne doivent pas être automatiquement transformés en une note globale.

### Cycle 7 — Validation multiplateforme

**Question centrale :** Dans quelle mesure ELIO peut-il être reproduit et fonctionner de manière cohérente sur différentes plateformes d'IA ?

La validation multiplateforme sera progressive, en fonction de la maturité du produit.

#### Phase 1 — Version actuelle

**Périmètre :** fichiers de contexte et modèles courants de LLM accessibles par interface conversationnelle dans un navigateur.

**Travaux à examiner :**
- portabilité des instructions ;
- compatibilité documentaire ;
- capacité à recevoir et exploiter les fichiers de contexte ;
- limites de nombre, de taille et de format des fichiers ;
- stabilité des règles pédagogiques ;
- différences de comportement entre modèles ;
- fiabilité et sécurité des réponses ;
- continuité du travail et transfert du contexte.

**Livrables envisagés :**
- protocole de validation multiplateforme ;
- première matrice de compatibilité ;
- résultats comparatifs ;
- registre des limites et adaptations nécessaires.

#### Phase 2 — Développement de l'application MVP

Le périmètre pourra être progressivement étendu pendant le développement de l'application :

- augmentation du nombre de modèles et de plateformes ;
- intégration éventuelle par API ;
- gestion centralisée du contexte et de la mémoire ;
- tests d'équivalence fonctionnelle ;
- validation des mécanismes propres à l'application.

**Livrables envisagés :**
- matrice de compatibilité étendue ;
- résultats comparatifs ;
- recommandations de déploiement ;
- protocole de validation de l'application.

**Emplacement principal :** `06-qa/`

**Principe directeur :**

La validation multiplateforme est progressive. Dans sa version actuelle, ELIO est évalué sur les modèles courants de LLM accessibles par navigateur et utilisant des fichiers de contexte. Le périmètre des plateformes et des modèles pourra être étendu pendant le développement de l'application MVP.

La compatibilité documentaire ne garantit pas l'équivalence pédagogique. Chaque modèle devra être évalué sur les comportements réellement attendus.

---

## 4. Dépendances entre les cycles

Les cycles suivent un ordre de travail recommandé. Ils ne constituent pas nécessairement une succession strictement linéaire : certains travaux peuvent être préparés en parallèle, sans anticiper les arbitrages dont ils dépendent.

Dépendances structurantes :

- **Cycle 0 :** s'appuie sur les décisions documentaires et pédagogiques pour produire des guides cohérents.
- **Cycle 1 :** fournit le socle documentaire des autres cycles.
- **Cycle 2 :** constitue la référence pédagogique du Cycle 3.
- **Cycle 3 :** s'appuie sur les exigences pédagogiques et documentaires pour définir les tests de fiabilité.
- **Cycle 4 :** doit prendre en compte les besoins de continuité et les contraintes des plateformes.
- **Cycle 5 :** ses garanties doivent être établies avant les expérimentations impliquant des enfants.
- **Cycle 6 :** s'appuie sur les critères pédagogiques, les protocoles de qualité et les garanties de sécurité.
- **Cycle 7 :** vérifie la reproductibilité des décisions et des comportements sur plusieurs plateformes.

---

## 5. Statuts et règles de progression

Chaque cycle suit, autant que possible, les statuts suivants :

| Statut | Signification |
|---|---|
| À planifier | Le cycle est identifié mais son examen n'a pas commencé |
| À débattre | Le sujet est ouvert à la discussion |
| En arbitrage | Les options sont examinées et une décision est attendue |
| Validé | Les arbitrages du cycle ont été explicitement approuvés |
| Documenté | Les décisions et leurs modalités sont consignées |
| Vérifié | Les dispositions ont été testées ou leur mise en œuvre contrôlée |

### Distinction entre validation du périmètre et avancement du cycle

La validation du périmètre confirme que les objectifs, les sujets à examiner et les livrables envisagés sont acceptés.

Elle ne signifie pas que :
- les options techniques ont été arbitrées ;
- les décisions d'architecture ont été prises ;
- les livrables ont été produits ;
- les dispositions ont été testées.

Un cycle peut comporter plusieurs décisions distinctes. Son statut global doit refléter son avancement réel et ne doit pas masquer les arbitrages encore ouverts.

---

## 6. Gestion des décisions d'architecture (ADR)

Les décisions d'architecture importantes peuvent faire l'objet de documents ADR indépendants, conservés dans `02-docs/decisions/`.

Chaque ADR devrait comporter :
- un identifiant et un titre ;
- le cycle auquel il se rattache ;
- le contexte et le problème à résoudre ;
- les options examinées ;
- les avantages, limites et risques de chaque option ;
- la décision retenue et sa justification ;
- les conséquences opérationnelles ;
- le statut et la date de validation ;
- les éventuelles conditions de réexamen.

La roadmap référence ces ADR sans se substituer à eux.

Une décision ne doit pas être considérée comme adoptée simplement parce qu'elle figure dans une proposition ou dans un document de travail.

---

## 7. Historique des évolutions

| Version | Évolution |
|---|---|
| 0.1 | Première version consolidée : huit cycles numérotés de 0 à 7, suppression des suffixes « bis », définition des périmètres, des dépendances et des règles de gouvernance. Intégration des quatre niveaux d'impact pédagogique et de l'approche progressive de validation multiplateforme. |

---

## 8. Règle de clôture

Aucun cycle ne doit être considéré comme achevé sur la seule base d'une discussion.

La validation des arbitrages, leur documentation et, lorsque nécessaire, leur vérification constituent des étapes distinctes.

La roadmap est un outil de pilotage évolutif. Elle conserve la mémoire des décisions, de leurs justifications et de leurs éventuelles révisions.