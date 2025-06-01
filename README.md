# Critical Question Generation using Fine-tuned Flan-T5 Model

This repository provides code, experiments, and a detailed report for generating critical questions from text passages using a fine-tuned [Flan-T5](https://huggingface.co/google/flan-t5-small) language model. The project was developed as a term project to investigate the effectiveness of large language models in supporting deep reading comprehension and educational tasks.

## Project Overview

- **Objective:**  
  Automatically generate high-quality, thought-provoking ("critical") questions from reading passages to assist educational and research activities.

- **Approach:**  
  - Utilizes the Flan-T5 model, a widely-used sequence-to-sequence transformer, as the base.
  - Fine-tuning performed on open datasets curated for question generation tasks.
  - All experimentation and analysis are conducted using Jupyter Notebooks.

- **Evaluation:**  
  - The system is evaluated using established natural language metrics such as BERTScore and STS Similarity score specific for this task.
  - Results and analysis are available in the final project report (see below).

## Repository Structure

- **Jupyter Notebooks:**  
  All code for data loading, preprocessing, model fine-tuning, and evaluation is available as Jupyter notebooks for reproducibility and easy experimentation.

- **Project Report:**  
  The detailed methodology, results, and discussion are documented in  
  [`495922_499564_500019 - Term_Project_Report - Critical_Questions_Generation_Task.pdf`](495922_499564_500019%20-%20Term_Project_Report%20-%20Critical_Questions_Generation_Task.pdf).

- **Dependencies:**  
  Primarily uses the following libraries:
  - [HuggingFace Transformers](https://github.com/huggingface/transformers)
  - [HuggingFace Datasets](https://github.com/huggingface/datasets)
  - [HuggingFace Evaluate](https://github.com/huggingface/evaluate)
  - [Sentence-BERT](https://www.sbert.net/)

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/HussainAhmed10/Critical-Question-Generation-using-Fine-tuned-Flan-T5-Model.git
   cd Critical-Question-Generation-using-Fine-tuned-Flan-T5-Model
   ```

2. **Open and run the Jupyter notebooks** to reproduce experiments or adapt to your own data.

## References and Links

- **Project Report:**  
  [Term Project Report (PDF)](495922_499564_500019%20-%20Term_Project_Report%20-%20Critical_Questions_Generation_Task.pdf)
- **Model Card:**  
  [Flan-T5 on HuggingFace](https://huggingface.co/google/flan-t5-small)
- **Related Paper:**  
  [Critical Question Generation Shared Task (ArXiv)](https://arxiv.org/abs/2505.11341)

## Citation

If you use this repository, code, or findings for your research, please cite the project report or the related [ArXiv paper](https://arxiv.org/abs/2505.11341).
