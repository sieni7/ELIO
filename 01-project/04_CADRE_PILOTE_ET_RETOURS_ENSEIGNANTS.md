# 04_CADRE_PILOTE_ET_RETOURS_ENSEIGNANTS.md

**Projet : ELIO — Assistant pédagogique CM1–CM2**  
**Version : 0.4 — Version consolidée pour le pilote**  
**Statut : Document de référence du pilote**

---

## 1. Pourquoi ELIO ?

Les devoirs à la maison peuvent devenir une source de tension. Des parents souhaitent aider leurs enfants, mais ne maîtrisent pas toujours les méthodes pédagogiques actuellement utilisées à l'école. Les enseignants, quant à eux, doivent accompagner des classes parfois nombreuses et ne peuvent pas toujours apporter à chaque élève toute l'attention individuelle dont il aurait besoin.

Dans ce contexte, l'intelligence artificielle suscite autant d'espoir que de méfiance. Elle peut devenir une machine à donner les réponses et à faire les devoirs à la place de l'enfant. Mais elle peut aussi être conçue comme un outil d'accompagnement de la réflexion et de l'apprentissage.

C'est cette seconde voie qu'explore ELIO.

ELIO est un assistant pédagogique expérimental destiné à accompagner les élèves de CM1 et CM2 en Côte d'Ivoire, dans le respect du PNAPAS et de l'APC Recadrée.

Son approche repose sur trois principes :

- **JE FAIS** : l'assistant explique et montre un exemple.
- **NOUS FAISONS** : l'élève s'exerce avec un accompagnement progressif.
- **TU FAIS** : l'élève réalise un exercice comparable de manière autonome.

ELIO cherche à faire progresser l'élève en Lire, Écrire et Calculer, en tenant compte de ses prérequis et en privilégiant la remédiation lorsqu'une difficulté est observée.

Il ne doit pas faire les devoirs à la place de l'enfant, se substituer à l'enseignant ou prétendre remplacer les ressources pédagogiques officielles.

Les parents peuvent mieux comprendre le travail réalisé grâce à un résumé de séance. Ce résumé ne signifie toutefois pas qu'ELIO dispose nécessairement d'une mémoire persistante ou d'un historique accessible entre les sessions.

### Une approche technologique accessible

Le premier prototype repose sur un modèle de langage (LLM), spécialisé par des instructions et un ensemble de documents de référence.

Le dispositif documentaire initial comprend quatre documents pédagogiques et comportementaux. Il est conçu pour être utilisé dans les fonctionnalités de projets proposées par différentes plateformes d'IA, notamment ChatGPT, Qwen, Grok ou Claude, sous réserve des capacités et limites propres à chacune.

Cette approche permet d'expérimenter ELIO sans construire immédiatement une application complète.

**ELIO est à ce stade un prototype expérimental.** Ses résultats doivent être observés, évalués et améliorés avant toute généralisation.

---

## 2. Objet du pilote

Le pilote vise à vérifier la pertinence pédagogique, la qualité des interactions et l'utilité pratique d'ELIO auprès d'enseignants, de parents, de relecteurs et de contributeurs volontaires.

Il doit permettre de :

1. vérifier le respect du cadre pédagogique et des documents de référence ;
2. évaluer la qualité des explications et des exercices ;
3. vérifier la capacité à détecter et traiter les difficultés ;
4. contrôler la distinction entre réussite guidée et réussite autonome ;
5. recueillir des retours d'utilisation ;
6. identifier les corrections prioritaires ;
7. préparer les décisions relatives à un futur MVP.

Le pilote ne constitue pas une validation institutionnelle du ministère de l'Éducation nationale et de l'Alphabétisation.

ELIO reste un outil complémentaire. Il ne remplace ni l'enseignant, ni le Manuel Unique, ni les programmes et ressources officielles.

---

## 3. Publics concernés et rôles

### 3.1. Fondateur

Le fondateur est à l'origine de la vision, du concept, de l'orientation pédagogique et de l'architecture documentaire initiale d'ELIO.

Il assure notamment :
- la définition de la vision et des orientations ;
- la cohérence pédagogique et fonctionnelle ;
- la validation des évolutions ;
- l'arbitrage des propositions ;
- la coordination du pilote ;
- la décision de passage éventuel au MVP.

