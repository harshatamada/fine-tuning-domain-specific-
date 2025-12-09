CSE Expert System — Fine-Tuned Phi-3 Mini
This project is my first hands-on experience with fine-tuning a Small Language Model (SLM). 
I trained Phi-3 Mini by Microsoft using LoRA so that it can act as a CSE (Computer Science & Engineering) expert system for my college. 
The model is able to answer technical questions more accurately in the CSE domain.
Project Overview
Model Used: Phi-3 Mini (3B parameters)
Fine-tuning Method: LoRA (Low-Rank Adaptation)
Frameworks: PyTorch, Transformers
Platform Used: Google Colab (T4 GPU)
The goal was to learn the full fine-tuning workflow including dataset creation, adapters, training, and evaluation.
Why LoRA?
Instead of updating all 3B parameters, LoRA trains only ~0.1% of weights using adapter layers.
Benefits:
Faster training
Less GPU memory
No need to download model locally
Base model knowledge remains intact
