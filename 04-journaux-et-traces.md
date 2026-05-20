# 04 — Journaux et traces

Ce document standardise les formats de journaux et de traces afin de rendre l'écosystème IRIS∞ plus cohérent et plus auditable.

## 1. Objectif

Les journaux servent à :

- conserver la mémoire de session,
- rendre les hypothèses révisables,
- tracer les révisions,
- détecter les récurrences,
- améliorer la calibration dans le temps.

## 2. Règles communes

- Format recommandé : Markdown simple
- Entrées délimitées par un bloc visible
- Date obligatoire
- Champ de statut recommandé
- Champ d'action ou de révision recommandé

## 3. Nomenclature recommandée

| Type | Nom recommandé |
|------|----------------|
| Journal spécifique à un skill | `journal-[nom-skill].md` |
| Journal de transformation | `journal-transformation.md` |
| Journal symbolique | `journal-stele.md` |
| Log probabiliste / calibration | `calibration-log.md` |
| Contexte d'entrée | `contexte-session.md` |

## 4. Gabarit universel minimal

```md
=== ENTREE ===
Date : [DATE]
Skill : [NOM]
Contexte : [résumé court]
Sortie : [résumé court]
Statut : [descriptif / spéculatif / performatif / conclusion provisoire]
Action ou révision : [optionnel]
================
```

## 5. Règle de compatibilité

Un skill peut enrichir ce format, mais il ne devrait pas le contredire.
