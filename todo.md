# 📋 Méthode de Gestion des Actions - Olive

 

Ce document décrit la méthodologie personnelle d'Olive pour organiser, prioriser et suivre ses actions professionnelles et personnelles.

 

---

 

## 🎯 **Philosophie Globale**

 

La gestion des actions chez Olive repose sur :

- **Une approche structurée** mais flexible

- **Un équilibre entre rigueur et adaptabilité**

- **La transparence** via un suivi visuel et collaboratif

- **L'amélioration continue** par rétrospection régulière

 

---

 

## 📊 **Structure du Système**

 

### 1. **Hiérarchie des Priorités**

 

Olive utilise un système de **priorités visuelles et textuelles** pour classer ses tâches :

 

| Symbole | Niveau de Priorité | Description |

|---------|-------------------|-------------|

| `!!!` | **Urgent/Critique** | Actions à traiter **immédiatement** (ex: recrutement, deadlines immédiates) |

| `!!` | **Haute Priorité** | Actions importantes avec échéance proche (ex: formations, réunions clés) |

| `!` | **Priorité Moyenne** | Actions importantes mais moins urgentes (ex: études, veille) |

| `~` | **Priorité Faible** | Actions utiles mais non critiques (ex: idées, explorations) |

| *Aucun symbole* | **Standard** | Actions normales du quotidien |

 

---

 

### 2. **Catégorisation par Tags**

 

Chaque tâche est associée à des **tags thématiques** pour faciliter le filtrage :

 

| Tag | Domaine | Exemples d'Actions |

|-----|---------|-------------------|

| `#UHF` | Unité de Travail UHF | Tests, maintenance, développement |

| `#metier` | Activités Métier | Études, veille, projets transverses |

| `#IA` | Intelligence Artificielle | Expérimentations, veille IA |

| `#💡` | Idées/Innovation | Propositions non formalisées |

| `#FORMATION` | Formation | Sessions de formation, certifications |

| `#TEAM` | Gestion d'Équipe | Recrutement, évaluations, onboarding |

| `#GAN`, `#COBRA`, `#SG` | Projets Spécifiques | Tâches liées à des projets nommés |

 

---

 

### 3. **Organisation en Listes Kanban**

 

Le système utilise une structure **Kanban-like** avec des colonnes thématiques :

 

| Liste | Statut | Description |

|-------|--------|-------------|

| **📦 Backlog** | Non commencé | Idées, projets futurs ou tâches en attente de ressources |

| **🗂️ Todo** | À faire | Tâches planifiées pour les prochains jours/semaines |

| **🎯 Today** | Aujourd'hui | Actions prioritaires du jour |

| **⏸️ Standby** | En pause | Tâches interrompues ou en attente d'informations |

| **✅ Done** | Terminées | Historique des actions complétées (archivage pour traçabilité) |

 

---

 

## ⚙️ **Processus de Gestion**

 

### **1. Capture des Actions**

- **Sources multiples** :

  - Réunions (CR, décisions)

  - Emails (demandes, follow-ups)

  - Idées spontanées (marquées `#💡`)

  - Retours d'expérience (RETEX)

- **Format standardisé** :

  ```markdown

  - [ ] Tâche @responsable #tag ~durée date-échéance

  ```

  Exemple :

  ```markdown

  - [ ] Faire kick off BMN AURORE 2026-11-02 #UHF ~1h

  ```

 

### **2. Priorisation**

- **Matrice Urgence/Importance** :

  - **Urgent + Important** → `!!!` (ex: recrutement)

  - **Important mais non urgent** → `#metier` (ex: études)

  - **Urgence faible** → `~` (ex: veille)

- **Règles de priorisation** :

  - Deadlines fixes → priorité absolue

  - Projets collaboratifs → coordination avec les parties prenantes

  - Idées innovantes → évaluées séparément (liste `#💡`)

 

### **3. Planification**

- **Horizon temporel** :

  - **Court terme** : Liste `Today` (actions du jour)

  - **Moyen terme** : Liste `Todo` (1-2 semaines)

  - **Long terme** : Liste `Backlog` (projets futurs)

