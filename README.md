# SmartMovieRec

### Dataset Link
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download

### Demo
https://huggingface.co/spaces/AbdallahAhmed98/SmartMovieRec


# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/Abdallah-Ahmed-98/SmartMovieRec.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n movieRec python=3.7.10 -y
```

```bash
conda activate movieRec
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### STEP 03- get dataset from the following link

```bash
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download
```

### STEP 04- go to research dir and run the following script to generate the models

```bash
Movie Recommender System Data Analysis.ipynb
```

### FINALLY- run the app

```bash
streamlit run app.py
```