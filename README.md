# Anime or Not?
An NLP model that determines whether a plot is anime enough.

Play with it on [HuggingFace Space](https://huggingface.co/spaces/daspartho/anime-or-not)

# Data Collection

The model is trained on plots that have been labelled as anime or not. I scraped IMDb lists for anime and vice-versa and then extracted plot details using [IMDbPY](https://imdbpy.readthedocs.io/en/latest/) (now Cinemagoer).

For steps to create the dataset check out the [dataset](https://github.com/daspartho/anime-or-not/blob/main/dataset.ipynb) notebook in the repo or open in [Colab](https://colab.research.google.com/github/daspartho/anime-or-not/blob/main/dataset.ipynb).

Dataset hosted [on HuggingFace](https://huggingface.co/datasets/daspartho/anime-or-not)

# Modelling

HuggingFace Transformers' [DistilBERT](https://huggingface.co/docs/transformers/model_doc/distilbert), a pre-trained transformer model, is fine-tuned on the [dataset](https://huggingface.co/datasets/daspartho/anime-or-not) of plots labelled as anime or not.

For steps to make the dataset check out the [model](https://github.com/daspartho/anime-or-not/blob/main/model.ipynb) notebook in the repo or open in [Colab](https://colab.research.google.com/github/daspartho/anime-or-not/blob/main/model.ipynb).


Model hosted [on HuggingFace](https://huggingface.co/daspartho/anime-or-not)

# Contributing
If you want to contribute code, simply create a pull request and the developers will review it. If you have an idea, create an issue and the developers will look into it!
