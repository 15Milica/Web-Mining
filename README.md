# Web-Mining
Dataset: Amazon Reviews (Kaggle) -
https://www.kaggle.􏰁om/datasets/kritanjalijain/amazon-reviews

# Sentiment Analysis — RoBERTa Fine-Tuning

Ovaj projekat obuhvata fino podešavanje RoBERTa modela za analizu sentimenta nad Amazon Reviews dataset-om. Korišćeni su različiti modeli, poređene performanse i dokumentovan proces obrade, treniranja i evaluacije.
```
├── training/                          # Folder sa trening skriptama po modelima
│   ├── distilroberta-base-sst2/
│   │   └── traning_model1.ipynb       # Fine-tuning DistilRoBERTa-SST2
│   ├── distilroberta/
│   │   └── traning_model2.ipynb       # Fine-tuning DistilRoBERTa Base
│   └── twitter-roberta/
│       └── traning_model3.ipynb       # Fine-tuning Twitter RoBERTa
│
├── Preprocessing.ipynb                # Priprema podataka, čišćenje i analiza
├── Tokenizing.ipynb                   # Tokenizacija i kreiranje dataset format-a
├── Evaluation.ipynb                   # Evaluacija modela, matrice konfuzije, ROC/PR
│
├── model_comparison.csv               # Uporedni rezultati modela (Accuracy/F1)
├── Analiza Sentimenata.pdf            # Finalni izveštaj / seminarski rad
│
├── requirements.txt                   # Python paketi potrebni za projekat
├── .gitignore                         # Izuzeti fajlovi i foldere iz git repozitorijuma
└── README.md                          # Dokumentacija projekta
```
