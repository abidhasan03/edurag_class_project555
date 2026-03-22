# 🧠 Multimodal RAG Notebooks (CLIP + SigLIP)

This repository contains a collection of Jupyter Notebooks demonstrating multimodal Retrieval-Augmented Generation (RAG) pipelines using CLIP and SigLIP as encoders, across several datasets including TextVQA, VQAv2, and PDF-based QA.

## 📁 Notebooks Included

- `textvqa+CLIP.ipynb`
- `textvqa_SIGLIP.ipynb`
- `vqav2_small_CLIP_plus_sentence.ipynb`
- `VQAv2_small_SIGLIP.ipynb`
- `PDF_RAG_SIGLIP+CLIP.ipynb`

## 🛠 Instructions

- All notebooks can be executed **independently**.
- The only exception is **`PDF_RAG_SIGLIP+CLIP.ipynb`**, which requires:
  - Replacing placeholder file paths with the **provided PDFs** and **JSON annotation files**.
  - Ensure the format and location of the files match what’s expected in the notebook.

## 💻 Environment Setup

To run these notebooks, install the required dependencies:

```bash
pip install -r requirements.txt
```

---

Feel free to explore, modify, and evaluate different configurations of multimodal RAG pipelines!
Coding for this repository was done with assistance of GPT. 
