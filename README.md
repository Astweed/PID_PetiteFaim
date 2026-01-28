# PID – Petite Faim 

Projet Django réalisé dans le cadre du **Projet Interdisciplinaire (PID)** à l’ESIG.

Petite Faim est une application web qui aide les utilisateurs à trouver des idées de recettes à partir des ingrédients qu’ils ont déjà, en s’appuyant sur l’intelligence artificielle via une API.

---

## Objectifs du projet

- Développer une application web complète avec Django
- Mettre en pratique la méthodologie Agile Scrum
- Travailler en équipe avec Git / GitHub
- Intégrer une API d’IA pour la génération intelligente de recettes
- Concevoir une application utile, réaliste et orientée utilisateur

---

## Fonctionnalités principales (prévisionnelles)

- Saisie libre des ingrédients par l’utilisateur (prompt)
- Génération de recettes via une API d’intelligence artificielle
- Affichage clair des recettes proposées (ingrédients, étapes, conseils)
- Interface web simple et intuitive
- Évolutivité possible 

---

## Technologies utilisées

- **Python**
- **Django**
- **HTML / CSS** (templates Django)
- **API d’intelligence artificielle** (à définir)
- **Git & GitHub** pour le versioning et le travail collaboratif

---

## Organisation & Méthodologie

- Méthode **Agile Scrum**
- Découpage du projet en **Epics** et **User Stories**
- Suivi du projet avec **Visual Paradigm**

## Rôles Scrum pour le Sprint 1
  - Scrum Master : Maxence
  - Product Owner : Thommy
  - Scrum Team Members : Emmanuel, Yosef et Astrid

## Rôles Scrum pour le Sprint 2 (à remplir après)

---

## Installation & Lancement du projet

### Prérequis
- Python 3.11+ recommandé
- Git installé

### Installation

```bash
git clone https://github.com/Astweed/PID_PetiteFaim.git
cd PID_PetiteFaim
git checkout develop
python -m venv .venv
source .venv/bin/activate  # Windows : .venv\Scripts\activate
pip install -r requirements.txt
python manage.py runserver
