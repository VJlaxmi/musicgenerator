# MusicGen AI Composer

## Overview


MusicGen AI Composer is a project that leverages the power of MusicGen, a state-of-the-art AI model, to generate music from text descriptions. This project uses the Hugging Face Transformers library and PyTorch to implement the AI model, and Gradio to create an interactive user interface.

## Features

Text-to-music generation in 5-30 seconds

Custom control over music duration and randomness

Multi-instrument and multi-genre capability

User-friendly interface for easy interaction

## Technical Details

Model: MusicgenForConditionalGeneration 

Framework: PyTorch + 🤗 Transformers

Architecture: T5 encoder + EnCodec 32kHz decoder

Parameters: 300M (small), 1.5B (large)

Generation: Classifier-free guidance, temperature sampling

UI: Gradio
