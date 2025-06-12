# 📦 pipeline ci-cd

Projet backend Django permettant de mettre en place une méthodologie DevSecOps dans le cadre de mon projet tutoré.  
Ce projet a pour objectif de détecter, analyser et corriger les vulnérabilités identifiées par l’OWASP Top 10 à l’aide d’un pipeline CI/CD sécurisé.

---

## 🎯 Objectif du projet

- Intégrer un pipeline CI/CD sécurisé pour un backend Django.
- Automatiser l’analyse de sécurité du code source et des dépendances.
- Détecter les vulnérabilités listées dans l’**OWASP Top 10**.
- Mettre en place des actions correctives automatiques ou manuelles.
- Suivre une démarche **DevSecOps** de bout en bout.

---

## 🚀 Fonctionnalités

- ✅ Analyse statique du code avec **Bandit**
- ✅ Vérification des dépendances avec **Safety**
- ✅ Intégration continue via **GitHub Actions**
- ✅ Génération automatique de rapports de sécurité
- ✅ Gestion des vulnérabilités OWASP Top 10 côté backend

---

## 🛠️ Technologies utilisées

- [Python 3.12](https://www.python.org/)
- [Django 5.x](https://www.djangoproject.com/)
- [Bandit](https://bandit.readthedocs.io/)
- [Safety](https://pyup.io/safety/)
- [GitHub Actions](https://github.com/features/actions)

---

## 📦 Installation locale

### 1️⃣ Cloner le dépôt

```bash
git clone https://github.com/pichou237/pipeline-ci-cd.git
cd pipeline-ci-cd
