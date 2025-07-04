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

- XML Parsing.

Reads and extracts structured data from the annotated XML file

Handles elements such as: questions, summaries, reference answers, and focus annotations

Exploratory Data Analysis

Extracts metadata like question types, answer counts, and topical distributions

Prints or visualizes sample Q&A pairs

Data Structuring

Converts XML content into usable Python dicts or DataFrames for downstream tasks

Preprocessing for ML/NLP

(Optional) You can expand it to build training corpora, embeddings, or retrieval evaluation sets



