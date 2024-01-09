# GPT-2 Based Q&A Chatbot
link to Colab:  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-hCUkHW3Qx-cP7cyq6-WZKoBVRluPEIJ)

This repository contains the code for a Q&A chatbot application leveraging the GPT-2 model. It is designed to provide intelligent, conversational responses to user queries, making it suitable for applications like customer service, information retrieval, and interactive dialogue systems.

## Features

- **GPT-2 and BERT Integration**: Utilizes the GPT-2 medium variant for generating conversational responses and BERT for question answering capabilities.
- **Custom Dataset Handling**: Includes scripts for processing and preparing custom datasets for training.
- **Efficient Training**: Implements a training pipeline using PyTorch and the Hugging Face Transformers library.
- **Modular Code Structure**: Easy to understand and modify to suit different use-cases or to experiment with different models.

## Prerequisites
- Python 3.8 or higher
- PyTorch (version as per your system's compatibility)
- Hugging Face's Transformers library
- Other dependencies listed in `requirements.txt`

## Installation

Clone the repository and install the required packages:

```bash
git clone https://github.com/your-github-username/gpt2-qa-chatbot.git
cd gpt2-qa-chatbot
pip install -r requirements.txt
