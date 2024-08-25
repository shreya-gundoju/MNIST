# MNIST HandWritten Digit Classification
This project demonstrates a neural network model built with Keras to classify handwritten digits from the MNIST dataset.

# Packages Used
**keras.datasets:** To load the MNIST dataset.

**matplotlib.pyplot:** For visualizing the dataset and model performance.

**keras.models.Sequential:** To construct the sequential neural network model.

**keras.layers.** Dense: To create fully connected layers in the model.

**keras.optimizers.SGD, Adam:** For optimizing the model during training.

**keras.callbacks.ModelCheckpoint:** To save the model at various training stages.

**keras.utils.to_categorical:**  For converting class vectors to binary class matrices.
# Model Overview
Data Ingestion: Loads and preprocesses the MNIST dataset.
Model Architecture: Sequential model with dense layers for classification.
Training: Optimized using SGD and Adam, with checkpointing for performance tracking.
Evaluation: Assesses the model's accuracy on the test set.
# Setup and Execution
Install Dependencies: Ensure you have the required packages installed.
Run the Model: Execute the script to train and evaluate the model.
