# Medical Question Answering with TREC LiveQA Data

This repo leverages the TREC 2017 LiveQA-Medical dataset to explore medical question answering using retrieval-based techniques. The dataset provides real-world, consumer health questions and curated answers, offering a valuable foundation for training and evaluating QA systems.

## Dataset
The dataset contains:

- 100+ medical questions from real users.

Each question includes:

- Original question and paraphrase.

- Medical subject.

- Annotations (problem, drug, treatment).

- Multiple reference answers with URLs and comments.

This dataset is ideal for:

- Biomedical question answering.

- Information retrieval and summarization.

- Clinical research.

## Notebook Features

This repo explores medical question answering using the TREC 2017 LiveQA-Medical dataset, which contains real world consumer health questions and expert reviwed answers. The goal is to preprocess and structure this dataset for downstream tasks such as information retrieval, question classification, and evaluation of medical QA systems.

The dataset includes more than 100 user-submitted medical questions, each annotated with a paraphrased version, medical topic, and semantic metadata like question type (e.g., treatment, cause, symptom) and focus (e.g., diseases, drugs). Additionally, each question is paired with one or more reference answers that are sourced from authoritative websites such as MedlinePlus or PubMed, along with comments that assess the relevance or quality of each response.

The accompanying notebook (QA.ipynb) is designed to parse the XML file and extract its rich structure into usable Python formats such as dictionaries or dataframes. It includes utilities to explore the content, count the number of answers per question, visualize question categories, and prepare the data for integration into retrieval-based or generative QA systems. While the notebook focuses on data exploration and structuring, it provides a strong foundation for building retrieval pipelines, fine-tuning large language models, or benchmarking QA performance using human-annotated references.

This work serves as a valuable stepping stone toward building biomedical question-answering systems that can support patient education, clinical decision-making, or healthcare search engines.



