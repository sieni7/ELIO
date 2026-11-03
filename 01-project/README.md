# ELIO — Assistant pédagogique pour le primaire en Côte d’Ivoire

**ELIO** est un projet d’assistant pédagogique fondé sur l’intelligence artificielle, conçu pour accompagner les apprentissages des élèves du **CM1 et du CM2** en Côte d’Ivoire.

Sa mission est d’aider les élèves à mieux **lire, écrire et calculer**, en s’appuyant sur le cadre pédagogique national, les programmes scolaires et une démarche d’enseignement explicite.

> **ELIO accompagne l’apprentissage. Il ne fait pas le travail à la place de l’élève.**

---

## 1. Pourquoi ELIO ?

Les élèves ont besoin d’un accompagnement régulier pour consolider leurs apprentissages. Les parents ne disposent pas toujours des repères nécessaires pour les aider, tandis que les enseignants doivent composer avec des classes nombreuses et des besoins individuels variés.

ELIO explore une autre manière de mobiliser l’intelligence artificielle : non pas comme une machine à fournir des réponses, mais comme un outil d'accompagnement qui explique, guide, fait pratiquer et aide à identifier les difficultés.

Le projet vise à rendre cette forme d’accompagnement pédagogique plus accessible.

## 2. Principes pédagogiques

ELIO s’appuie notamment sur :

- le PNAPAS et l’Approche par Compétences (APC) Recadrée ;
- les programmes éducatifs de CM1 et CM2 disponibles dans le corpus documentaire ;
- l’enseignement explicite ;
- la vérification progressive de la maîtrise ;
- la remédiation des prérequis non maîtrisés.

### La démarche d’apprentissage

Chaque apprentissage avec l’élève suit trois étapes :

1. **JE FAIS** — ELIO présente et explique un modèle.
2. **NOUS FAISONS** — l’élève s’exerce avec un accompagnement.
3. **TU FAIS** — l’élève réalise un exercice de manière autonome.

Une réussite obtenue avec de l’aide ne suffit pas à conclure que la compétence est maîtrisée. ELIO doit vérifier que l’élève peut réussir seul un exercice comparable.

## 3. Architecture documentaire

Le fonctionnement d’ELIO repose sur un ensemble de documents de référence complémentaires.

| Fichier | Fonction |
|---|---|
| `00_PROMPT_MAITRE_ELIO.md` | Identité, mission et règles de comportement d’ELIO |
| `01_CADRE_REGLEMENTAIRE_PNAPAS_APC.md` | Cadre pédagogique et réglementaire |
| `02_PROGRAMMES_OFFICIELS_CM1_CM2.md` | Références relatives aux programmes des deux niveaux |
| `03_FICHES_EXECUTION_CM1_CM2.md` | Modèles et fiches d’exécution pédagogique |
| `04_CADRE_PILOTE_ET_RETOURS_ENSEIGNANTS.md` | Organisation du pilote, retours et gouvernance |

Le fichier `INSTRUCTIONS` est distinct de ces documents : il contient les consignes courtes à renseigner dans le champ **Instructions** de la plateforme qui héberge le projet ELIO.

**Important :** le corpus documentaire validé comporte cinq documents. La copie locale présentée au moment de la rédaction de ce README montre les quatre premiers ; le document `04` reste à intégrer ou à localiser dans le dépôt.

## 4. Fonctionnement technique actuel

ELIO utilise une approche de spécialisation d’un modèle de langage existant par :

- des instructions spécifiques ;
- un corpus documentaire de référence ;
- une organisation cohérente des sources ;
- des scénarios de test et des retours d’utilisation.

Le projet peut être expérimenté sur différentes plateformes proposant des espaces de projets ou des mécanismes équivalents d’injection de contexte.

Les fonctionnalités disponibles dépendent de la plateforme utilisée. ELIO ne doit pas être présenté comme disposant d’une mémoire persistante, d’un suivi automatique des élèves ou d’un système autonome de gestion des apprentissages si ces fonctions ne sont pas effectivement implémentées.

## 5. Publics concernés

ELIO s’adresse principalement à trois catégories d’utilisateurs :

- **Élèves :** accompagnement dans les apprentissages et les exercices.
- **Parents :** meilleure compréhension des difficultés et des progrès observés pendant les séances.
- **Enseignants :** outil complémentaire pour soutenir les apprentissages et expérimenter des modalités d’accompagnement.

ELIO ne remplace ni l’enseignant, ni le parent, ni les ressources pédagogiques officielles.

## 6. Statut du projet

ELIO est actuellement dans une phase de conception, de structuration documentaire et d’expérimentation pilote.

Les documents pédagogiques de référence ont fait l’objet d’un travail de révision et de validation. Le cadre du pilote précise les modalités de participation, les retours attendus, les précautions relatives aux données et les principes de gouvernance.

Les choix techniques définitifs de la future version applicative restent à établir.

## 7. Gouvernance et contributions

Le projet est porté par son fondateur et concepteur initial, qui conserve la responsabilité des orientations et des décisions structurantes jusqu’au MVP.

Les contributions sont envisagées sur une base volontaire et non rémunérée dans le cadre du pilote, selon les conditions définies par le cadre de participation.

Les contributions substantielles peuvent faire l’objet d’une mention nominative, avec l’accord des personnes concernées. Les conditions de réutilisation des contributions doivent être clarifiées avant leur intégration dans une version diffusée du projet.

Le projet s’oriente vers une stratégie de licence hybride et progressive. Aucune licence définitive n’est déclarée dans ce README.

## 8. Organisation du dépôt

Le dépôt Git a vocation à centraliser :

- les documents de référence ;
- les instructions et configurations du projet ;
- les documents de gouvernance ;
- les scénarios de test ;
- les évolutions et décisions de conception ;
- les futurs éléments techniques du MVP.

Git servira à assurer le suivi des versions, la traçabilité des modifications et la collaboration.

## 9. Évolutions envisagées

Les prochaines étapes comprennent notamment :

1. Consolidation de la structure documentaire dans le dépôt.
2. Mise en place du document de gouvernance et de participation.
3. Formalisation et exécution des scénarios de test.
4. Organisation de la collecte et de l’analyse des retours du pilote.
5. Préparation progressive d’un MVP.
6. Étude des besoins de mémoire, de suivi et de gestion structurée des sessions.

Ces éléments constituent des perspectives de travail et ne doivent pas être confondus avec des fonctionnalités déjà disponibles.

## 10. Esprit du projet

ELIO repose sur une conviction simple :

**L’intelligence artificielle doit aider l’enfant à apprendre, à réfléchir et à progresser — jamais se substituer à son effort ni à l’accompagnement humain.**

---

*ELIO — Empower Learning to Interact and Overcome.*