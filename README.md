## NPR Detection

This repository contains a Jupyter Notebook implementation of the Normalized Perturbation Ratio (NPR) method for detecting AI-generated text.

## Files

Github_NPR.ipynb – Main notebook with full pipeline (data loading → perturbation → scoring → evaluation).

requirements.txt – Python dependencies to run the notebook.

## Inside the notebook:

1-Load dataset

2-Generate perturbations with T5-base

3-Score text with chosen models (GPT, Pythia, etc.)

4-Compute NPR values

5- Using AUROC, Precision, Recall, F1, Accuracy


## Datasets

Datasets are not included in this repo. Please download separately and update paths in the notebook:

Kaggle – Essays Dataset: https://www.kaggle.com/datasets/sunilthite/llm-detect-ai-generated-text-dataset

Hugging Face – Text Sentences Datasets: https://huggingface.co/datasets/shahxeebhassan/human_vs_ai_sentences

Hugging Face - Fake News Dataset: https://huggingface.co/datasets/ErfanMoosaviMonazzah/fake-news-detection-dataset-English

## Output

1-The notebook produces:

2-Detection scores for each model

3-Evaluation metrics (AUC, precision, recall, F1, accuracy)

4-Logs and CSVs of results

## License

This code is provided for educational and research purposes.




# Note on Running Experiments  
**The notebook combines small and large model evaluations in a single cell for convenience.  
If you encounter errors, it is recommended to separate the code for small and large models into different cells and run them individually.  
This makes debugging easier and saves time when an error occurs in one model without interrupting the others.**
