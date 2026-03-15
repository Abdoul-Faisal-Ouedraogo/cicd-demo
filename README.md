# Créez et déployez l'application Node.js avec CI/CD Pipeline  
## Docker + GitHub Actions + AWS EC2

Ce dépôt démontre un pipeline CI/CD réel pour le déploiement d'une application Node.js à l'aide de Docker, GitHub Actions et AWS EC2.

L'objectif de ce projet est de montrer comment les équipes modernes DevOps construisent, conteneurisent et déploient automatiquement des applications à l'aide d'outils standard de l'industrie dans un flux de travail de type production.

---

## 📺  Vidéo Walkthrough

Ce projet est expliqué étape par étape dans une vidéo pratique complète:

🔗 https://youtu.be/WwxSNIrW8bk

Il est fortement recommandé de regarder la vidéo pour comprendre le flux complet et la prise de décision derrière la configuration.

---

## 🚀 Ce Que Ce Projet Couvre


- Création d'une application Node.js
- Contenition de l'application en utilisant Docker
- Création d'un pipeline CI/CD avec GitHub Actions
- Déploiement automatique de l'application sur AWS EC2
- Gérer les déploiements dans un environnement de type production

Cette configuration reflète de près la façon dont les pipelines CI/CD sont mis en œuvre dans de véritables équipes DevOps.

---

## 🧱 Tech Stack

- **Node.js** – Application backend
- **Docker** – Contenarisation d’application
- **GitHub Actions** –  Intégration et déploiement continus
- **AWS EC2** - Calcul cloud pour l’hébergement de l’application
- **Linux (Ubuntu)** – Système d'exploitation de serveur

---

## 🏗️ Aperçu de l'architecture

```text
Developer Pushes Code
        ↓
GitHub Repository
        ↓
GitHub Actions CI/CD Pipeline
  - Build Docker Image
  - Push Image
  - Deploy to EC2
        ↓
Docker Container Running on EC2
        ↓
Application Accessible to Users

A Maitriser

Youtube Video link: https://youtu.be/WwxSNIrW8bk
