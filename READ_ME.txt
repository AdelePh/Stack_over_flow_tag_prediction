You need to install Anaconda before runing the following
Download dataset for training :

https://www.kaggle.com/datasets/stackoverflow/stacksample?select=Questions.csv
https://www.kaggle.com/datasets/stackoverflow/stacksample?select=Tags.csv

and place them inside folder stackoverflow_tag_classification

1. from anaconda prompt, navigate to the folder stackoverflow_tag_classification

conda env create -f my_env.yaml
conda activate my_env
python -m spacy download en_core_web_sm

2. type jupyter notebook and press enter or choose the new environment my_env through anaconda navigator

3. open tag_classjification.ipynb and run it