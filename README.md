
# Introduction to ML - Decision Tree Coursework
This project implements a decision tree learning algorithm with cross-validation for classification. The project analyzes WiFi signal datasets and applies a decision tree learning method to classify the data. The code also calculates various metrics to evaluate model performance.

## Project Structure

- `notebook.ipynb` - Main notebook containing the decision tree learning code, tree visualization, and evaluation metrics.
- `requirements.txt` - File with required dependencies for the project.
- `wifi_db/` - Directory containing the datasets:
  - `clean_dataset.txt` - Clean dataset used for training and evaluation.
  - `noisy_dataset.txt` - Noisy dataset that can be used as an alternative for testing.

## Requirements

This project requires Python and the following dependencies:

- `matplotlib==3.9.2`
- `numpy==2.1.1`
- `scipy==1.14.1`

These dependencies are listed in `requirements.txt`.

## Installation & Usage

To set up the environment, open a terminal session on a lab machine and `cd` to the directory where you extracted the zip file to. Run the following commands in this terminal session
```bash
$ source /vol/lab/ml/intro2ml/bin/activate

(intro2ml) $ jupyter notebook
```
This will provide you with a link to jupyter notebooks - open the link in a browser and double click on `notebook.ipynb`.
You can then run each block to see the learning, visualisation and evaluation stages.
In order to run on the noisy dataset, change TEST_DATASET to 'wifi_db/noisy_dataset.txt' in the first block.
Similarly, you can can change TEST_DATASET to any filepath of your choice containing a dataset of the same format.
The generated decision tree will be shown in the notebook and also stored as `tree.png` in the root directory.
