## 📚 Mini Knowledge Base – Base de connaissances collaborative

## 📝 Présentation du projet
Ce projet est une base de connaissances collaborative réalisée dans le cadre d’un TPE académique.  
Elle regroupe des fiches pédagogiques rédigées en Markdown sur les thèmes suivants :
- Git
- GitHub
- Méthodes Agiles
- Bonnes pratiques de développement

L’objectif est de travailler dans des conditions proches du monde professionnel en utilisant Git, GitHub et une organisation Agile.

---

## 🎯 Objectifs pédagogiques
- Utiliser Git de manière professionnelle en local
- Travailler en équipe avec GitHub
- Appliquer un workflow Git utilisé en entreprise
- Organiser le travail avec une approche Agile
- Mettre en place une intégration continue simple

---

## 📁 Structure du dépôt

knowledge-base/
│── README.md
│── CONTRIBUTING.md
│── docs/
│ ├── git/
│ │ ├── git-init.md
│ │ ├── branches.md
│ ├── agile/
│ │ ├── scrum.md
│ │ ├── kanban.md
│── assets/

---

## 🧩 Organisation Agile

Méthode utilisée : **Kanban**

Outils :
- GitHub Issues (Backlog)
- GitHub Projects (Tableau Kanban)

Colonnes du Kanban :
- Backlog
- In Progress
- Review
- Done

Chaque Issue correspond à une **User Story** sous la forme :
> En tant que …  
> Je veux …  
> Afin de …

---

## 🔀 Workflow Git utilisé
### Workflow choisi : **GitHub Flow**

**Justification :**

- Simple et adapté aux petites équipes
- Recommandé pour les projets collaboratifs
- Très utilisé en entreprise

**Règles principales :**

- La branche `main` est protégée
- Une branche par fonctionnalité : `feature/nom-fonctionnalité`
- Pull Request obligatoire
- Revue par au moins un membre avant fusion

---

## 🧪 Intégration Continue (CI)

Une GitHub Action est mise en place pour :
- Vérifier la présence des fichiers Markdown obligatoires
- Garantir la cohérence minimale du dépôt

---

## 🤝 Règles de contribution

Les règles de contribution sont détaillées dans le fichier [CONTRIBUTING.md](CONTRIBUTING.md).

---

## 📌 Auteurs

Projet réalisé par un groupe de 3 étudiants dans un cadre académique.
 
 - DIFFO NGASSOP KEVIN DIBRIL (RS-Cybersécurité Lipro_Azimut_Campus B)

 - KOH DJOUFO VALENTIN (Génie-logiciel Lipro_Azimut_Campus B)

 - BASSEEK BRENDA PAOLA (RS-Cybersécurité Lipro_Azimut_Campus B)

---

## 📄 Licence

Projet à usage pédagogique.