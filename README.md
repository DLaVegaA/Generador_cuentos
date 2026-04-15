# Multimodal Generative AI System for Illustrated Story Creation 📚🎨

This repository contains the implementation of an Artificial Intelligence pipeline capable of automatically generating short stories in Spanish and their respective illustrations, integrating Large Language Models (LLMs) and image generation models.

## 🚀 Key Achievement
**Accomplished** the co-development of an AI pipeline for Spanish illustrated stories, **as measured by** the successful training of a Mistral 7B model on a 55,000-story dataset, **by utilizing** QLoRA, PyTorch, and an Ollama-run image generator.

## ✨ Main Features
* **Text Generation:** Fine-tuning of **Mistral 7B** optimized for Spanish narratives using QLoRA.
* **Multimodal AI:** Automatic integration of text descriptions with diffusion models to create story-coherent images.
* **Data Pipeline:** Processing and cleaning of a massive 55,000-story dataset.
* **PDF Export:** Automatic generation of final documents with dynamic layouts (interleaved text and images).
* **Resource Efficiency:** Optimized implementation designed to run in resource-constrained environments (e.g., Google Colab T4).

## 🛠️ Technologies Used
* **Language:** Python
* **LLM Frameworks:** Hugging Face (Transformers, PEFT, Accelerate), Mistral AI.
* **Deep Learning:** PyTorch.
* **Image Generation:** Ollama (Local Image Model Integration).
* **Data Processing:** Pandas, NumPy.
* **Document Output:** FPDF (for final PDF creation).

## 📦 Project Structure
* `Generador_de_cuentos.ipynb`: Main notebook containing the training, inference, and PDF generation workflow.
* `data/`: (Optional) Scripts used for cleaning and structuring the 55,000-story dataset.
* `outputs/`: Examples of generated stories in PDF format.

## ⚙️ Setup and Installation
To replicate this project, using a GPU environment (NVIDIA T4 or higher) is highly recommended.

1. **Install dependencies:**
   ```bash
   pip install torch transformers peft accelerate bitsandbytes fpdf