Le fondateur demeure le responsable des décisions stratégiques et le décisionnaire final du projet, du pilote jusqu'au MVP.

### 3.2. Enseignants

Les enseignants peuvent :
- tester ELIO sur des situations pédagogiques ;
- examiner la conformité des explications et exercices ;
- signaler les erreurs ou incohérences ;
- proposer des améliorations ;
- évaluer l'utilité pratique de l'assistant.

Ils conservent leur liberté pédagogique et leur responsabilité professionnelle.

### 3.3. Parents

Les parents peuvent :
- accompagner les essais réalisés par leurs enfants ;
- observer la compréhension des explications ;
- signaler les difficultés rencontrées ;
- évaluer la clarté des résumés de séance.

Ils ne sont pas invités à transmettre des informations personnelles inutiles sur les enfants.

### 3.4. Relecteurs

Les relecteurs peuvent intervenir sur :
- la pédagogie ;
- les programmes et références officielles ;
- la qualité rédactionnelle ;
- la cohérence fonctionnelle ;
- la sécurité ;
- les aspects techniques.

Leur rôle est consultatif, sauf accord distinct.

### 3.5. Contributeurs

Les contributeurs peuvent proposer des corrections, des ressources, des exercices, des documents, des idées ou des composants techniques.

Les contributions substantielles font l'objet d'un accord spécifique avant leur intégration ou leur réutilisation dans le projet.

---

## 4. Participation volontaire et contributions

### 4.1. Principe général

La participation au pilote est volontaire et non rémunérée.

Chaque participant peut interrompre sa participation à tout moment, sans justification.

La participation au pilote ne crée pas, à elle seule, de relation de travail, de partenariat commercial, de statut de cofondateur ou de droit de décision sur le projet.

### 4.2. Deux catégories de participation

Une distinction est faite entre :

**A. Participation au pilote**

Elle comprend notamment les tests, observations, questionnaires, signalements et suggestions générales.

**B. Contribution substantielle**

Elle correspond à la production d'un élément original susceptible d'être intégré à ELIO : document, ressource pédagogique, exercice structuré, code, module ou autre création.

### 4.3. Charte générale et accord spécifique

Le projet adopte deux niveaux de formalisation :

- une **charte générale de participation**, applicable aux participants du pilote ;
- un **accord complémentaire de contribution**, applicable lorsqu'une création originale ou une contribution substantielle est destinée à être réutilisée dans ELIO.

La charte générale précise les objectifs, le caractère volontaire de la participation, les règles de respect, de confidentialité et de sécurité.

La charte pourra être publiée dans le dépôt Git du projet, comme document complémentaire de gouvernance. Elle ne constitue pas un sixième document à intégrer au Project ELIO.

L'accord complémentaire précise notamment :
- l'identification du contributeur ou son pseudonyme ;
- la description de la contribution ;
- la confirmation de sa capacité à proposer cette création ;
- les usages autorisés ;
- les possibilités d'intégration, d'adaptation et de modification ;
- les conditions de diffusion ;
- les modalités de crédit ;
- les éventuelles conditions particulières.

La transmission d'une contribution ne vaut pas automatiquement cession de droits.

Aucune création originale ne doit être intégrée au MVP sans autorisation adaptée.

### 4.4. Reconnaissance des contributions

Les contributions substantielles pourront donner lieu à une mention nominative dans les documents du projet, les crédits du MVP ou une page dédiée.

Cette mention est soumise à l'accord du contributeur.

Une reconnaissance nominative ne confère pas automatiquement un statut de cofondateur, une participation financière ou un pouvoir de décision sur ELIO.

### 4.5. Droits des contributeurs et ressources tierces

Les contributeurs conservent les droits qui leur appartiennent sur leurs créations originales, sauf accord distinct et explicite.

Les ressources provenant de tiers — notamment les documents institutionnels, programmes, manuels et supports d'éditeurs — doivent faire l'objet d'une vérification de leurs conditions d'utilisation.

Le caractère volontaire et gratuit d'une contribution ne signifie pas l'abandon des droits d'auteur.

---

## 5. Scénarios de test du pilote

Le pilote s'appuie sur une série de scénarios permettant d'évaluer les comportements essentiels d'ELIO.

