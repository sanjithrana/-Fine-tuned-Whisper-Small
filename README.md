Fine-Tuned Whisper Small

This repository contains experiments and notebooks for fine-tuning OpenAI's Whisper-Small model for automatic speech recognition (ASR). Whisper is a state-of-the-art transformer-based model capable of transcribing speech, detecting language, and performing translation. In this project, the Whisper-Small variant was fine-tuned on custom audio data to improve performance on domain-specific speech.

Features

Fine-tuning pipeline for Whisper-Small using Hugging Face 🤗 Transformers.

Preprocessing scripts for preparing audio and transcription datasets.

Jupyter notebooks demonstrating training, evaluation, and inference.

Support for custom datasets in .wav or .mp3 format with text transcripts.

Improved accuracy compared to the base Whisper-Small on specialized audio.


Repository Structure

Fine_tuned_Whisper_Small.ipynb → Initial fine-tuning notebook.

Fine_tuned_Whisper_Small_final.ipynb → Final version with evaluation.

data/ (optional) → Folder for dataset preparation.

README.md → Project overview and instructions.


Getting Started

1. Clone the repo:

git clone https://github.com/sanjithrana/-Fine-tuned-Whisper-Small.git
cd -Fine-tuned-Whisper-Small


2. Install dependencies:

pip install -r requirements.txt


3. Open the fine-tuning notebook and run the cells to reproduce training.



Future Work

Benchmarking against other Whisper variants (medium, large).

Adding support for multi-language fine-tuning.

Exporting models for deployment (TorchScript, ONNX).
# -Fine-tuned-Whisper-Small