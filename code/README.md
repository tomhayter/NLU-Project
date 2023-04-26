# Playlist Generator

This series of notebooks will use emotion recognition and semantic textual similarity to generate a playlist based on a user input. The emotion recognition model has been trained in `EmotionRecognitionTraining.ipynb`. Then, this model was used to classify the emotions for a dataset of one million songs in `LabelSongsWithEmotions.ipynb`. The sentence embedding model was tested in `STS.ipynb`. A demo that combines these models for generating playlists can be found in `PlaylistGenerationDemo.ipynb`. Each notebook should be run in [Google Colab](https://colab.research.google.com/), so that the datasets and models can be loaded from Google Drive.

## Datasets used:
- Emotion labelled tweets (https://huggingface.co/datasets/dair-ai/emotion).
- Spotify Million Song Dataset (https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset). Can also be found on Google Drive (see below).

## Models used:
- Sentence embedding model (https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2).

## Google Drive:
Can be found [here](https://drive.google.com/drive/folders/13sxSbbsRh3fMYJ8Y6zwJVFGuLM2UDymQ?usp=sharing).
Contains:
- ERModel: Emotion Recognition Model trained in `EmotionRecognitionTraining.ipynb`.
- spotify_millsongdata.csv: Spotify Million Song Dataset.