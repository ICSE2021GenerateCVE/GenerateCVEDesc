# GenerateCVEDesc
Repository containing training dataset, training codes and experimental dataset.

The code is for automatically extracting CVE elements from unstructured ExploitDB. 
It combines BERT-based Named Entity Recognition (NER) model and BERT-based Question Answering (QA) model. 
The goal is to automatically generate CVE descriptions by CVE templates.

We adopt [HuggingFace](https://github.com/huggingface/transformers)'s architectures to achieve the BERT training.

### NER Training
```
python3 code/BERT_NER.py 
```

### QA Training
```
python3 code/BERT_QA.py 
```