### 5.1. Première série : T01 à T10

| Test | Situation évaluée |
|---|---|
| T01 | Identification du profil de l'utilisateur |
| T02 | Refus de faire les devoirs à la place de l'élève |
| T03 | Explication explicite d'une notion |
| T04 | Détection et remédiation d'un prérequis non maîtrisé |
| T05 | Vérification de la maîtrise autonome |
| T06 | Gestion de la pression exercée par l'élève |
| T07 | Qualité du retour pédagogique après une erreur |
| T08 | Respect des programmes et gestion de l'incertitude |
| T09 | Protection de l'enfant et gestion d'une situation sensible |
| T10 | Fin de séance, résumé et continuité |

### 5.2. Deuxième série : T11 à T20

Une deuxième série pourra compléter les tests initiaux, notamment sur :
- les notions absentes ou insuffisamment documentées ;
- les incertitudes relatives au CM2 ;
- les contradictions entre documents ;
- les réponses obtenues avec une aide excessive ;
- les erreurs répétées ;
- les interruptions de séance ;
- les contenus non vérifiables ;
- les interactions avec les enseignants ;
- les interactions avec les parents ;
- les limites de récupération documentaire propres aux plateformes.

Les tests supplémentaires seront définis et validés progressivement.

---

## 6. Organisation du pilote et diffusion

Le pilote privilégie une démarche progressive, en commençant par les enseignants et les personnes capables d'évaluer les réponses pédagogiques.

Les premiers relais de diffusion envisagés sont les réseaux et communautés d'enseignants, notamment les groupes professionnels sur Facebook et WhatsApp.

La participation des élèves doit être encadrée par un parent ou un enseignant.

Une page de présentation d'ELIO pourra centraliser :
- la présentation du projet ;
- les modalités de participation ;
- l'accès aux ressources de test ;
- les formulaires de retour ;
- les informations relatives à la protection des données ;
- les évolutions du projet.

La page de présentation constitue le point d'entrée du pilote. Elle ne remplace pas l'assistant ELIO lui-même.

---

## 7. Collecte des retours

### 7.1. Principe retenu : collecte simple

Le pilote adopte une collecte volontairement légère.

L'objectif n'est pas de constituer un dossier détaillé sur chaque enfant, mais de recueillir suffisamment d'informations pour identifier les problèmes, évaluer les comportements et orienter les améliorations.

Les formulaires sont destinés aux adultes participants.

### 7.2. Informations pouvant être recueillies

Les formulaires peuvent comporter :
- le profil du participant : enseignant, parent, relecteur ou contributeur ;
- le niveau concerné : CM1 ou CM2 ;
- la date du test ;
- le type de situation testée ;
- le problème observé ;
- le comportement attendu ;
- une suggestion d'amélioration ;
- une appréciation générale de l'expérience.

Un champ facultatif peut permettre de transmettre un extrait de réponse d'ELIO, à condition qu'il soit anonymisé et limité à ce qui est nécessaire.

### 7.3. Données à ne pas collecter inutilement

Le pilote ne doit pas demander :
- le nom complet d'un enfant ;
- son adresse ;
- son numéro de téléphone ;
- ses identifiants personnels ;
- des informations sensibles sans nécessité et cadre approprié ;
- des conversations complètes lorsque quelques extraits anonymisés suffisent.

Les formulaires ne doivent pas encourager la transmission de données personnelles concernant les élèves.

### 7.4. Accès aux retours

Les retours sont accessibles uniquement au fondateur et aux personnes expressément autorisées à participer à leur analyse.

Ils sont utilisés pour l'évaluation et l'amélioration du projet, conformément aux informations communiquées aux participants.

Les coordonnées d'adultes souhaitant être recontactés doivent être séparées des observations pédagogiques autant que possible.

---

## 8. Protection des enfants et sécurité

La sécurité des enfants constitue une priorité.

Les essais impliquant des élèves doivent être supervisés par un adulte responsable.

ELIO ne doit pas solliciter d'informations personnelles inutiles.

En cas de situation de danger, de détresse ou de révélation préoccupante, l'assistant doit orienter immédiatement l'enfant vers un adulte de confiance.

Les participants sont invités à éviter de transmettre des éléments permettant d'identifier un enfant dans les formulaires ou les retours.

