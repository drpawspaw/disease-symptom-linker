# Disease Symptom Linker with Ontology

This repository contains the code snippets used to implement the entity disambiguation model for animal disease and symptoms. Basically this component contain three main sub-modules;

- Part-of-Speech Tagger - Identify and tagged the named entities from the given sentences or the user input. This module developed using the custom tagged corpus and you can find the related implementations from (https://github.com/drpawspaw/disease-symptom-ner)
    
- Text-Similarity - This component used to compare the two words and return the similarity. For this module, developer has used the state-of-art model available in the hugging face (https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2, https://huggingface.co/tasks/sentence-similarity)

- Semantic-Similarity - This component used to the contextual similarity of the two words and return the similarity. For this module, developer  has used the state-of-art model available in the hugging face (https://huggingface.co/keras-io/bert-semantic-similarity)


Find the ontology used to implement this module (https://github.com/drpawspaw/animal-disease-symptom-ontology)