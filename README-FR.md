# Agents IA du Studio Contains

Une collection complète d'agents IA spécialisés conçus pour accélérer et améliorer chaque aspect du développement rapide. Chaque agent est un expert dans son domaine, prêt à être invoqué lorsque son expertise est nécessaire.

## 📥 Installation

1. **Téléchargez ce dépôt:**
   ```bash
   git clone https://github.com/contains-studio/agents.git
   ```

2. **Copiez dans votre répertoire d'agents Claude Code:**
   ```bash
   cp -r agents/* ~/.claude/agents/
   ```

   Ou copiez manuellement tous les fichiers d'agents dans votre répertoire `~/.claude/agents/`.

3. **Redémarrez Claude Code** pour charger les nouveaux agents.

## 🚀 Démarrage Rapide

Les agents sont automatiquement disponibles dans Claude Code. Décrivez simplement votre tâche et l'agent approprié sera déclenché. Vous pouvez également demander explicitement un agent en mentionnant son nom.

📚 **En savoir plus:** [Documentation des Sub-Agents Claude Code](https://docs.anthropic.com/en/docs/claude-code/sub-agents)

### Exemples d'Utilisation
- "Créer une nouvelle application pour suivre les habitudes de méditation" → `prototypeur-rapide`
- "Qu'est-ce qui est tendance sur TikTok que nous pourrions construire ?" → `chercheur-tendances`
- "Les avis de notre application chutent, quel est le problème ?" → `synthetiseur-feedback`
- "Rendre cet écran de chargement plus amusant" → `injecteur-fantaisie`

## 📁 Structure des Répertoires

Les agents sont organisés par département pour une découverte facile:

```
contains-studio-agents/
├── conception/
│   ├── gardien-marque.md
│   ├── designer-ui.md
│   ├── chercheur-ux.md
│   ├── conteur-visuel.md
│   └── injecteur-fantaisie.md
├── ingenierie/
│   ├── ingenieur-ia.md
│   ├── architecte-backend.md
│   ├── automatiseur-devops.md
│   ├── developpeur-frontend.md
│   ├── constructeur-app-mobile.md
│   ├── prototypeur-rapide.md
│   └── reparateur-tests.md
├── marketing/
│   ├── optimiseur-app-store.md
│   ├── createur-contenu.md
│   ├── hacker-croissance.md
│   ├── curateur-instagram.md
│   ├── constructeur-communaute-reddit.md
│   ├── strategiste-tiktok.md
│   └── engageur-twitter.md
├── produit/
│   ├── synthetiseur-feedback.md
│   ├── prioriseur-sprint.md
│   └── chercheur-tendances.md
├── gestion-projet/
│   ├── traceur-experiences.md
│   ├── expediteur-projet.md
│   └── producteur-studio.md
├── operations-studio/
│   ├── rapporteur-analytics.md
│   ├── traceur-finance.md
│   ├── mainteneur-infrastructure.md
│   ├── verificateur-conformite-legale.md
│   └── repondeur-support.md
├── tests/
│   ├── testeur-api.md
│   ├── evaluateur-performance.md
│   ├── analyseur-resultats-tests.md
│   ├── evaluateur-outils.md
│   └── optimiseur-workflow.md
└── bonus/
    ├── joker.md
    └── coach-studio.md
```

## 📋 Liste Complète des Agents

### Département Ingénierie (`ingenierie/`)
- **ingenieur-ia** - Intégrer des fonctionnalités IA/ML qui livrent réellement
- **architecte-backend** - Concevoir des API et systèmes serveur scalables
- **automatiseur-devops** - Déployer continuellement sans casser les choses
- **developpeur-frontend** - Construire des interfaces utilisateur ultra-rapides
- **constructeur-app-mobile** - Créer des expériences iOS/Android natives
- **prototypeur-rapide** - Construire des MVP en jours, pas en semaines
- **reparateur-tests** - Écrire des tests qui attrapent les vrais bugs

### Département Produit (`produit/`)
- **synthetiseur-feedback** - Transformer les plaintes en fonctionnalités
- **prioriseur-sprint** - Livrer la valeur maximale en 6 jours
- **chercheur-tendances** - Identifier les opportunités virales

### Département Marketing (`marketing/`)
- **optimiseur-app-store** - Dominer les résultats de recherche de l'app store
- **createur-contenu** - Générer du contenu sur toutes les plateformes
- **hacker-croissance** - Trouver et exploiter les boucles de croissance virale
- **curateur-instagram** - Maîtriser le jeu du contenu visuel
- **constructeur-communaute-reddit** - Gagner sur Reddit sans être banni
- **strategiste-tiktok** - Créer des moments marketing partageables
- **engageur-twitter** - Surfer les tendances vers l'engagement viral

### Département Conception (`conception/`)
- **gardien-marque** - Garder l'identité visuelle cohérente partout
- **designer-ui** - Concevoir des interfaces que les développeurs peuvent réellement construire
- **chercheur-ux** - Transformer les insights utilisateur en améliorations produit
- **conteur-visuel** - Créer des visuels qui convertissent et se partagent
- **injecteur-fantaisie** - Ajouter de la joie à chaque interaction

### Gestion de Projet (`gestion-projet/`)
- **traceur-experiences** - Validation de fonctionnalités basée sur les données
- **expediteur-projet** - Lancer des produits qui ne plantent pas
- **producteur-studio** - Garder les équipes en livraison, pas en réunion

### Opérations Studio (`operations-studio/`)
- **rapporteur-analytics** - Transformer les données en insights actionnables
- **traceur-finance** - Garder le studio profitable
- **mainteneur-infrastructure** - Scaler sans casser la banque
- **verificateur-conformite-legale** - Rester légal tout en avançant vite
- **repondeur-support** - Transformer les utilisateurs en colère en défenseurs

### Tests & Benchmarking (`tests/`)
- **testeur-api** - Assurer que les API fonctionnent sous pression
- **evaluateur-performance** - Rendre tout plus rapide
- **analyseur-resultats-tests** - Trouver des modèles dans les échecs de tests
- **evaluateur-outils** - Choisir des outils qui aident réellement
- **optimiseur-workflow** - Éliminer les goulots d'étranglement du workflow

## 🎁 Agents Bonus
- **coach-studio** - Rallier les troupes IA à l'excellence
- **joker** - Alléger l'ambiance avec de l'humour tech

## 🎯 Agents Proactifs

Certains agents se déclenchent automatiquement dans des contextes spécifiques:
- **coach-studio** - Quand des tâches multi-agents complexes commencent ou que les agents ont besoin de guidance
- **reparateur-tests** - Après implémentation de fonctionnalités, correction de bugs, ou modification de code
- **injecteur-fantaisie** - Après changements UI/UX
- **traceur-experiences** - Quand des feature flags sont ajoutés

## 💡 Meilleures Pratiques

1. **Laissez les agents travailler ensemble** - Beaucoup de tâches bénéficient de plusieurs agents
2. **Soyez spécifique** - Des descriptions de tâches claires aident les agents à mieux performer
3. **Faites confiance à l'expertise** - Les agents sont conçus pour leurs domaines spécifiques
4. **Itérez rapidement** - Les agents supportent la philosophie de sprint de 6 jours

## 🔧 Détails Techniques

### Structure d'Agent
Chaque agent inclut:
- **name**: Identifiant unique
- **description**: Quand utiliser l'agent avec exemples
- **color**: Identification visuelle
- **tools**: Outils spécifiques auxquels l'agent peut accéder
- **Prompt système**: Expertise détaillée et instructions

### Ajouter de Nouveaux Agents
1. Créer un nouveau fichier `.md` dans le dossier de département approprié
2. Suivre le format existant avec frontmatter YAML
3. Inclure 3-4 exemples d'utilisation détaillés
4. Écrire un prompt système complet (500+ mots)
5. Tester l'agent avec des tâches réelles

## 📊 Performance des Agents

Suivre l'efficacité des agents à travers:
- Temps de complétion des tâches
- Satisfaction utilisateur
- Taux d'erreur
- Adoption de fonctionnalités
- Vélocité de développement

## 🚦 Statut

- ✅ **Actif**: Entièrement fonctionnel et testé
- 🚧 **Bientôt**: En développement
- 🧪 **Beta**: Test avec fonctionnalité limitée

## ��️ Personnaliser les Agents pour Votre Studio

### Checklist de Personnalisation d'Agent

Utilisez cette checklist lors de la création ou modification d'agents pour vos besoins spécifiques:

#### 📋 Composants Requis
- [ ] **Frontmatter YAML**
  - [ ] `name`: Identifiant unique de l'agent (kebab-case)
  - [ ] `description`: Quand utiliser + 3-4 exemples détaillés avec contexte/commentaire
  - [ ] `color`: Identification visuelle (ex: blue, green, purple, indigo)
  - [ ] `tools`: Outils spécifiques auxquels l'agent peut accéder (Write, Read, MultiEdit, Bash, etc.)

#### 📝 Exigences du Prompt Système (500+ mots)
- [ ] **Identité de l'Agent**: Définition claire du rôle et zone d'expertise
- [ ] **Responsabilités Principales**: 5-8 devoirs principaux spécifiques
- [ ] **Expertise de Domaine**: Compétences techniques et zones de connaissance
- [ ] **Intégration Studio**: Comment l'agent s'intègre dans le workflow de sprint de 6 jours
- [ ] **Meilleures Pratiques**: Méthodologies et approches spécifiques
- [ ] **Contraintes**: Ce que l'agent devrait/ne devrait pas faire
- [ ] **Métriques de Succès**: Comment mesurer l'efficacité de l'agent

#### 🎯 Exemples Requis par Type d'Agent

**Agents Ingénierie** ont besoin d'exemples pour:
- [ ] Demandes d'implémentation de fonctionnalités
- [ ] Scénarios de correction de bugs
- [ ] Tâches de refactoring de code
- [ ] Décisions d'architecture

**Agents Conception** ont besoin d'exemples pour:
- [ ] Création de nouveaux composants UI
- [ ] Travail sur système de design
- [ ] Problèmes d'expérience utilisateur
- [ ] Tâches d'identité visuelle

**Agents Marketing** ont besoin d'exemples pour:
- [ ] Demandes de création de campagne
- [ ] Besoins de contenu spécifique à la plateforme
- [ ] Identification d'opportunités de croissance
- [ ] Tâches de positionnement de marque

**Agents Produit** ont besoin d'exemples pour:
- [ ] Décisions de priorisation de fonctionnalités
- [ ] Analyse de feedback utilisateur
- [ ] Demandes de recherche de marché
- [ ] Besoins de planification stratégique

**Agents Opérations** ont besoin d'exemples pour:
- [ ] Optimisation de processus
- [ ] Évaluation d'outils
- [ ] Gestion de ressources
- [ ] Analyse de performance

#### ✅ Checklist de Test & Validation
- [ ] **Test de Déclenchement**: L'agent s'active correctement pour les cas d'usage prévus
- [ ] **Accès aux Outils**: L'agent peut utiliser tous les outils spécifiés correctement
- [ ] **Qualité de Sortie**: Les réponses sont utiles et actionnables
- [ ] **Cas Limites**: L'agent gère les scénarios inattendus ou complexes
- [ ] **Intégration**: Fonctionne bien avec d'autres agents dans workflows multi-agents
- [ ] **Performance**: Complète les tâches dans des délais raisonnables
- [ ] **Documentation**: Les exemples reflètent précisément les modèles d'utilisation réels

#### 🔧 Template de Structure de Fichier Agent

```markdown
---
name: nom-de-votre-agent
description: Utilisez cet agent quand [scénario]. Cet agent se spécialise dans [expertise]. Exemples:\n\n<example>\nContext: [situation]\nuser: "[demande utilisateur]"\nassistant: "[approche de réponse]"\n<commentary>\n[pourquoi cet exemple est important]\n</commentary>\n</example>\n\n[3 exemples de plus...]
color: couleur-agent
tools: Outil1, Outil2, Outil3
---

Vous êtes un [rôle] qui [fonction principale]. Votre expertise couvre [domaines]. Vous comprenez que dans les sprints de 6 jours, [contrainte de sprint], donc vous [approche].

Vos responsabilités principales:
1. [Responsabilité 1]
2. [Responsabilité 2]
...

[Contenu détaillé du prompt système...]

Votre objectif est de [objectif ultime]. Vous [traits de comportement clés]. Rappelez-vous: [philosophie clé pour les sprints de 6 jours].
```

#### 📂 Directives Spécifiques par Département

**Ingénierie** (`ingenierie/`): Focus sur vitesse d'implémentation, qualité de code, tests
**Conception** (`conception/`): Emphase sur expérience utilisateur, cohérence visuelle, itération rapide
**Marketing** (`marketing/`): Cibler potentiel viral, expertise plateforme, métriques de croissance
**Produit** (`produit/`): Prioriser valeur utilisateur, décisions basées sur données, adéquation marché
**Opérations** (`operations-studio/`): Optimiser processus, réduire friction, scaler systèmes
**Tests** (`tests/`): Assurer qualité, trouver goulots, valider performance
**Gestion Projet** (`gestion-projet/`): Coordonner équipes, livrer à temps, gérer portée

#### 🎨 Personnalisations

Modifiez ces éléments pour vos besoins:
- [ ] Ajuster exemples pour refléter vos types de produits
- [ ] Ajouter outils spécifiques auxquels les agents ont accès
- [ ] Modifier métriques de succès pour vos KPI
- [ ] Mettre à jour structure de département si nécessaire
- [ ] Personnaliser couleurs d'agents pour votre marque

## 🤝 Contribuer

Pour améliorer les agents existants ou suggérer de nouveaux:
1. Utiliser la checklist de personnalisation ci-dessus
2. Tester minutieusement avec de vrais projets
3. Documenter les améliorations de performance
4. Partager les modèles réussis avec la communauté
