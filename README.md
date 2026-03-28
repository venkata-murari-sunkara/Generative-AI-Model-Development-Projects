# Generative AI & Deep Learning Model Development

This repository contains a collection of end-to-end machine learning pipelines, focusing on the architecture, training, and evaluation of advanced Deep Learning and Generative AI models. 

## Tech Stack
* **Languages:** Python
* **Models:** Transformers (GPT-2, BERT, T5, LLaMA 3.2), GANs, Tiny GPT
* **Frameworks:** Hugging Face Transformers, PyTorch/TensorFlow 
* **Environment:** Jupyter Notebook, Docker (containerized workflows)

---

## 📂 Projects

### 1. Transformer Architectures for NLP
* **Models:** GPT-2, BERT, T5
* **Dataset:** CNN/Daily Mail
* **Objective:** Architected and fine-tuned Large Language Models to perform high-fidelity abstractive and extractive text summarization.
* **Key Results:** T5 (encoder-decoder) achieved the highest performance across all metrics, yielding a ROUGE-1 score of 0.403 and the lowest perplexity (7.79) despite having the fewest parameters. The analysis successfully demonstrated that encoder-decoder architectures are optimal for conditional generation tasks like summarization, outperforming both GPT-2 and BERT.

### 2. Generative vs. Discriminative Modeling (GANs)
* **Models:** Generative Adversarial Networks (GANs), Logistic Regression
* **Dataset:** MNIST
* **Objective:** Designed and evaluated generative models to synthesize complex image patterns from noise, comparing performance against discriminative approaches.

### 3. Prompt Engineering & Local LLM Deployment
* **Model:** LLaMA 3.2 (1B)
* **Environment:** Deployed locally via Ollama
* **Objective:** Executed advanced prompt engineering techniques to optimize the summarization of fixed paragraphs, maximizing contextual accuracy.

### 4. Comparative Training Methods (RLHF & Fine-Tuning)
* **Model:** Tiny GPT
* **Dataset:** WikiText-2
* **Objective:** Evaluated the performance trade-offs between Unsupervised Pre-Training, Supervised Fine-Tuning (SFT), and Reinforcement Learning approaches.

### 5. Multimodal Vision-Language & Code Generation Models
* **Models:** Qwen2.5-VL-7B (Multimodal), DeepSeek-Coder-6.7B
* **Environment:** Google Colab (T4 GPU), Hugging Face
* **Objective:** Conducted practical demonstrations of emerging models, including image-based question answering (object counting, spatial reasoning) and specialized code generation.

---

## How to Run
1. Clone this repository.
2. Ensure you have Jupyter Notebook installed or run the `.ipynb` files via Google Colab.
3. Required dependencies can be found within the respective notebook cells.
