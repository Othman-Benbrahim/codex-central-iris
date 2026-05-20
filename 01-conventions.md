# 01 — Conventions

Ce document définit les conventions communes de l'écosystème IRIS∞.

## 1. Nommage des fichiers

### Skills

- Nom de dépôt : kebab-case ou titre lisible selon la logique historique du skill.
- Fichier principal : `SKILL.md`
- Références internes : dossier `references/`

### Fichiers externes utilisateur

Conventions recommandées :

- `journal-*.md` pour les journaux spécifiques à un skill
- `calibration-log.md` pour les traces de calibration ou de révision
- `contexte-session.md` pour l'ancrage d'une session
- `lexique-perso.md` pour les surcouches personnelles

## 2. Structure minimale recommandée d'un skill

Chaque skill devrait idéalement contenir :

1. un frontmatter clair,
2. une mission,
3. des déclencheurs d'usage,
4. une procédure ou pipeline,
5. des garde-fous,
6. des références,
7. un format de sortie type.

## 3. Référencement croisé

Lorsqu'un skill mentionne un autre skill :

- il décrit la relation conceptuelle,
- il n'impose pas de dépendance implicite,
- il évite de déléguer sans condition,
- il reste opérable seul.

## 4. Priorité documentaire

Ordre recommandé :

1. sécurité et non-nuisance,
2. conventions globales du Codex,
3. logique métier du skill,
4. références spécialisées,
5. style de sortie.

## 5. Principe de non-duplication

Tout élément transversal répété dans plus de trois skills doit être évalué pour migration éventuelle dans le Codex Central.
