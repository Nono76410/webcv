# 🚀 CV Web & Portfolio — Nolan Pay

![Netlify](https://img.shields.io/badge/Netlify-Deployed-00C7B7?style=flat&logo=netlify)
![Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3-blue)
![Pipeline](https://img.shields.io/badge/CI%2FCD-Netlify-brightgreen)

> Portfolio personnel et CV interactif hébergé via une chaîne de déploiement continu (CI/CD).

🔗 **URL du site :** [https://nolan-pay.netlify.app](https://nolan-pay.netlify.app)

---

## 👨‍💻 À propos

Actuellement en **3ᵉ année de BUT Réseaux & Télécommunications** à l'IUT de Rouen et **Technicien Support Technique Client (STC N1)** chez l'opérateur **Linkt**, je prépare mon entrée en cycle d'ingénieur pour me spécialiser en **DevOps & Cloud** (recherche d'une alternance de 3 ans pour la **rentrée 2027**).

Ce projet présente mon parcours, mes compétences en administration système/réseau et mes projets d'automatisation.

---

## 🛠️ Architecture & Workflow DevOps

Ce site web n'est pas seulement une vitrine statique, il est intégré dans un flux de travail automatisé :

```mermaid
graph LR
    A[Code Local HTML/CSS] -->|Git Push| B(Dépôt GitHub)
    B -->|Webhook / Build Trigger| C(Netlify CI/CD)
    C -->|Déploiement Automatique| D[Production / CV Web]
