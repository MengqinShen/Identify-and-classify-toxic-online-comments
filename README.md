# Identify-and-classify-toxic-online-comments
 This project was to build a multi-headed model that’s capable of detecting different types of of toxicity like threats, obscenity, insults, and identity-based hate. For learning purpose, base model like NB, text CNN , and LSTM was built and tested. MOre advanced models like BERT was used to further improve model accuracy . 
 
## Generate Config
```
himl hiera/model=bert/ --output-file config/bert_config.yaml
```

## Run
```
python run.py --config config/bert_config.yaml 
```
