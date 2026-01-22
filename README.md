# Vibe AI – Empathetic Best-Friend Chatbot

This project was built as part of the Vibe AI hiring assignment.  
The goal is to fine-tune an open-source Large Language Model (LLM) to behave like an empathetic, best-friend chatbot.

---

## Objective
- Improve empathetic responses compared to a base model
- Fine-tune using PEFT (QLoRA) under low compute constraints
- Demonstrate qualitative improvements in emotional understanding

---

## Model & Tools
- Base Model: Qwen2.5-7B-Instruct
- Fine-tuning Method: QLoRA (PEFT)
- Framework: HuggingFace Transformers
- Platform: Google Colab (GPU)

---

## Training Approach
- Supervised Fine-Tuning (SFT)
- Small curated empathy-focused conversational data
- Persona-based prompting (`<persona:best_friend><tone:warm>`)

---

## Results
- The fine-tuned model produces warmer, more empathetic responses
- Qualitative improvements observed compared to the base model

---

## How to Run
1. Open the notebook in Google Colab
2. Enable GPU (Runtime → Change runtime type → GPU)
3. Run all cells in order

---

## Notes
- This is a lightweight sanity-check fine-tuning due to compute constraints
- The focus is on correct methodology and explainability

- ---

## Submission & Review
This repository is submitted as part of the Vibe AI hiring assignment.  
Reviewer / Tagged for review: @ahan-2000

