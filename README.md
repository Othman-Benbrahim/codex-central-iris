# Codex Central IRIS∞

Le **Codex Central IRIS∞** est le dépôt de référence transversal de l'écosystème de skills IRIS∞. Il est structuré comme un vrai dossier de skill, avec un `SKILL.md` obligatoire au point d'entrée, complété par des fichiers Markdown spécialisés qui servent de documentation de référence et de cadre commun.

Cette organisation respecte la logique standard des Agent Skills : un skill est d'abord un dossier centré sur `SKILL.md`, auquel peuvent s'ajouter des ressources complémentaires comme des références, des scripts ou des documents annexes.

## Rôle du dépôt

Ce dépôt ne remplace pas les `SKILL.md` métier de chaque skill. Il définit les conventions communes, les garde-fous universels, les statuts épistémiques partagés et la cartographie générale de l'écosystème.

Le **Codex Central** joue donc un rôle de socle documentaire :

- il harmonise sans fusionner,
- il structure sans orchestrer,
- il documente sans absorber les logiques métier,
- il soutient l'écosystème sans créer de dépendance excessive.

## Principe directeur

Chaque skill reste **autonome** :

- il conserve sa logique métier,
- ses protocoles d'activation,
- ses fichiers de référence spécifiques,
- sa voix propre,
- ses gabarits de sortie.

Le Codex Central fixe seulement les **invariants communs** :

- conventions de nommage,
- formats de journaux,
- garde-fous communs,
- lexique des statuts de vérité,
- repères de navigation entre skills,
- principes de cohérence d'ensemble.

## Structure du dépôt

| Fichier | Fonction |
|---------|----------|
| `SKILL.md` | Point d'entrée opérationnel du Codex, règles d'usage et orientation vers les bons fichiers de référence |
| `README.md` | Point d'entrée humain, vision d'ensemble du Codex |
| `00-carte-ecosysteme.md` | Vue d'ensemble de l'écosystème IRIS∞ |
| `01-conventions.md` | Nommage, formats communs, règles transversales |
| `02-statuts-epistemiques.md` | Lexique partagé des niveaux de vérité et d'interprétation |
| `03-garde-fous-universels.md` | Règles de sécurité et limites communes à tous les skills |
| `04-journaux-et-traces.md` | Formats communs de logs, journaux, blocs de traçabilité |
| `05-matrice-des-skills.md` | Table d'orientation : quel skill pour quel usage |
| `06-principes-de-style.md` | Cohérence d'écriture, ton, densité, relation entre voix locale et cadre global |
| `07-roadmap-codex.md` | Évolutions prévues du Codex et gouvernance |

## Logique de lecture

Deux niveaux de lecture coexistent :

### 1. Lecture agent

Le fichier `SKILL.md` est la porte d'entrée principale pour un agent. Il décrit :

- quand le Codex doit être utilisé,
- quand il ne doit pas l'être,
- comment distinguer un besoin transversal d'un besoin métier,
- quels fichiers consulter selon le problème posé.

### 2. Lecture humaine

Le `README.md` sert à expliquer l'intention globale du dépôt, sa structure, ses objectifs et sa philosophie documentaire.

## Nomenclature retenue

La numérotation des fichiers documentaires est volontaire : elle stabilise l'ordre de lecture, facilite la maintenance, et permet d'ajouter de nouveaux modules sans casser la lisibilité de l'ensemble.

Schéma retenu :

- `00-` vue d'ensemble,
- `01-` à `06-` cadre commun,
- `07-` pilotage et évolution.

## Règle d'usage

Le Codex Central est un **socle documentaire**, pas un orchestrateur. Son `SKILL.md` oriente vers les conventions pertinentes, mais il ne doit pas absorber les protocoles détaillés de chaque skill spécialisé.

## Usage recommandé

Utiliser ce dépôt pour :

- harmoniser les skills sans les fusionner,
- réduire les duplications d'instructions transversales,
- documenter les règles communes de l'écosystème,
- préparer un futur agent de simplification sur une base stable.

Ne pas l'utiliser pour :

- remplacer un `SKILL.md` métier,
- centraliser tous les contenus spécialisés,
- créer une dépendance d'exécution systématique entre tous les skills.

## Évolution attendue

Le dépôt pourra évoluer de manière incrémentale :

- d'abord comme référentiel documentaire,
- ensuite comme base d'alignement des skills existants,
- puis comme fondation pour un éventuel agent de simplification.

Cette progression est cohérente avec les approches recommandées pour les Agent Skills : garder un point d'entrée simple, déplacer les détails dans les bons fichiers, et charger l'information seulement quand elle est utile.[cite:36][cite:46]
