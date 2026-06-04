# Developing a Large Language Model in Meitei Mayek for the Manipuri Language

## 📖 Overview

This repository contains my B.Tech thesis submitted to the Department of Computer Science and Engineering, National Institute of Technology (NIT) Manipur.

The project focuses on developing a Large Language Model (LLM) for the Manipuri language written in its native **Meitei Mayek** script. Existing NLP research for Manipuri has largely focused on translation tasks and often relies on the Bengali script. This work aims to bridge that gap by creating a generative language model specifically for Meitei Mayek.

---

## 🎯 Objectives

* Build a high-quality Meitei Mayek text corpus from multiple data sources.
* Design and evaluate custom tokenizers for the Meitei Mayek script.
* Explore different approaches for language model training.
* Fine-tune a foundation model for Manipuri text generation.
* Evaluate model performance using quantitative and qualitative metrics.

---

## 🏗️ Methodology

The project was carried out in three major experiments:

### Experiment 1: BLOOMZ Fine-Tuning

* Fine-tuned BLOOMZ-1B1 using LoRA on a pilot Manipuri dataset.
* Evaluated the feasibility of adapting multilingual models to Meitei Mayek.

### Experiment 2: Custom Mini-GPT

* Built and trained a Mini-GPT style Transformer model from scratch.
* Trained exclusively on Meitei Mayek text data.

### Experiment 3: Mistral 7B Adaptation

* Constructed a large-scale Meitei Mayek corpus.
* Developed a custom SentencePiece tokenizer.
* Replaced the original vocabulary and fine-tuned Mistral 7B using LoRA.
* Trained on NVIDIA RTX PRO 5000 Blackwell GPU hardware.

---

## 📊 Dataset Sources

The corpus was created using data from:

* Hugging Face English-to-Meitei-Mayek Dataset
* E-Pao Manipuri News Archive
* OCR-extracted text from printed Meitei/Meetei script documents

The collected data was cleaned, normalized, converted from legacy fonts, and merged into a unified training corpus.

---

## 🛠️ Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* PEFT / LoRA
* SentencePiece
* Mistral 7B
* BLOOMZ
* NVIDIA GPU Acceleration

---

## 🚀 Key Contributions

* Developed a dedicated Meitei Mayek language corpus.
* Created a custom tokenizer optimized for the script.
* Compared multiple language modeling strategies.
* Fine-tuned a large language model for a low-resource indigenous language.
* Established a reproducible pipeline for future research in low-resource NLP.

---

## 📄 Thesis Report

The complete thesis report is available in:

`Thesis B.Tech 2026_compressed.pdf`

---

## 👨‍💻 Author

**Nelson Singh Shagolsem**
B.Tech, Computer Science and Engineering
National Institute of Technology Manipur

---

## 📌 Future Work

* Release cleaned training datasets.
* Open-source training and preprocessing pipelines.
* Improve model performance with larger corpora.
* Explore instruction tuning and conversational capabilities.
* Extend the methodology to other low-resource Indian languages.
