# Deep Learning Models for Identification of Key Medical Classifier Terms from EHR related to Cardiology [Numen Health Internship]

## OVERVIEW
An internship task for the team of Noel Alben, Niraj Anil, Sai Deepika, and J Sumanth to train and test various deep learning models for the identification and extraction of key medical terms from electronic health records (EHR’s) related to Cardiology, to be later used as a feature in the mobile application.

## GOALS ACHEIVED
1. Find and implement methods to extract medical terms and classifiers from SNOMED CT for purposes of identifying Key Medical Classifier terms from free text.
1. Search for additional databases for terms related to cardiology, specifically discharge summaries and Electronic Health Records.
1. Find, Test, and Train various Deep learning Models for key Medical term identification and extraction from free text Electronic Health Records [Named Entity Recognition].

## Repository Content and Instructions
1. The models in this repository are designed and altered using python script and most of the training of the models took place on local systems which brought about testing efficiency between 90-95%.
2. Some important terms: **Natural Language Processing**, **SNOMED CT**, **Named Entity Recognition**, **Clinical Term Identification**, **BERT**
3. The models that we worked on and their relavent jupyter notebooks are available in the /Models directory of this repository.
4. Some of the models were found, trained and tested by cloning available repositories and resources, the relavent links are provided.
5. Additionaly this repository contains a comprehensive report that was made as part of the internship activity, the report provides relavent information, theory and background for all the work presented in this repository.

## System Dependency
To run the relavent models kindly ensure that the requirements.txt is satisfied on your local system. <br>Run the command:
<pre><code>pip install -r requirements.txt
</code></pre>

## Example
The figure below showcases a Named Entity recogniton task performed on clinical text data using the CliNER model.<br>
![Alt text](https://github.com/nol-alb/ClinicalClassifier/blob/main/Images/Screenshot%202021-07-07%20at%207.25.29%20PM.png "Named Entity Recognition and Classification using CliNER")

