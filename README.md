This repository contains the implementation of a toxic speech identification classifier developed in the context of the emoBot project, an LLM-based educational system for second/foreign language learning.
The classifier is designed to detect both explicit and implicit toxic language in educational interactions and supports downstream tasks such as:
- content filtering
- safe dialogue generation
- detoxification pipelines
The work emphasizes linguistically informed annotation and ethically grounded NLP practices.

**Repository structure**
```bash
.
├── data/              # Datasets (DE, EL splits)
├── models/            # Trained models (to be added)
├── notebooks/
│   └── toxic_classifier_training.ipynb #notebooks for experimentation
├── src/               # Training, evaluation, inference scripts (to be added)
├── results/           # Evaluation outputs (to be added)
└── README.md



```

**Datasets**

The dataset consists of German (DE) and Greek (EL) data.

The corpus has been split into training, development, and test sets.


| Language     | Dev | Train | Test | Total |
|--------------|-----|-------|------|-------|
| German (DE)  |     |       |      |       |
| Greek (EL)   |     |       |      |       |
| **Total**    |     |       |      |       |


**Team**

Voula Giouli, Aristotle University of Thessaloniki & ILSP, ATHENA Research Centre

Stella Markantonatou, ILSP, ATHENA Research Centre

Antonis Balas, Aristotle University of Thessaloniki

Elina Zioga, Aristotle University of Thessaloniki

Rodanna Konstantinidi, Aristotle University of Thessaloniki

Elena Triantafyllidi, Aristotle University of Thessaloniki


**To cite this work**


TBD


**Acknowledgements**

This research was supported by the National Recovery and Resilience Plan (NRRP) “Greece 2000” under the ``Clusters of Research Excellence'' (CREs) program, SUB1.1, with project code \textgreek{ΟΠΣ ΤΑ 5180519} and title ``Interactive Agent with Emotional Intelligence for Second/Foreign Language Learning'', Acronym: ``EmoBot''.

