<p align="center">
  <img src="assets/screenshots/logo.png" alt="IAG-Cardio Logo" width="300" />
</p>

<h1 align="center">🫀 IAG-Cardio & Cardio-Spectra v4</h1>

<p align="center">
  <strong>Intelligence Artificielle Médicale : Diagnostic Cardiaque en Temps Réel pour Zones Médicalement Isolées.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Master-M2%20MIAS%20Centrale%20Lille-purple" alt="Academic">
  <img src="https://img.shields.io/badge/Partnership-STaR--AI-blue" alt="Partner">
  <img src="https://img.shields.io/badge/AI-LLM%20%26%20Deep%20Learning-red" alt="AI">
  <img src="https://img.shields.io/badge/AUC-0.99-brightgreen" alt="Performance">
</p>

---

### 🌟 Vision du Projet
Développé en collaboration avec **STaR-AI**, ce projet vise à briser les barrières géographiques de l'accès aux soins. **IAG-Cardio** permet de détecter des crises cardiaques en temps réel, sans cardiologue sur place, spécifiquement conçu pour les zones rurales (notamment en Afrique).

### 🚀 Deux Solutions Complémentaires
1.  **IAG-Cardio :** Interface de diagnostic génératif où un infirmier dicte les symptômes vocalement pour obtenir une analyse complète.
2.  **Cardio-Spectra v4 :** Pipeline d'analyse d'ECG 12 dérivations capable de détecter **10 pathologies cardiaques** distinctes.

---

## 📸 Performances & Interfaces

> **Explicabilité (XAI) :** Une IA médicale ne peut être adoptée sans être comprise. Nous utilisons **SHAP** pour expliquer chaque décision de l'IA.

| 📉 Matrice de Confusion (r1) | 📊 F1-Score & Rappel (r2) |
|:---:|:---:|
| <img src="assets/screenshots/r1.PNG" width="400" /> | <img src="assets/screenshots/r2.PNG" width="400" /> |

### Aperçu de l'Application
| Dashboard Principal | Analyse ECG | Diagnostic Vocal |
|:---:|:---:|:---:|
| <img src="assets/screenshots/d1.PNG" width="250" /> | <img src="assets/screenshots/d2.PNG" width="250" /> | <img src="assets/screenshots/v1.PNG" width="250" /> |

---

## 🛠️ Stack Technologique High-End

* **Large Language Models (LLM) :** LLaMA 3.3 + GPT-OSS (Diagnostic génératif).
* **Machine Learning :** Random Forest calibré pour la classification ECG.
* **Interprétabilité (XAI) :** SHAP (Shapley Additive Explanations).
* **Frontend & Backend :** Next.js (React) avec NeonDB (PostgreSQL).
* **Performance :** AUC jusqu'à **0.99** sur les arythmies.

---

## 🧠 Enseignements Clés
* **Explicabilité > Précision :** Un médecin n'utilisera jamais une "boîte noire". L'interprétabilité est la clé de la confiance.
* **Adaptation Locale :** L'IA médicale doit être adaptée aux réalités locales (infrastructures, types de symptômes reportés) et non simplement calquée sur les modèles européens.

---

## 👥 L'Équipe (Centrale Lille - M2 MIAS)
Projet réalisé en collaboration étroite par :
* **Edouard Lansiaux**
* **Aurelien Loison**
* **Hugo Kazzi**
* **Guillaume Gauguet**
* **Abdallah Imad LAFENDI**

---

## ⚖️ Propriété Intellectuelle & Confidentialité

Copyright © 2026 **Projet IAG-Cardio / Centrale Lille / STaR-AI**.

Ce dépôt est une **présentation publique**. Le code source, les modèles pré-entraînés et les datasets médicaux sont strictement confidentiels et protégés par les accords de partenariat avec STaR-AI. Toute reproduction est interdite.

---
**Contact :** [Ton Email] | [Lien vers ton LinkedIn]