Aucun témoignage, extrait de conversation ou résultat identifiable concernant un enfant ne doit être publié sans cadre approprié et autorisation préalable.

---

## 9. Conservation et suppression des données du pilote

### 9.1. Durée retenue

Les retours identifiables recueillis dans le cadre du pilote sont conservés pendant une durée maximale de **six mois après la clôture du pilote**.

À l'issue de cette période, ils doivent être supprimés ou rendus durablement anonymes, sous réserve des obligations légales applicables.

La date de clôture du pilote devra être formellement déterminée et communiquée.

### 9.2. Synthèses anonymisées

Les synthèses pédagogiques et statistiques réellement anonymisées pourront être conservées pour documenter les enseignements du pilote et préparer le MVP.

Il faudra vérifier que ces synthèses ne permettent pas de réidentifier indirectement un participant ou un enfant.

### 9.3. Responsabilité de la conservation

Le responsable de la collecte doit :
- limiter les accès ;
- éviter les copies non nécessaires ;
- définir les modalités de stockage ;
- organiser la suppression à échéance ;
- informer les participants des modalités applicables.

Les choix d'hébergement et d'outils de collecte devront être vérifiés avant le lancement effectif des formulaires.

---

## 10. Analyse et traitement des retours

Les observations sont classées selon quatre catégories :

| Catégorie | Nature du retour |
|---|---|
| A — Critique | Sécurité, erreur grave, non-respect majeur du cadre |
| B — Pédagogique | Erreur de contenu, explication insuffisante, remédiation inadéquate |
| C — Conversationnelle | Ton, formulation, compréhension du profil, fluidité |
| D — Amélioration souhaitée | Fonctionnalité ou évolution non indispensable au pilote |

Chaque retour peut être examiné selon :
- sa fréquence ;
- sa gravité ;
- son impact sur l'apprentissage ;
- sa reproductibilité ;
- sa faisabilité de correction.

Une suggestion ne devient pas automatiquement une modification du projet.

Le fondateur examine les retours, décide des priorités et valide les évolutions.

Les corrections importantes doivent être documentées afin de conserver une trace des décisions et des versions.

---

## 11. Gouvernance et propriété intellectuelle

### 11.1. Gouvernance du projet

Le fondateur demeure le responsable de l'orientation générale et le décisionnaire final du projet pendant le pilote et jusqu'au MVP.

Les enseignants, relecteurs et contributeurs participent à l'amélioration du projet par leurs observations et propositions.

Cette participation est précieuse, mais ne transfère pas automatiquement la responsabilité des décisions stratégiques.

### 11.2. Reconnaissance des contributions substantielles

Les contributions substantielles pourront être reconnues nominativement, sous réserve de l'accord des personnes concernées.

Les modalités de reconnaissance seront adaptées à la nature et à l'importance réelle des contributions.

### 11.3. Politique de licence hybride et progressive

ELIO adopte une politique de propriété intellectuelle hybride et progressive.

Le projet conserve la maîtrise de son identité, de son orientation stratégique, de sa gouvernance et des décisions relatives à la publication de ses composants.

L'ouverture éventuelle de certains éléments sera étudiée progressivement, composant par composant.

**Première priorité d'examen : les documents pédagogiques originaux du projet.**

Cette première étape ne signifie pas que ces documents sont déjà placés sous licence libre ou autorisés à être redistribués.

Avant toute publication, il faudra :
- identifier les auteurs et titulaires de droits ;
- distinguer les créations originales des contenus issus de sources tierces ;
- vérifier les autorisations de réutilisation ;
- choisir une licence adaptée ;
- préciser les conditions d'attribution et de réutilisation.

L'ouverture du code du futur MVP, des interfaces ou d'autres composants techniques n'est pas décidée à ce stade.

Aucune licence globale n'est considérée comme adoptée tant que l'inventaire des composants et de leurs droits n'a pas été réalisé.

---

## 12. Plateforme de collecte et choix techniques

### 12.1. Principe

La page de présentation du pilote doit servir de point d'entrée aux participants.

Les retours peuvent être recueillis au moyen de formulaires distincts ou de sections adaptées aux différents profils.

### 12.2. Solutions envisageables

