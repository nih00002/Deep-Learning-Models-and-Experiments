# Deep Learning Models and Experiments

A curated collection of deep learning implementations and experiments covering machine-learning foundations, computer vision, sequence modeling, representation learning, and transformer-based natural language processing.

The repository demonstrates a progression from core NumPy and PyTorch operations to convolutional neural networks, recurrent architectures, autoencoders, and modern transformer models.

## Repository Contents

| Notebook | Focus | Key Topics |
|---|---|---|
| `01_NumPy_ML_Foundations.ipynb` | Machine Learning Foundations | Matrix operations, ridge regression, softmax classification, PCA |
| `02_PyTorch_ML_Foundations.ipynb` | PyTorch Foundations | Tensors, autograd, optimization, classification, PCA |
| `03_CNN_CIFAR10.ipynb` | Computer Vision | CNNs, CIFAR-10, BatchNorm, dropout, ablation experiments, feature maps |
| `04_RNN_GRU_Language_Modeling.ipynb` | Sequence Modeling | RNNs, GRUs, character-level language modeling, text generation |
| `05_LSTM_Sentiment_Analysis.ipynb` | Sentiment Analysis | LSTMs, bidirectional networks, attention, model comparison |
| `06_Autoencoder_Representation_Learning.ipynb` | Representation Learning | Autoencoders, latent representations, reconstruction |
| `07_Transformers_NLP.ipynb` | Transformer NLP | DistilBERT, BERT, T5, sentiment classification, summarization |

## Topics Covered

The experiments span several areas of modern deep learning:

- NumPy and PyTorch machine-learning foundations
- Automatic differentiation and optimization
- Convolutional neural networks for image classification
- CNN architecture improvement and feature-map analysis
- Recurrent neural networks and GRUs
- Character-level language modeling and text generation
- LSTM-based sentiment classification
- Bidirectional recurrent networks and attention
- Autoencoder-based representation learning
- Transformer architectures for NLP
- BERT and DistilBERT sentiment classification
- T5 text summarization

## Technologies

- Python
- NumPy
- PyTorch
- Torchvision
- Scikit-learn
- Matplotlib
- Hugging Face Transformers
- Hugging Face Datasets
- Jupyter Notebook

## Repository Structure

```text
Deep-Learning-Models-and-Experiments/
├── README.md
├── requirements.txt
├── .gitignore
└── notebooks/
    ├── README.md
    ├── 01_NumPy_ML_Foundations.ipynb
    ├── 02_PyTorch_ML_Foundations.ipynb
    ├── 03_CNN_CIFAR10.ipynb
    ├── 04_RNN_GRU_Language_Modeling.ipynb
    ├── 05_LSTM_Sentiment_Analysis.ipynb
    ├── 06_Autoencoder_Representation_Learning.ipynb
    └── 07_Transformers_NLP.ipynb
```

## Selected Experiments

### CNN Image Classification

The CNN notebook explores image classification using CIFAR-10, beginning with a baseline convolutional architecture and extending it with techniques such as Batch Normalization and Dropout. It also includes architecture comparisons and feature-map visualization.

### RNN and GRU Language Modeling

The recurrent-network experiments investigate character-level language modeling, text generation at different temperatures, gradient behavior, sequence length, and a GRU-based extension.

### LSTM Sentiment Analysis

The LSTM experiments explore sequence classification using recurrent architectures, including bidirectional LSTMs, comparison with a vanilla RNN, confusion-matrix analysis, and an attention-based extension.

### Autoencoder Representation Learning

A fully connected autoencoder is used to learn a compact latent representation of synthetically generated high-dimensional data and reconstruct the original features.

### Transformer-Based NLP

The transformer experiments explore modern pretrained language models, including DistilBERT and BERT for sentiment classification and T5 for text summarization.

## Running the Notebooks

Clone the repository and install the required packages:

```bash
git clone https://github.com/nih00002/Deep-Learning-Models-and-Experiments.git
cd Deep-Learning-Models-and-Experiments
pip install -r requirements.txt
jupyter notebook
```

Then open the desired notebook from the `notebooks/` directory.

Some transformer experiments download pretrained models and datasets from Hugging Face and therefore require an internet connection and sufficient compute resources.

## Notes

These notebooks are curated portfolio versions of completed deep-learning experiments. Assignment-administration material has been removed while the technical implementations and experimental outputs have been retained.

The repository is intended to demonstrate practical experience across multiple neural-network architectures rather than present the collection as a single research study.
