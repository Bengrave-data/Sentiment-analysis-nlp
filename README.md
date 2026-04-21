# 💬 Analyse de sentiment de commentaires clients

Projet de traitement du langage naturel (NLP) pour analyser automatiquement le sentiment de commentaires clients en français.

## 🎯 Objectif

Développer un système capable de détecter automatiquement si un commentaire client est positif ou négatif — un cas d'usage très demandé par les entreprises pour analyser leurs avis Google, Trustpilot, réseaux sociaux, etc.

## 🛠️ Technologies utilisées

- **Python 3**
- **Pandas** — manipulation de données
- **Scikit-learn** — Machine Learning classique (CountVectorizer, Régression logistique)
- **Hugging Face Transformers** — modèles d'IA pré-entraînés
- **BERT multilingue** — modèle de Deep Learning pour le NLP
- **Matplotlib** — visualisation

## 📊 Démarche

### 1. Approche Machine Learning classique
- Transformation du texte en vecteurs numériques (Bag of Words)
- Entraînement d'un modèle de régression logistique
- Test sur des commentaires inédits

### 2. Approche Deep Learning (Transfer Learning)
- Utilisation du modèle pré-entraîné **BERT multilingue** de Hugging Face
- Analyse sur une échelle de 1 à 5 étoiles
- Gestion des négations ("pas mal", "ne suis pas déçu")

## 🆚 Comparaison des deux approches

| Caractéristique | ML classique | BERT (Deep Learning) |
|-----------------|--------------|----------------------|
| Compréhension du contexte | ❌ | ✅ |
| Gestion des négations | ❌ | ✅ |
| Notation nuancée | Binaire (0/1) | 5 étoiles |
| Précision | Correcte | Excellente |

## 💼 Cas d'usage business

Ce type d'analyse peut être appliqué à :
- Analyse de satisfaction client (Google Reviews, Trustpilot)
- Classification automatique d'emails
- Veille de e-réputation
- Modération de commentaires

## 👤 Auteur

**Benjamin Gravé** — Data Analyst Freelance
📍 Belgique | 💼 [LinkedIn](https://www.linkedin.com/in/benjamin-grav%C3%A9-217a0517/)
