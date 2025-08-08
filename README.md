# Pretrained Chatbot

## General Process & Overview

<p>This project was created for the Congressional App Challenge. LLMS and Transformers are an integral part of AI today. After working with numerous types of Neural Networks, I expanded to employ transformers in various text based tasks. Transformers can be used for many text based tasks, whether it be classification or text generation. Additionally, the use of a transformer solves the age-old problem: <a href="https://en.wikipedia.org/wiki/Vanishing_gradient_problem">the vanishing gradient problem</a>. </p>
<p>To create this project, I imported the <a href="https://huggingface.co/Qwen/Qwen3-4B">Qwen3-4B</a> model from Hugging Face. Then, using a dataset that I also found in Hugging Face, I fine-tuned the model, changing up the weights and biases. </p>

## Complications

<p>An LLM/Transformer that has been pretrained and posted on Hugging Face has already undergone intense training using extremely large datasets. Unfortunately, fine-tuning a model with a smaller dataset would most likely hinder the performance of the model, rather than help it. This proved to be evident while I pretrained the model, as not only did it take an absurd amount of time to train (15-17 hours), but it also performed worse than the pretrained model itself. Regardless, this project helped me gain the experience of pre-training a Hugging Face model, and how to improve its accuracy in future projets. </p>

## Tech Stack

- Jupyter
- Python
- PyTorch
- <a href="https://huggingface.co/">Hugging Face</a>

## How to Use

```bash
git clone https://github.com/aakashvishcoder/Pretrained-Chatbot.git
cd your-repo
