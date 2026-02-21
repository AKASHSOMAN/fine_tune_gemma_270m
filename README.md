# Fine-tuning Gemma 3 270M for Grammar Correction

This repository demonstrates how to fine-tune **Gemma 3 270M** for **grammatical error correction (GEC)** using **QLoRA** and the Hugging Face **TRL** library.  
The workflow is optimized for **memory efficiency** and is designed to run smoothly on **Google Colab**.

---

## 🚀 What this project covers

- Loading and preprocessing a grammar correction dataset
- Formatting data in a chat-style (system / user / assistant)
- Baseline evaluation of the base Gemma model
- Fine-tuning using **Quantized LoRA (QLoRA)**
- Saving LoRA adapters to Google Drive
- Pushing the fine-tuned model to Hugging Face Hub
- Running inference using the published model

---

## 🧠 Model details

- **Base model:** Gemma 3 270M  
- **Task:** Grammatical Error Correction  
- **Fine-tuning method:** QLoRA (parameter-efficient)
- **Training framework:** Hugging Face TRL (SFT)
- **Quantization:** 4-bit (bitsandbytes)

---

## 📓 Training notebook

The full fine-tuning pipeline is available as a Google Colab notebook:

👉 **Open in Colab:**  
