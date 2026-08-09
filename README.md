# Assignment 2 - Sentiment Classification

This project uses DistilBERT to classify movie reviews as negative (0) or positive (1).

## Model
I used the pretrained DistilBERT model with a sequence classification layer.

## Training
The training data was split into 80% training and 20% validation. Class weights were used because the training dataset contained more positive reviews than negative reviews.

- Optimizer: AdamW
- Learning rate: 2e-5
- Batch size: 8
- Epochs: 3
- Maximum token length: 256

## Results
- Validation accuracy: 75%
- Public test accuracy: 52.5%

## Running
Install the required packages with:

pip install -r requirements.txt

Then open stage1_notebook.ipynb.
