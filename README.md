# How to run the notebook

## Software requirements

It is recommended to run the following notebook using a conda environment with the following dependencies:
* `python=3.10`
* `ipython=8.8`
* `jupyter=1.0.0`
* `notebook=6.5.2`
* `pandas=1.5.2`
* `numpy=1.24.1`
* `seaborn=0.11.2`
* `matplotlib=3.6.2`
* `wordcloud=1.8.2.2`
* `spacy=3.4.4`
* `category_encoders=2.5.1`
* `scikit-learn=1.2.0`
* `cudatoolkit=11.2`
* `cudnn=8.1.0`
* `tensorflow=2.11`
* `keras=2.11.0`
* `chardet=4.0.0`

Also run the following command to download spacy english module:
```
python -m spacy download en
```

## Other instructions
The dataset should be named `data.csv` and it should be positioned in the same folder as the notebook. Also, it is recommended to create new folders named `images` and `histories` in the same position.