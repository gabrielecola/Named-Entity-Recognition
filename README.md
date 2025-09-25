## Named Entity Recognition for GUM

## Table of Contents

 - [Named Entity Recognition using Neural Neworks and Transformers Approach](#named-entity-recognition-using-neural-neworks-and-transformers-approach)
- [1. Problem Statement](#1-problem-statement)
- [2. Data Description](#2-data-description)
  * [Attribute Information](#attribute-information)
    + [Inputs](#inputs)
    + [Output](#output)
- [3. Topic Modelling](#3-topic-modelling)
- [4. EDA](#4-eda)
- [5. Modelling Evaluation](#5-modelling-evaluation)
- [6. Results](#6-results)

### Name Entity Recognition using Neural Networks and Transformers Approach

This dataset contains release versions of the Georgetown University Multilayer Corpus (GUM), a corpus of English texts from twelve written and spoken text types.The corpus is created as part of the course LING-367 (Computational Corpus Linguistics) at Georgetown University.
Thus, our aim is to use two different kind of classifiers in order to accomplish the NER task.

### 1. Problem Statement
Classify correctly the 23 classes

### 2. Data Description
Data is obtained from this [repo](https://github.com/nluninja/nlp_datasets/tree/main/GUM).

- Number of instances - 44111 entries (**Train**), 18236 entries (**Test**)
- Number of classes - 2
  #### Attribute Information
  ##### Inputs
  - token: string feature
  ##### Output
  - ner_tag : a classification label , 23 classes
  
 ###  3.  Topic Modelling
 The Topics are analyzed via two methods:
   - Latent Dirichlet Allocation (LDA)
   - Negative Matrix Factorization (NMF)
   
 <p float="left">
   <img src="https://user-images.githubusercontent.com/103529789/209487141-717f4a28-51ba-410e-b0d8-e21969649e7f.png" width="350"/>
   <img src="https://user-images.githubusercontent.com/103529789/209487263-7ebc8005-9600-436c-bea3-7f81f446df13.png" width="350"/>
   </p>

   
  
 ### 4. EDA
 <p float="left">
  <img src="https://user-images.githubusercontent.com/103529789/209395989-6935edaa-2b24-4890-9b4e-d6d18122496e.png" width="350"/>
  <img src="https://user-images.githubusercontent.com/103529789/209487644-a24931a1-34de-428b-b83b-2834137adab3.png" height='315' width="450"/>
  </p>

  
  
 ### 5. Modelling Evaluation
 - Algorithms used
    - BI-LSTM
 - Metrics used: Accuracy, Precision,Recall, F1-Score
 
  ### 6. Results
  
   <p float="left">
  <img src="https://user-images.githubusercontent.com/103529789/209486618-6ae1d7a5-fd6f-44a9-99c1-e163efd7f4f8.png" width="380"/>
  </p>
