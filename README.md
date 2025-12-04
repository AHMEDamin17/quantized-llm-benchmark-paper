# 📄 Research Paper Draft: Benchmarking Quantized LLMs

**Title:** Benchmarking Quantized Open-Source LLMs for Complex Reasoning and Faithfulness in Resource-Constrained RAG Pipelines  
**Target Conference:** ICISSC / Springer LNCS  
**Status:** Draft / In-Progress

## 📌 Abstract
This paper presents a comparative benchmark of Llama-3 8B, Mistral 7B, and Phi-3 Mini in a resource-constrained RAG environment (16GB VRAM, 4-bit quantization). We introduce "GlobalQA," a novel protocol for testing corpus-level reasoning. Results indicate Llama-3 8B offers the optimal balance of speed (18.1s) and logical consistency, while Mistral 7B suffers from a "verbosity trap."

## 📂 Repository Contents
* **`main.tex`**: The complete LaTeX source code for the paper (Springer format).
* **`images/`**: Contains the architecture diagram, speed charts, and failure tables used in the figures.

## 🖼️ Figures Preview
### Figure 1: Architecture
![RAG Pipeline](rag_architecture_diagram.png)

### Figure 2: Results
![Speed Chart](inference_speed_chart.png)

---
*Draft maintained by Ahmed Amin K. and Team.*