Les solutions envisagées comprennent :
- GitHub pour le dépôt du code, des documents complémentaires et la gestion des versions ;
- Netlify ou Vercel pour l'hébergement de la page ;
- un outil de formulaire adapté à la collecte ;
- un espace de stockage sécurisé et à accès limité.

Le choix définitif de l'hébergement, des formulaires et du stockage n'est pas encore arrêté.

Il devra tenir compte :
- des conditions de traitement des données ;
- des possibilités d'export et de suppression ;
- des droits d'accès ;
- de la localisation et des garanties offertes par les prestataires ;
- des exigences applicables en Côte d'Ivoire.

### 12.3. Distinction entre le Project ELIO et le dépôt Git

Le Project ELIO conserve une limite de cinq documents de référence téléversés.

Le présent document constitue le cinquième document de ce Project.

La charte de participation pourra être conservée dans le dépôt Git comme document complémentaire de gouvernance. Elle ne doit pas être considérée comme un sixième document à téléverser dans le Project.

Cette organisation permet de distinguer :
- le corpus documentaire directement utilisé par l'assistant ;
- les documents de gouvernance et de fonctionnement du projet ;
- le code et les ressources techniques gérés dans le dépôt Git.

---

## 13. Points nécessitant encore une validation

Les éléments suivants restent ouverts et doivent être traités avant ou pendant le lancement du pilote.

### 13.1. Validation juridique

- Finaliser la charte de participation.
- Préparer l'accord complémentaire de contribution.
- Vérifier les conditions de réutilisation des créations originales.
- Examiner les droits applicables aux ressources institutionnelles et tierces.
- Déterminer les informations à fournir aux participants sur la collecte.
- Vérifier les obligations applicables à la protection des données personnelles en Côte d'Ivoire, notamment auprès de l'ARTCI.
- Vérifier les conditions particulières applicables aux données concernant les mineurs.
- Déterminer les licences éventuellement adaptées aux documents originaux après inventaire des droits.

### 13.2. Validation technique

- Choisir la solution d'hébergement de la page de présentation.
- Choisir l'outil de formulaire.
- Définir l'espace de stockage des retours.
- Organiser les droits d'accès.
- Prévoir la suppression effective des données à l'échéance des six mois.
- Vérifier les conditions de traitement des données par les prestataires retenus.
- Définir le mode d'export et d'archivage des synthèses anonymisées.

### 13.3. Validation opérationnelle

- Définir la date officielle de clôture du pilote.
- Désigner les personnes autorisées à consulter les retours.
- Finaliser les formulaires.
- Préparer la charte à faire accepter aux participants.
- Définir le processus de traitement des contributions substantielles.

---

## 14. Clôture du pilote et préparation du MVP

À la fin du pilote, un bilan devra présenter :
- le nombre et les profils des participants ;
- les scénarios effectivement testés ;
- les problèmes critiques détectés ;
- les améliorations pédagogiques réalisées ;
- les limites persistantes ;
- les retours des enseignants et parents ;
- les enseignements sur l'utilisation des plateformes ;
- les besoins techniques identifiés ;
- les propositions de fonctionnalités pour le MVP.

Le passage au MVP ne sera pas automatique.

Il fera l'objet d'une décision du fondateur, après examen des résultats, des risques, des besoins et des ressources disponibles.

Le MVP pourra nécessiter une architecture distincte du prototype actuel, notamment pour la gestion des sessions, la continuité pédagogique, les données et les interfaces.

Les mécanismes de mémoire persistante, de stockage structuré et de gestion d'état ne doivent pas être considérés comme déjà disponibles dans le prototype actuel.

---

## 15. Historique des versions

| Version | Évolution |
|---|---|
| 0.1 | Première structuration du cadre pilote |
| 0.2 | Consolidation de la vision, des rôles, des tests, de la gouvernance et de la politique hybride |
| 0.3 | Intégration des arbitrages : charte et accord complémentaire, collecte simple, conservation de six mois après clôture, ouverture progressive limitée à l'examen des documents pédagogiques originaux |
| 0.4 | Clarification de la séparation entre les cinq documents du Project ELIO et les documents complémentaires du dépôt Git ; intégration de la charte dans les ressources de gouvernance prévues pour Git |

---

**Fin du document — Version 0.4.**