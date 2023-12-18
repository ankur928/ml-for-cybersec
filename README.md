
# Enhancing Resilience to Adversarial Attacks in Fake News Detection

## Overview
This repository introduces an advanced Graph Neural Network (GNN) model implementation for fake news detection, emphasizing enhanced resilience against adversarial attacks through the integration of the Fast Gradient Sign Method (FGSM).

## Key Contributions
- **Adversarial Training with FGSM**: A novel training approach to improve the model's defense against adversarial attacks.
- **Model Training Adaptation**: Modified the training process to include adversarial examples, bolstering the model's detection capabilities in adversarial scenarios.
- **Performance Evaluation**: Conducted thorough experiments to demonstrate the improved robustness of the models under adversarial conditions.

## Installation and Setup
### Prerequisites
- Python 3.6 or higher
- PyTorch 1.6 or higher
- PyTorch-Geometric 1.6.1 or higher

### Steps
```bash
git clone https://github.com/your-repository/GNN-FakeNews.git
cd GNN-FakeNews
pip install -r requirements.txt
```

## Datasets
The project uses the GossipCop and PolitiFact datasets. Download the datasets from the provided links and place them under the `\data\{dataset_name}\raw\` directory in the cloned repository.

- Google Drive: [Download Link](https://drive.google.com/drive/folders/1OslTX91kLEYIi2WBnwuFtXsVz5SS_XeR?usp=sharing)
- Baidu Disk: [Download Link](https://pan.baidu.com/s/1NFtuwzmpAezNcJzlSlduSw) (Password: fj43)

## Running the Notebook
The project's main code is in a Jupyter Notebook format. You can run the notebook either locally using Jupyter Notebook or remotely on Google Colab.

### Using Jupyter Notebook
After installing the prerequisites, launch Jupyter Notebook:
```bash
jupyter notebook
```
Navigate to the cloned repository's directory and open the `.ipynb` file. Run the cells in the notebook to train the model and view results.

### Using Google Colab
1. Upload the `.ipynb` file to your Google Colab workspace.
2. Upload the dataset to Google Drive and mount the drive in Colab to access the datasets.
3. Execute the notebook cells to run the model.
