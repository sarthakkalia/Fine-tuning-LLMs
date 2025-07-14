# Fine-tuning-LLMs
fine-tune of different type LLMs with the various dataset (Available+Own) used for learning purpose.

This repository demonstrates fine-tuning techniques for low-parameter Large Language Models (LLMs) using several advanced methods:

* Parameter-Efficient Fine-Tuning (PEFT) with **LoRA** and **QLoRA**
* **Reinforcement Learning from Human Feedback (RLHF)**
* **Reinforcement Learning from AI Feedback (RLAIF)**

## Overview

The repository showcases practical examples and scripts for efficiently fine-tuning LLMs (1B–13B parameters). We cover:

* **LoRA** and **QLoRA** for low-resource environments.
* **RLHF** to align models with human preferences.
* **RLAIF** as a scalable alternative using AI-generated preference labels.

---

## Features

* Modular and reproducible fine-tuning pipelines.
* Support for Hugging Face Transformers and PEFT libraries.
* RLHF implementation using reward models and PPO training loops.
* RLAIF framework using synthetic preference datasets.

---

## ✨ Acknowledgements

* [Hugging Face Transformers](https://github.com/huggingface/transformers)
* [PEFT Library](https://github.com/huggingface/peft)
* [TRL Library](https://github.com/huggingface/trl)

---

## 📌 Notes

* For large model training, ensure you have access to GPUs with sufficient VRAM.
* For QLoRA, `bitsandbytes` and quantization setup is required.
* RLHF and RLAIF implementations require careful tuning of reward models and PPO hyperparameters.

---
