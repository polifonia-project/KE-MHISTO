# KE-MHISTO: towards a Multilingual Historical Knowledge Extraction benchmark for addressing the long-tail problem
A **multilingual** benchmark for **Entity Linking** and **Question Answering** on historical knowledge in the music domain.
## 📚Paper Abstract
Large Language Models (LLMs) struggle when probed for "long-tail knowledge": information that is rarely encountered during their training phase. Benchmarks focused on historical documents can systematically evaluate SotA KE methods on real-world data characterized by long-tail knowledge.
This paper introduces KE-mHISTO, a multilingual benchmark for Entity Linking and Question Answering on historical knowledge in the music domain, available in Italian and English. We show how KE-mHISTO is significantly better at covering long-tail knowledge than existing alternatives. Crucially, KE-mHISTO presents significant challenges for State of Art models. Our experiments reveal that smaller models trained in a multilingual setting achieve performance comparable to significantly larger models, showing the potential of efficient, language-aware approaches for long-tail knowledge extraction.

## 💻 Datasets and Evaluation scripts
KE-mHISTO comprises two bi-lingual (Italian/English) datasets: (**MHERCL**) for NER and EL tasks and (**DynaKnowledge** aka DK) for QA. <br>
All datasets are included in the *Datasets* folder. <br>
We investigate the performances of **Named Entity Recognition (NER)**, **Entity Linking (EL)**, and **Question Answering (QA)** models. <br>
The *Tasks* folder contains the predictions of each tested model for every task, along with the corresponding evaluation Jupyter notebook.

