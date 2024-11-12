# Identify-and-classify-toxic-online-comments
 This project was to build a multi-headed model that’s capable of detecting different types of of toxicity like threats, obscenity, insults, and identity-based hate. For learning purpose, base model like LSTM, text CNN was built and tested. MOre advanced models are planned to be tested eventually. 
 
## Generate Config
'''
himl hiera/model=textcnn/ --output-file config/config.yaml
```

## Run 
```
python run.py --config config/config.yaml 
```
