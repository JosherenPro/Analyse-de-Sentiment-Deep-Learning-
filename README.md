# Analyse de Sentiment (Deep Learning)

Dans ce mini-projet d’**analyse de sentiment** (positif ou négatif), j’ai appliqué mes compétences en **Deep Learning** pour construire un modèle capable de reconnaître l’opinion exprimée dans une phrase.

## Technologies et outils utilisés

1. **Pandas** — pour la manipulation et le nettoyage du jeu de données
2. **Scikit-learn (sklearn)** — pour la division des données en ensembles d’entraînement et de test
3. **NLTK** et **PyTorch** — pour le prétraitement linguistique (tokenisation, nettoyage, etc.)
4. **TF-IDF** ou **CountVectorizer** (*sklearn*) — pour convertir les phrases en représentations numériques exploitables par le modèle
5. **PyTorch** avec une architecture **GRU (Gated Recurrent Units)** — pour la classification des sentiments

## Résultats

Le modèle a obtenu une **accuracy d’environ 87%** sur l’ensemble de test.
Avec un jeu de données plus vaste, il pourrait atteindre une **précision avoisinant les 95%**.
