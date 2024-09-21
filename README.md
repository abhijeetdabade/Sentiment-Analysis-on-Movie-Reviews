
# Sentiment Analysis on Movie Reviews

## Overview
This project performs sentiment analysis on movie reviews using a dataset from Stanford's IMDB collection. Various techniques, such as bag-of-words, TF-IDF, and transformer models (e.g., BERT), are applied to classify reviews as positive or negative.

## Project Structure
- `Sentiment_Analysis_on_Movie_Reviews.ipynb`: The Jupyter notebook containing all the steps from data collection to model building.
- `requirements.txt`: Lists all necessary dependencies.
- `data/`: Directory where the dataset is stored (not included in the repository, but instructions to download are provided).

## How to Run
1. Clone the repository.
2. Install the dependencies: `pip install -r requirements.txt`
3. Download the dataset:
   ```bash
   wget https://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz
   ```
4. Extract the dataset:
   ```python
   import tarfile
   with tarfile.open('aclImdb_v1.tar.gz', 'r') as tar:
       tar.extractall(path='data/')
   ```

5. Run the Jupyter notebook: `jupyter notebook Sentiment_Analysis_on_Movie_Reviews.ipynb`

## Dataset
The dataset is downloaded from [Stanford IMDB Dataset](https://ai.stanford.edu/~amaas/data/sentiment/).
