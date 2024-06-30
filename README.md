# Machine Translation Model Training and Evaluation using mT5

This project focuses on training and evaluating a machine translation system using the multilingual T5 (mT5) model, capable of translating text between English and Japanese.

## Project Overview

This project implements a complete pipeline for fine-tuning the mT5 model on a custom dataset. It includes data preprocessing, model training, evaluation, and visualization of results.

## Features

- **Data Preprocessing**: Tokenization and preparation of multilingual text data.
- **Model Training**: Fine-tuning of the mT5 model with support for learning rate scheduling and checkpointing.
- **Evaluation**: Calculation of BLEU scores to evaluate translation quality.
- **Visualization**: Comprehensive visualizations of training loss, BLEU scores, learning rate schedules, and token length distributions.

## Technologies Used

- **Programming Language**: Python
- **Deep Learning Framework**: PyTorch
- **NLP Library**: Hugging Face Transformers
- **Data Visualization**: Matplotlib, Seaborn
- **Development Environment**: Google Colab
- **Evaluation Metrics**: BLEU score (using NLTK)

## Getting Started

### Prerequisites

- Python 3.x
- PyTorch
- Hugging Face Transformers
- NLTK
- Seaborn
- Matplotlib

## License
This project is proprietary, and all rights are reserved. You may not use, copy, modify, or distribute this code without explicit permission from the author.

