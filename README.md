# NewsEmbed-Pipeline

Pipeline NLP complète pour classifier automatiquement des articles d’actualité en quatre catégories : **World**, **Sports**, **Business** et **Sci/Tech**.  
Ce projet utilise Hugging Face, Sentence Transformers, ChromaDB, Machine Learning et Streamlit, orchestré par Apache Airflow.

---

## 🔹 Contexte du projet

Avec la croissance massive des informations numériques, il devient difficile pour les plateformes de médias d’organiser, analyser et exploiter efficacement les flux d’articles publiés quotidiennement.  
Ce projet propose un système intelligent capable de classer automatiquement les articles d’actualité dans des catégories stratégiques pour faciliter l’analyse et la visualisation.

---

## 🔹 Fonctionnalités principales

- Chargement du dataset [AG News](https://huggingface.co/datasets/ag_news) depuis Hugging Face.  
- Prétraitement des textes : normalisation, suppression des doublons, stopwords et ponctuation.  
- Conversion des données en DataFrame pandas pour faciliter l’analyse.  
- Génération des embeddings avec **Sentence Transformers**.  
- Stockage des embeddings et métadonnées dans **ChromaDB**.  
- Entraînement et évaluation des modèles de Machine Learning.  
- Déploiement dans une interface **Streamlit** pour la classification en temps réel.  
- Orchestration du pipeline avec **Apache Airflow** pour automatiser toutes les étapes.  

---

## 🔹 Technologies utilisées

- Python 3.x  
- [Hugging Face Datasets](https://huggingface.co/docs/datasets)  
- [Pandas](https://pandas.pydata.org/)  
- [Sentence Transformers](https://www.sbert.net/)  
- [ChromaDB](https://www.trychroma.com/)  
- [Scikit-learn](https://scikit-learn.org/stable/)  
- [Streamlit](https://streamlit.io/)  
- [Apache Airflow](https://airflow.apache.org/)  

---

## 🔹 Installation

1. **Cloner le repository :**
```bash
git clone https://github.com/bouchta65/NewsEmbed-Pipeline
cd NewsEmbed-Pipeline
