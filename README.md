# Atelier ObTIC : Traitement Automatique des Langues avec spaCy

Bienvenue dans le dépôt de l'atelier sur le Traitement Automatique des Langues (TAL) avec la bibliothèque Python **spaCy**. Cet atelier a été conçu pour offrir une introduction pratique et complète aux concepts fondamentaux et aux fonctionnalités avancées de spaCy.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1GEnqIC8OIM5TGconK4pNpMbdjA6-nQHY?usp=sharing)

## 📖 À propos de cet atelier

Cet atelier s'adresse aux étudiants, chercheurs et développeurs ayant des bases en Python et souhaitant explorer le monde du TAL. À travers un notebook Jupyter interactif, nous partons des bases de la manipulation de texte pour aller jusqu'à des applications plus complexes comme la recherche de motifs et l'analyse sémantique.

### Ce que vous apprendrez :

* **Les bases de spaCy** : Comprendre le pipeline de traitement, la tokenisation et la segmentation en phrases avec `spacy.blank()`.
* **Les annotations linguistiques** : Utiliser les modèles pré-entraînés (`spacy.load()`) pour effectuer :
    * La lemmatisation (réduction des mots à leur forme de base).
    * L'étiquetage morpho-syntaxique (POS Tagging).
    * L'analyse morphologique.
* **L'analyse de texte** : Réaliser une analyse lexicométrique simple et filtrer les mots-vides (*stop words*).
* **Les fonctionnalités avancées** :
    * Visualiser les arbres de dépendance avec **DisplaCy**.
    * Effectuer la **Reconnaissance d'Entités Nommées (NER)** pour identifier les personnes, lieux, et organisations.
    * Utiliser le **`Matcher`** pour trouver des motifs linguistiques complexes (plus puissant que les regex).
    * Mesurer la **similarité sémantique** entre des mots ou des phrases grâce aux vecteurs de mots (*word embeddings*).
* **Bonus** : Un aperçu de comment personnaliser et entraîner un composant de spaCy pour une langue peu dotée.

---

## 📂 Contenu du Dépôt

1.  **`obtic_atelier_spacy.ipynb`** : Le notebook Jupyter principal contenant tout le code, les exercices et les explications.
2.  **`Spacy Atelier.pdf`** : Les diapositives de présentation utilisées durant l'atelier.
3.  **`README.md`** : Ce fichier, qui fournit une vue d'ensemble du projet.

---

## 🚀 Comment commencer ?

### Option 1 : Google Colab (Recommandé)

Le moyen le plus simple de suivre cet atelier est d'utiliser Google Colab. Cela ne nécessite aucune installation sur votre machine.

Cliquez simplement sur le badge ci-dessous pour ouvrir le notebook dans votre navigateur :

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1GEnqIC8OIM5TGconK4pNpMbdjA6-nQHY?usp=sharing)

### Option 2 : En local

Si vous préférez exécuter le notebook sur votre propre machine :
1.  Clonez ce dépôt : `git clone https://github.com/VOTRE_NOM_UTILISATEUR/atelier_obtic_spacy.git`
2.  Créez un environnement virtuel et activez-le.
3.  Installez les dépendances nécessaires :
    ```bash
    pip install -U spacy
    pip install requests
    ```
4.  Téléchargez les modèles spaCy utilisés dans l'atelier :
    ```bash
    python -m spacy download fr_core_news_sm
    python -m spacy download fr_core_news_md
    python -m spacy download fr_core_news_lg
    python -m spacy download en_core_web_lg
    ```
5.  Lancez Jupyter Notebook ou JupyterLab et ouvrez le fichier `obtic_atelier_spacy.ipynb`.

---

Cet atelier a été préparé par l'équipe **ObTIC** de Sorbonne Université.
