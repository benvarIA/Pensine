# Pensine — Specs techniques, UI/UX & fonctionnelles

> **Référentiel de projets de vie** : vider la tête, capturer et centraliser tous les projets — applications, lutherie, électronique, maison — dans un format structuré et consultable.

**Date de rédaction :** 2026-06-03
**Statut :** Phase d'initialisation (structure définie, projets à remplir)
**Format actuel :** fichiers Markdown (README.md + projets.md)
**Stack future :** à définir selon l'évolution vers une vraie app

---

## 1. Contexte & Problème

Les projets s'accumulent dans la tête sans être formalisés : fabrication d'une guitare, idée d'application, panneau solaire, réorganisation d'une pièce. Pensine est le **second cerveau** : un endroit unique pour capturer, structurer et retrouver tous ces projets, quelle que soit leur nature.

Référence à la *Pensine de Dumbledore* (Harry Potter) : un bassin où l'on dépose ses pensées pour y revenir plus tard.

---

## 2. Catégories de projets

| Catégorie | Description | Exemples |
|---|---|---|
| **Lutherie** | Fabrication, entretien, modification, customisation de guitares | Fabriquer une guitare, réglage complet, changement de micros, refrettage, custom esthétique |
| **Apps** | Applications en cours, en idée, à prototyper ou à lancer | App en dev, idée d'app, prototype rapide, outil perso, SaaS |
| **Electronique** | Bricolage, conception, réparation, amélioration de systèmes électroniques | Panneaux solaires, batteries, alimentations, capteurs, boîtiers/montages |
| **Maison** | Amélioration de l'appartement, aménagement, confort, organisation, travaux | Optimisation d'une pièce, rangement, amélioration confort, travaux esthétiques |

---

## 3. Structure d'une fiche projet

Chaque projet est documenté avec les champs suivants :

```
- Nom :
- Catégorie :
- Statut :            (Idée / En cours / En pause / Terminé / Abandonné)
- Description courte :
- Prochaine action :
- Matériel / outils nécessaires :
- Contraintes / points de vigilance :
- Notes :
```

---

## 4. Fonctionnalités actuelles (Markdown)

- `README.md` : définition des catégories + structure recommandée
- `projets.md` : liste des projets par catégorie (à remplir)

---

## 5. Évolution possible — App web locale

Si le volume de projets le justifie, Pensine pourrait évoluer vers une webapp :

**Fonctionnalités envisagées :**
- [ ] CRUD de fiches projets avec les champs structurés
- [ ] Filtres par catégorie, statut, prochaine action
- [ ] Vue tableau (Kanban ou liste) par catégorie
- [ ] Recherche textuelle
- [ ] **Capture rapide** (ajouter une idée en < 5 secondes)
- [ ] Rappels / prochaine action avec date
- [ ] Export Markdown (garder la portabilité)

**Stack envisagée :** React + Vite + TypeScript · SQLite ou localStorage (app locale simple)

---

## 6. Hors scope / non-objectifs

- Gestion de projet collaboratif (usage solo uniquement)
- Synchronisation cloud (local-first)
- Intégration avec des outils tiers (Notion, Linear, etc.)
