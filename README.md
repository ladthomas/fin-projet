

readme_content = """# 📎 Annexes diverses – Projet Spota

Ce document regroupe l’ensemble des ressources annexes utiles à la présentation du projet **Spota**, application mobile dédiée à la découverte d’événements culturels gratuits ou abordables dans les grandes villes.

---

## 🔗 Liens utiles

### 🧠 Documentation API (Stoplight)
- 👉 [Documentation interactive de l’API Spota](https://ladthomas.stoplight.io/docs/spota/branches/main/2udzuykgooxbz-spota-backend-api)  
  *Exploration de l’API avec endpoints, paramètres, et réponses types.*

---

### 🗂️ Diagramme de base de données
- 🗺️ [Visualisation du schéma relationnel](https://dbdiagram.io/d/675ad91146c15ed4792be4e8)  
  *Structure des tables, relations entre entités, clés primaires/étrangères.*

---

## 📁 Repositories GitHub publics

### 🚀 Backend – API REST
- 🔧 [Repository GitHub – spota-api](https://github.com/ladthomas/spota-api)  
  *Code source du backend Node.js/Express, documentation technique, gestion des endpoints.*

---

### 📱 Application mobile (Frontend)
- 📲 [Repository GitHub – spota](https://github.com/ladthomas/spota)  
  *Code source de l’application mobile développée avec React Native + Expo.*

---

### 📄 Documents & livrables (PDF / DOC)
- 📘 [Repository GitHub – fin-projet](https://github.com/ladthomas/fin-projet)  
  *Rapports, présentations, schémas et autres documents annexes.*

---

### 🌐 Landing Page de présentation
- 🖥️ [Repository GitHub – LandingPage-spota](https://github.com/ladthomas/LandingPage-spota)  
  *Page d’accueil marketing du projet avec présentation claire de Spota.*

---

## 📝 Notes
- Toutes les ressources ci-dessus sont en accès public et régulièrement mises à jour.
- En cas de problème d’accès ou pour toute question technique, veuillez contacter l’équipe projet.
"""

# Export to README.md
readme_path = Path("/mnt/data/README_Annexes_Spota.md")
readme_path.write_text(readme_content, encoding="utf-8")

readme_path.name
