## Lab 1: NLP Basics 
Credits to: [tartu-nlp-2021](https://github.com/ckittask/tartu-nlp-2021/tree/main/labs/lab_1)

You can either do the lab exercises in Google Colab or download the notebook and do it on your own computer. 
If you prefer your own computer, it is recommended to create virtual environment for that. 
```
conda create --name nlp_3.6 python=3.6
conda install -n nlp_3.6 jupyter
conda install -n nlp_3.6  -c conda-forge spacy
conda install -n nlp_3.6 -c anaconda nltk
```
Download the spaCy model, we need this model in the lab: 
``` 
conda activate nlp_3.6
python -m spacy download en_core_web_sm
```

Add it to available kernels: 
```
conda activate nlp_3.6
conda install ipykernel
python -m ipykernel install --user --name nlp_3.6
```

