# 🤖 Agent IA – Projet Informatique

Ce projet implémente un **Agent IA minimal** capable de comprendre des messages en langage naturel, détecter l’intention de l’utilisateur, extraire des informations utiles (montant, date, nom, ville), gérer un état de dialogue et exécuter des actions simulées.

---

## 🚀 Fonctionnalités

- **Intent Classification** (avec TF-IDF + Logistic Regression)
- **Extraction d’entités (NER simple)** :
  - Montant (ex: "50 dinars")
  - Date (ex: "demain", "10h")
  - Cible (ex: "à Amine")
- **Gestion d’un état de dialogue** :
  - Confirmation d’un transfert
  - Historique des messages
- **Actions simulées** :
  - Météo
  - Solde bancaire
  - Transfert d’argent
  - Création d’événement
- **Deux modes d’utilisation** :
  - 🖥️ **CLI** (terminal)
  - 🌍 **API REST** via FastAPI

---

## 📂 Structure du projet

