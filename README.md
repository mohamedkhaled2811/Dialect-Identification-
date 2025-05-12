# Arabic Dialect Identification with BERT Models and Contrastive Learning

This repository provides a Jupyter notebook for Arabic dialect identification, leveraging transformer-based models and advanced training techniques. The notebook facilitates preprocessing of Arabic text, model fine-tuning, and evaluation for classifying dialects such as Egyptian, Gulf, Levantine, and others.

**Key Features:**

`Pre-trained Model`: Utilizes aubmindlab/bert-large-arabertv02-twitter and UBC-NLP/MARBERTv2, both optimized for Arabic NLP tasks, particularly on social media text.

`Dual Loss Functions`: Implements a combination of `Supervised Contrastive Loss` and `Cross-Entropy Loss` during training to enhance representation learning and classification accuracy.

`Dataset`: Employs the dataset from the NADI 2023 Shared Task, which includes tweets labeled by country-level dialects across 21 Arab countries. For more details on the dataset, refer to the [NADI 2023 Shared Task overview](https://aclanthology.org/2023.arabicnlp-1.62/).

