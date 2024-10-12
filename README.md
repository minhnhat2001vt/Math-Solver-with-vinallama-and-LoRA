# Math-Solver-with-vinallama-and-LoRA
# VinALlama 7B Chat - Vietnamese Math Solver

This project fine-tunes the [VinALlama 7B Chat model](https://huggingface.co/vilm/vinallama-7b-chat) to solve Vietnamese grade school math problems using multiple-choice questions. The model is trained with 4-bit quantization and Low-Rank Adaptation (LoRA) to improve memory efficiency while maintaining performance.

## Purpose

The goal is to create a model that solves Vietnamese math questions step-by-step, providing detailed explanations. This model aims to help students learn by showing them how to approach math problems.

## Features

- **LoRA Fine-tuning**: Efficient fine-tuning by modifying only specific model layers.
- **4-bit Quantization**: Reduces model memory usage with bitsandbytes.
- **Training with Vietnamese MCQ Dataset**: The model is trained on a dataset of math problems with detailed explanations.

## Inference

The model can take a math question, generate a step-by-step solution, and select the correct answer from multiple choices. It is useful for automated tutoring or educational assistance in Vietnamese.

   
## Model Hub

The trained model is available on Hugging Face: NhatNguyen2101/vinallama-peft-7b-math-solver.
