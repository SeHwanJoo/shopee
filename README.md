# [VinBigData Chest X-ray Abnormalities Detection](https://www.kaggle.com/c/vinbigdata-chest-xray-abnormalities-detection)
top 6% solution

### CV strategy

### image classification
scheduler: cosine annealing
loss: arcface loss

-  EfficientNet

-  NFNet

### transformer

#### sentence-transformer

model 1: sentence-transformers/paraphrase-xlm-r-multilingual-v1

model 2 : sentence-transformers/bert-base-nli-cls-token


##### indonesian

model 3 : cahya/distilbert-base-indonesian

#### ensemble

CV best : model 1 + model 3
LB best : model 1 + model 2 + model 3

## try

image classification: Vit, resnext

transformer: RoBert

etc: oof stacking, meta model 

Most of the top solutions' key points were meta models, 
but I was sorry to didn't spend much time on meta models