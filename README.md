# Cerveau IA

## Presentation

Cerveau IA est presente ici sous une forme publique limitee, sans secrets ni donnees privees.

## Demarrage rapide

### Pre-requis

- Git installe localement.

### Installer et lancer

```powershell
git clone https://github.com/RYJITS/cerveau_ia_local-showcase.git
cd cerveau_ia_local-showcase
```

## Installation locale

Cette vitrine contient uniquement la documentation generale partageable. Pour la consulter localement:

```powershell
git clone https://github.com/RYJITS/cerveau_ia_local-showcase.git
cd cerveau_ia_local-showcase
Get-Content README.md
```

Aucune configuration serveur privee, adresse reseau ou sauvegarde operationnelle n'est incluse.

## Lancement

Cette vitrine documentaire ne lance aucun service. Les configurations et procedures operationnelles detaillees restent dans le depot prive.

## Utilisation

Lire `README.md` pour la vue d'ensemble, `FICHE_PROJET.md` pour les fonctions, `INSTALLATION_FR.md` pour les pre-requis generaux et `CHANGELOG_FR.md` pour les evolutions. Le deploiement reel s'appuie sur des fichiers prives absents de cette vitrine.

## Concept

Espace de travail IA local qui organise les instructions, la memoire, les competences, les integrations API et les projets dans un systeme coherent.

Conserver un contexte durable entre les assistants IA et les projets, reutiliser les memes competences et appliquer des regles communes sans exposer les donnees privees.

Public vise: Usage personnel et prive pour piloter plusieurs projets avec des assistants IA tout en gardant la maitrise des fichiers, de la memoire et des acces API.


## Fonctionnement de l'application

Le systeme separe les responsabilites en espaces dedies: les instructions definissent les regles de travail, la memoire conserve les decisions et apprentissages, les competences apportent des methodes reutilisables, les configurations API restent locales, et chaque projet garde ses propres sources et documents. Les assistants utilisent ce contexte commun pour travailler de maniere coherente tout en respectant les limites de chaque projet.

## Fonctions de l'application

- Organise les instructions communes utilisees par les assistants IA.
- Conserve une memoire utilisateur et une memoire par projet.
- Centralise les competences et outils reutilisables entre plusieurs projets.
- Isole les configurations API locales et les donnees sensibles.
- Structure les projets dans des dossiers independants avec des regles communes.
- Produit une vue publique assainie sans publier le cerveau central complet.

## Actualisations et evolution

- Renommage de la representation locale en 89_cerveau_ia_local (2026-08-07)
- Separation explicite entre l'environnement prive et sa representation publique (2026-08-07)
- Consolidation des regles communes de memoire et de securite (2026-08-07)

## Comment le projet a ete reflechi et construit

Le projet suit une approche locale, modulaire et prudente. Les informations partagees entre projets sont centralisees uniquement lorsqu'elles sont reellement transverses; les sources, secrets et donnees metier restent separes. Une representation publique limitee permet de presenter le concept et les fonctions sans exposer la structure privee complete.

### Outils, IA et moteurs utilises

- Documents Markdown et JSON
- Scripts Node.js d'automatisation
- Assistants Codex et Mistral
- Index de memoire
- Competences reutilisables
- Configuration API locale
- Architecture locale modulaire
- Separation des responsabilites
- Memoire persistante indexee
- Configuration sensible non publiee
- Documentation versionnee
- Vitrine publique assainie

### Options techniques detectees

- Options techniques a documenter.

### Stack et dependances principales

- Dossier projet
- Architecture locale modulaire
- Separation des responsabilites
- Memoire persistante indexee
- Configuration sensible non publiee
- Documentation versionnee
- Vitrine publique assainie

### Scripts disponibles

- Aucun script detecte.

### Dependances applicatives

- Aucune dependance applicative detectee.

### Dependances de developpement

- Aucune dependance de developpement detectee.

## Automatisations et comportements internes

- Chargement des instructions communes au demarrage d'une session
- Enregistrement des decisions dans la memoire utilisateur ou projet
- Regeneration des index apres une mise a jour de memoire
- Mise a disposition des competences reutilisables
- Application des regles propres au projet actif
- Lecture locale des configurations API sans les publier

## Captures d'ecran

Aucune capture publique n'est disponible pour ce projet.

## Variables d'environnement

Aucune variable d'environnement n'est requise d'apres les fichiers publies.

## Securite

Ne jamais publier `.env`, tokens, sessions, logs sensibles, cles privees ou donnees personnelles.
