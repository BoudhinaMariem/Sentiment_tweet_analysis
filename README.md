# 🧠 Analyse des Sentiments et Influence dans les Réseaux Sociaux  

## 🎯 Objectif du Projet
Analyser des **tweets** afin de détecter les **sentiments (positif/négatif)** et comprendre les **relations d’influence entre utilisateurs**.  
Le but est d’identifier les **influenceurs**, les **communautés** et les **opinions dominantes** à travers les interactions sociales (mentions, retweets, hashtags...).

---

## 🧩 Techniques à Explorer

### 🔤 NLP (Natural Language Processing)
- Utilisation de **Transformers** (BERT, DistilBERT ou RoBERTa) pour l’analyse des sentiments.
- Nettoyage et prétraitement des tweets : tokenization, stopwords, lemmatisation.

### 🕸️ GNN (Graph Neural Networks)
- Construction d’un **graphe utilisateur-tweet** reliant :
  - Les utilisateurs entre eux (mentions, retweets)
  - Les tweets aux auteurs  
- Utilisation de **PyTorch Geometric** ou **DGL** pour la modélisation du graphe.

### 🔁 GTN (Graph Transformer Networks)
- Propagation de l’information dans le graphe pour détecter :
  - Les **influenceurs**
  - Les **clusters de communautés**

### 💬 Graph-RAG (Retrieval-Augmented Generation sur graphes)
- Permet de répondre à des questions comme :
  > “Quels tweets influencent le plus cette opinion ?”  
  > “Quel utilisateur a le plus d’impact sur un sujet donné ?”

---

## 📊 Jeu de Données

### 🗂️ Dataset principal :
[Sentiment140 – Annotated Tweets (Kaggle)](https://www.kaggle.com/datasets/kazanova/sentiment140)

- 1,6 million de tweets annotés : *positif / négatif / neutre*
- Peut être enrichi avec :
  - Graphe des utilisateurs (mentions, retweets)
  - Métadonnées : localisation, hashtags, heure

---

## 🚀 Livrables Attendus
- ✅ Graphe interactif des utilisateurs et tweets  
- ✅ Identification des communautés et influenceurs  
- ✅ Modèle prédictif pour le **sentiment** des tweets  
- ✅ Suggestions d’interactions influentes  
- ✅ Visualisation via **Streamlit** ou **Power BI / Dash**

---

## ⚙️ Stack Technique
- **Langages :** Python  
- **Librairies principales :** PyTorch, Hugging Face Transformers, NetworkX, PyTorch Geometric  
- **Outils :** Jupyter Notebook, GitHub, Kaggle, Streamlit  

---

# 🎯 Déploiement du Meilleur Modèle avec Streamlit

Le meilleur modèle entraîné pour la classification de sentiments a été déployé dans une interface **Streamlit** simple, rapide et interactive.

### ✔️ Fonctionnalités :
- Saisie d’un tweet
- Prédiction instantanée du sentiment
- Probabilités associées à chaque classe
- Interface web moderne et intuitive

### 📸 Captures du déploiement Streamlit :

<img width="575" height="487" alt="negatif" src="https://github.com/user-attachments/assets/ad47ab39-cd93-490a-9095-5c4d8b655bd7" />

<img width="627" height="478" alt="positif" src="https://github.com/user-attachments/assets/6d882871-b6da-4901-984d-5754d4269cf7" />

---

# 🎯 Chatbot RAG avec Gradio

Un chatbot intelligent a été développé en utilisant **Gradio** et la méthode **RAG** (Retrieval-Augmented Generation).  
Il permet d’interagir avec les tweets indexés pour répondre à des questions liées aux sentiments, sujets populaires ou influenceurs.

### ✔️ Capacités :
- Réponses contextuelles générées automatiquement
- Interface conversationnelle simple et accessible

### 📸 Capture du chatbot Gradio :

<img width="615" height="532" alt="chatboat" src="https://github.com/user-attachments/assets/11c8f070-d6d0-4bf9-bb5e-f15f4fe1ac31" />



---

## 👩‍💻 Auteurs
👤 **Mariem Boudhina**  
🎓 Engineering Student in Business Intelligence  
📧 [mareim.boudhina@esprit.tn](mailto:mareim.boudhina@esprit.tn)  
🔗 [linkedin.com/in/mariemboudhina](https://linkedin.com/in/mariemboudhina)

---

⭐ *If you like this project, feel free to star it and contribute!* 🚀