- **Durées estimées** :

  - Toujours indiquées (`~30m`, `~2h`, `~1d`)

  - Ajustées en fonction de la charge réelle

 

### **4. Exécution**

- **Suivi visuel** :

  - Mise à jour quotidienne des statuts (`[ ]` → `[/]` → `[x]`)

  - Couleurs pour les priorités (`!!!` en rouge, `!` en orange)

- **Flexibilité** :

  - Réaffectation possible entre listes (ex: `Todo` → `Standby` si blocage)

  - Réévaluation hebdomadaire des priorités

 

### **5. Rétrospection**

- **Revue hebdomadaire** :

  - Transfert des tâches `Todo` vers `Done` ou `Backlog`

  - Analyse des blocages (liste `Standby`)

  - Mise à jour des deadlines

- **Bilan mensuel** :

  - Évaluation des objectifs atteints

  - Ajustement des méthodes si nécessaire

 

---

 

## 🔄 **Flux de Travail Type**

 

```mermaid

graph TD

    A[Capture] --> B{Priorisation}

    B -->|Urgent| C[Today]

    B -->|Important| D[Todo]

    B -->|Idée| E[Backlog/#💡]

    C --> F[Exécution]

    D --> F

    E -->|Mûri| D

    F --> G[Statut: [/] ou [x]]

    G --> H[Rétrospection]

    H --> B

```

 

---

 

## 📌 **Bonnes Pratiques**

 

1. **Clarté** :

   - Toujours indiquer `@responsable`, `#tag`, et `~durée`

   - Utiliser des libellés précis (éviter les tâches trop génériques)

 

2. **Collaboration** :

   - Assigner les tâches avec `@` pour clarifier les responsabilités

   - Utiliser les tags pour partager avec les équipes (ex: `#UHF` pour l'unité)

 

3. **Flexibilité** :

   - Accepter de déplacer les tâches entre listes si nécessaire

   - Ne pas hésiter à marquer une tâche en `Standby` si bloquée

 

4. **Transparence** :

   - Archiver systématiquement les tâches `Done` pour traçabilité

   - Utiliser les deadlines pour anticiper les surcharges

 

5. **Amélioration Continue** :

   - Noter les idées `#💡` pour innovation future

   - Réévaluer régulièrement les priorités en fonction du contexte

 

---

 

## 🛠️ **Outils Complémentaires**

 

- **Calendrier Outlook** : Pour les réunions et deadlines critiques

- **Fichiers de suivi** : Documents dédiés pour les projets complexes (ex: roadmaps)

- **Collaboration** : Partage des tags avec les équipes (ex: `#metier` pour les activités transverses)

 

---

## 📝 **Exemple Concret**

 

### **Scénario : Préparation d'une Formation**

1. **Capture** :

   - Email reçu : "Formation Software DevOps à organiser le 2026-10-23"

2. **Priorisation** :

   - Urgent (date fixe) + Important (formation) → `!!!`

   - Tag `#FORMATION` + `@me` (responsable)

3. **Planification** :

   - Ajout à la liste `Todo` avec échéance

   - Estimation : `~8h` (préparation + logistique)

4. **Exécution** :

   - Réservation de la salle, préparation du support

   - Suivi avec `[/]` pendant la préparation

5. **Clôture** :

   - Passage à `[x]` après la formation

   - Archivage dans `Done` avec détails (ex: "#FORMATION @me ~8h 2026-10-23")

 

---

## 📚 **Ressources Associées**

 

- [TODO.md](TODO.md) : Liste principale des actions

- [Roadmaps](ex: "roadmap AT sur DP") : Pour les projets à long terme

- [CR Réunions](ex: "CR PALMA SSA") : Pour les décisions formalisées

- [Emails](ex: "Réponse PROFIDIS @wilfrid") : Suivi des échanges

 

---

**Dernière mise à jour** : 2026-10-23

**Auteur** : Olive

**Méthode inspirée de** : Approches Agile + Gestion de Projet Personnelle (GTD-like)