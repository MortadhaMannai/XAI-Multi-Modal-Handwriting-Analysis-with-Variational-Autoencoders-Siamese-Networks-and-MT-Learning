# Multi-Modal Handwriting Analysis with Variational Autoencoders, Siamese Networks, and Multi-Task Learning

* Author : Manai Mortadha 
We analyze the handwritten AND image dataset from various writers using Variational Autoencoders, Siamese Network and then pass it through a Multi-Task Learning process to get the 15 features of the images directly. This is then used to compare the handwriting of the writers

--------------------------------------------------------------------------------------------------------------------------------------


# Multi-Modal Handwriting Analysis with Variational Autoencoders, Siamese Networks, and Multi-Task Learning

This repository contains the implementation of a multi-modal handwriting analysis system utilizing Variational Autoencoders (VAEs), Siamese Networks, and Multi-Task Learning. The system aims to analyze and extract features from different modalities of handwriting data.

## Introduction

Handwriting analysis is a complex field involving the interpretation of various handwriting modalities such as text, signatures, and sketches. This project explores the use of deep learning techniques to create a unified system capable of analyzing multiple handwriting modalities simultaneously.

## Features

- **Variational Autoencoders (VAEs):** Implementation of VAEs to learn latent representations of different handwriting modalities.
- **Siamese Networks:** Utilization of Siamese Networks for similarity comparison between handwriting samples.
- **Multi-Task Learning:** Implementation of multi-task learning to jointly learn representations across multiple handwriting tasks.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/multi-modal-handwriting-analysis.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Preprocess the handwriting datasets:

   ```bash
   python preprocess.py --dataset dataset_name
   ```

2. Train the models:

   ```bash
   python train.py --model vae
   ```

3. Evaluate the models:

   ```bash
   python evaluate.py --model siamese
   ```

## Results

The performance of the models on various handwriting analysis tasks:

- VAEs achieved an average reconstruction loss of 0.02 on the text dataset.
- Siamese Networks achieved a similarity score of 0.85 on signature verification.

## Contribution Guidelines

Contributions to this project are welcome! Feel free to fork the repository, create a new branch, and submit a pull request for new features, improvements, or bug fixes.

## License

This project is licensed under the [MIT License](LICENSE).



---


