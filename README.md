# Dog Breed Vision V2 🐶

A deep learning project that classifies dog breeds from images using transfer learning with TensorFlow Hub and tf_keras.

This project was developed in Google Colab and demonstrates an end to end computer vision workflow: from data preparation and modeling, to monitoring and optimization.

 # Features

Preprocessing pipeline for large-scale dog image datasets

Transfer learning with pretrained CNN backbones

Training loop with TensorBoard logging and EarlyStopping

Scales from small subsets (1k images) to full datasets

Strong validation accuracy with consistent API usage (tf_keras)

# Process

Data Preparation – cleaned and structured thousands of labeled dog images.

Model Building – used TensorFlow Hub feature extractors with a custom classification head.

Training & Monitoring – trained with callbacks (TensorBoard & EarlyStopping) to stabilize performance.

Debugging – resolved framework mismatches (tf.keras vs tf_keras) to keep the pipeline consistent.

Scaling – validated on a smaller subset, then scaled to full dataset training.

# Results

Achieved strong validation accuracy with transfer learning

Clear and stable learning curves tracked in TensorBoard

Efficient training with early stopping to prevent overfitting


# Tech Stack

Python

TensorFlow & tf_keras

TensorFlow Hub

Google Colab
