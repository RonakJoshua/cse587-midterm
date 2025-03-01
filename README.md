# Midterm Project for CSE 587

---

This is Ronak Singh's CSE 587 midterm project repository. The report containing all training and model details, as well as all experiments and results can be found in `report.pdf`.

### Steps to Run Code

First, begin by downloading the `GoogleNews-vectors-negative300.bin` file, containing the pretrained Word2Vec model. This model can be downloaded from [here](https://github.com/mmihaltz/word2vec-GoogleNews-vectors). Add the binary file to the root directory of this repository (it isn't included by default in this repo since the file is so large).

Next, run `pip install -r requirements.txt` to install all required packages.

To run the training loop, open and run the `train_eval.ipynb` file. This will retrain the model from scratch.

To run the experiments related to introducing typos to the dataset, open and run the `experiments.ipynb` file. To view all plots (and code used to generate the plots), open the `plots/` folder.

### Extra Information (for Reference)

- The dataset can be found as a csv file in the `kaggle_data/` folder.
- The final trained model is stored in the `epoch_typo_15.pth` file.
- All training was performed using a rented NVIDIA A4000 GPU on Paperspace.
