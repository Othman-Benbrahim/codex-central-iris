---
name: codex-central-iris
description: Référentiel transversal de l'écosystème IRIS∞. Utiliser quand un skill ou un agent a besoin de conventions communes, de garde-fous universels, de statuts épistémiques partagés, d'une carte de l'écosystème ou d'une règle de nommage documentaire. Ne pas utiliser pour remplacer les protocoles métier d'un skill spécialisé. Utiliser aussi quand il faut harmoniser plusieurs skills sans les fusionner.
description: Référentiel transversal de l'écosystème IRIS∞. Utiliser quand un skill ou un agent a besoin de conventions communes, de garde-fous universels, de statuts épistémiques partagés, d'une carte de l'écosystème ou d'une règle de nommage documentaire. Ne pas utiliser pour remplacer les protocoles métier d'un skill spécialisé. Utiliser aussi quand il faut harmoniser plusieurs skills sans les fusionner.
---

# Codex Central IRIS∞

Le Codex Central IRIS∞ est un **socle documentaire partagé**. Il ne remplace aucun skill métier et n'exécute aucun protocole spécialisé à la place d'un autre skill. Son rôle est de fournir un cadre commun, léger et stable, en cohérence avec les bonnes pratiques des Agent Skills : `SKILL.md` concis, documentation séparée, et chargement progressif des ressources selon le besoin.[cite:36][cite:46]

## Quand l'utiliser

Utiliser ce skill quand il faut :

- clarifier une convention commune à plusieurs skills,
- vérifier un garde-fou transversal,
- harmoniser les statuts épistémiques,
- choisir une nomenclature commune,
- comprendre la place d'un skill dans l'écosystème,
- documenter ou faire évoluer l'architecture globale de l'ensemble.

## Quand ne pas l'utiliser

Ne pas utiliser ce skill pour :

- remplacer le `SKILL.md` d'un skill métier,
- produire une lecture symbolique,
- réaliser une analyse introspective,
- faire une mise à jour bayésienne,
- orchestrer automatiquement les autres skills,
- rediriger systématiquement toute demande vers un document central.

## Procédure d'usage

1. Identifier si la demande porte sur un **élément transversal** ou sur un **protocole métier**.
2. Si la demande est transversale, lire uniquement le fichier du Codex pertinent.
3. Si la demande est métier, s'arrêter et laisser le skill spécialisé traiter la demande.
4. Si plusieurs skills doivent être harmonisés, utiliser le Codex comme référence commune sans écraser leurs logiques propres.

## Fichiers de référence

| Fichier | Usage |
|---------|-------|
| `README.md` | Vision d'ensemble du Codex et règle d'usage |
| `00-carte-ecosysteme.md` | Comprendre les familles de skills et leur rôle |
| `01-conventions.md` | Nommage, structure minimale, règles transversales |
| `02-statuts-epistemiques.md` | Lexique partagé des niveaux de vérité et d'interprétation |
| `03-garde-fous-universels.md` | Limites, prudence, non-nuisance |
| `04-journaux-et-traces.md` | Formats communs de logs et journaux |
| `05-matrice-des-skills.md` | Orientation non rigide entre besoins et skills |
| `06-principes-de-style.md` | Cohérence de ton et de formulation |
| `07-roadmap-codex.md` | Gouvernance et évolutions prévues |

## Règles internes

- Toujours préserver l'autonomie opérationnelle des skills.
- Toujours distinguer cadre commun et logique métier.
- Toujours privilégier la lisibilité à la centralisation excessive.
- Ne déplacer vers le Codex que ce qui est réellement transversal, stable et réutilisable.

## Sortie attendue

Quand le Codex est pertinent, la sortie doit idéalement préciser :

- l'élément transversal concerné,
- le fichier de référence pertinent,
- la règle commune applicable,
- ce qui doit rester local au skill concerné.
