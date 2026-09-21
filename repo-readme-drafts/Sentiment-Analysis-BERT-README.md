# Sentiment Analysis with BERT

Fine-tuning BERT for multi-class emotion classification from text.

This notebook walks through a practical NLP training workflow: loading the emotion dataset, encoding labels, tokenizing text for BERT, preparing PyTorch dataloaders, fine-tuning a sequence classification model, and evaluating predictions with classification metrics.

## What It Covers

- Loads train, validation, and test splits from the Kaggle `emotions-dataset-for-nlp` dataset.
- Encodes emotion labels for supervised classification.
- Uses `bert-base-uncased` tokenization with padded attention masks.
- Fine-tunes `BertForSequenceClassification` with PyTorch.
- Tracks loss and learning rate during training.
- Evaluates predictions with confusion matrix and classification report.
- Includes optional model/tokenizer saving code for later reuse.

## Stack

- Python
- PyTorch
- Hugging Face Transformers
- pandas and NumPy
- scikit-learn
- Matplotlib and Seaborn
- Kaggle Notebook

## Dataset

The notebook expects the Kaggle dataset at:

```text
/kaggle/input/emotions-dataset-for-nlp/
```

Expected files:

```text
train.txt
test.txt
val.txt
```

## How To Run

1. Open the notebook in Kaggle or another environment with GPU support.
2. Attach the `emotions-dataset-for-nlp` dataset.
3. Run the cells from top to bottom.
4. Review the classification report and confusion matrix after training.

## Notes

This is an experiment notebook rather than a packaged application. The next improvement is to add a `requirements.txt`, split reusable training/evaluation code into scripts, and save final metrics in the repository.

