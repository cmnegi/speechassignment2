# speechassignment2
Speech Assignment2
Assignment 1: Speech Enhancement

Objective

Enhance the speech of each speaker in a multi-speaker environment using speaker verification models.

Steps to Follow

Dataset Preparation

Download the VoxCeleb1 and VoxCeleb2 datasets.

Use the VoxCeleb1 (cleaned) file for evaluation.

The VoxCeleb2 dataset will be used for fine-tuning.

Pre-trained Speaker Verification ModelsChoose one from the following models:

hubert large

wav2vec2 xlsr

unispeech sat

wavlm base plus

Download the pre-trained models from Hugging Face

Speaker Verification and Evaluation

Perform speaker verification using the pre-trained model.

Evaluate using the list of trial pairs from VoxCeleb1 (cleaned).

Fine-Tuning with LoRA and ArcFace Loss

Fine-tune the selected speaker verification model using LoRA (Low-Rank Adaptation) and ArcFace loss.

Use the First 100 identities (sorted in ascending order) for training.

Use the remaining 18 identities for testing.

Performance Comparison MetricsCompare the pre-trained and fine-tuned models based on:

Equal Error Rate (EER) (%)

True Acceptance Rate (TAR) @ 1% False Acceptance Rate (FAR)

Speaker Identification Accuracy

Assignment 2: MFCC Feature Extraction and Comparative Analysis of Indian Languages

Objective

Extract and analyze Mel-Frequency Cepstral Coefficients (MFCC) for Indian languages.

Steps to Follow

Dataset Preparation

Download the Audio Dataset with 10 Indian Languages from Kaggle.

MFCC Feature Extraction

Implement a Python program to extract MFCC features from each audio sample.

Visualization of MFCC Spectrograms

Generate and visualize MFCC spectrograms for a representative set of samples from at least 3 different Indian languages.

Use libraries like Librosa, Matplotlib, and NumPy for visualization.

Comparative Analysis

Compare the MFCC spectrograms across different languages.

Identify and discuss visual similarities and differences in spectral patterns.

Optional: Statistical Analysis

Compute the mean and variance of MFCC coefficients.

Quantify differences between languages using statistical measures.
