# Deep Learning Models for Identification of Key Medical Classifier Terms from EHR related to Cardiology

This directory contains example code and trained datasets for Clinical Named Entity recognition using:
1. [CliNER](https://github.com/nol-alb/ClinicalClassifier/tree/main/Models/CliNER)
2. [MedTextClassification](https://github.com/nol-alb/ClinicalClassifier/tree/main/Models/MedTextClassification)
3. [SpaCy](https://github.com/nol-alb/ClinicalClassifier/tree/main/Models/Spacy)
4. [Word2Vec](https://github.com/nol-alb/ClinicalClassifier/tree/main/Models/Word2Vec)

Additionally this task was implemented using open source resources available on repositories linked below:<br>
### 1. BIOBERT: <br>
<p>
BERT (Bidirectional Encoder Representations from Transformers) is a recent paper [11] published by researchers at Google AI Language. It has caused a stir in the Machine Learning community by presenting state-of-the-art results in a wide variety of NLP tasks, including Question Answering (SQuAD v1.1), Natural Language Inference (MNLI), and others. <br>
BioBERT is a biomedical language representation model designed for biomedical text mining tasks such as biomedical named entity recognition, relation extraction, question answering, etc [12]. This project was undertaken by the engineers over at DMIS-Lab and they have provided weighted models trained over PubMed datasets which we can then exploit and tweak for our purposes. <br>
 
Github repository link:  https://github.com/dmis-lab/biobert 

</p>

### 2. MEDCAT: <br>
<p>
Medical Concept Annotation Tool (MedCAT), is an open-source unsupervised approach to NER+L (Named Entity Recognition and Linking). MedCAT uses unsupervised machine learning to disambiguate entities. It was validated on MIMIC-III (a freely accessible critical care database) and MedMentions (Biomedical papers annotated with mentions from the Unified Medical Language System). <br>
 
 Github repository link: https://github.com/CogStack/MedCAT <br>
 A demo application is available at https://medcat.rosalind.kcl.ac.uk/
 </p>


