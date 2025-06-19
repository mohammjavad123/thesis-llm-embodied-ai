# LLM-Guided Perception for Embodied AI in AI Habitat

This repository contains the final thesis report for the Master's thesis titled **"LLM-Guided Perception for Embodied AI in AI Habitat"**, completed as part of the Master's program in Artificial Intelligence at the University of Padua, under the supervision of **Prof. Lamberto Ballan** (Visual Intelligence and Machine Perception [VIM] Group).

## 📘 Abstract

This thesis presents a modular vision system for embodied agents that enables open-world object navigation in 3D environments. The system leverages **Large Language Models (LLMs)** to guide perception through **prompt-based control** of modular components, supporting flexible and generalizable behavior across unseen scenarios.

We fine-tuned state-of-the-art object detectors (**YOLO, DETR**) and integrated **CLIP** for **open-vocabulary recognition**, enabling recognition of novel objects beyond the training set. A **memory-enhanced filtering mechanism** was also implemented to improve detection stability and reduce false positives.

Experiments were conducted using a custom annotated dataset generated in **Habitat-Sim**, featuring 6000+ synthetic images based on **HM3D scenes**, expanded to 9000 with augmentations and over 13,000 object instances. Results on the **MultiON 3-ON task** demonstrated strong generalization and significant improvements over baseline end-to-end navigation methods, including a **+26% success rate** and **+24% progress gain** compared to ProjNeuralMap.

## 📄 Thesis PDF

The full thesis report is available in this repository:  
📎 [`LLM_Guided_Perception_Thesis.pdf`](./LLM_Guided_Perception_Thesis.pdf)

## 🧠 Key Contributions

- ✅ Introduced a **modular perception architecture** for embodied agents
- 🎯 Fine-tuned **YOLO and DETR** for custom detection in 3D navigation
- 🧠 Integrated **LLMs** to coordinate perception modules through **prompt engineering**
- 🖼️ Incorporated **CLIP** for zero-shot, open-vocabulary classification
- 🧮 Implemented a **memory-based filtering** mechanism for detection refinement
- 🧪 Built a synthetic dataset with **Habitat-Sim** and performed evaluation on **MultiON 3-ON**

## 🛠️ Technologies & Frameworks

- Python, PyTorch
- YOLOv8, DETR (Facebook AI Research)
- CLIP (OpenAI)
- Habitat-Sim, Habitat-Lab
- Transformers (Hugging Face)
- Prompt engineering with LLMs (e.g., GPT-based models)

## 📊 Results Summary

| Model        | Success Rate (SR) | Progress (%) | SPL | PPL |
|--------------|-------------------|---------------|-----|-----|
| ProjNeuralMap | 31%              | 41%          | —   | —   |
| **TANGO (Ours)** | **57%**        | **65%**      | ↑   | ↑   |

> Note: Full experimental setup, metrics, and analysis are in the thesis.

## 👨‍🏫 Supervisor

**Prof. Lamberto Ballan**  
Visual Intelligence and Machine Perception (VIM) Group  
Department of Mathematics, University of Padua  
🌐 [http://www.lambertoballan.net](http://www.lambertoballan.net)

## 🧑‍💻 Author

**Mohammadkazem Rajabi**  
Master in Artificial Intelligence – University of Padua  
✉️ mohammadkazem.rajabi@studenti.unipd.it  
🔗 [LinkedIn](https://www.linkedin.com/in/mohammadkazem-rajabi-3b5a121ab)  
🔗 [GitHub](https://github.com/mohammjavad123)

## 📌 Citation

If you reference or build upon this work, please cite the thesis report (available in PDF).