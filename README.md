# TransformerTextClassification
# AG News Classification with a Nano Transformer

This project demonstrates text classification using a simplified Transformer model, referred to as a "Nano Transformer," on the AG News dataset. The model is implemented in PyTorch and trained to categorize news articles into four classes: World, Sports, Business, and Science/Technology.

## Dataset

The AG News dataset is used for training and evaluation. It consists of short news articles and their corresponding labels. The dataset can be downloaded from Kaggle.

## Model

The Nano Transformer is an encoder-only Transformer model with a reduced number of layers and parameters compared to traditional Transformer architectures. It utilizes an embedding layer for tokens, sinusoidal positional embeddings, a single Transformer block (with multi-head attention and feed-forward layers), and a final linear layer for prediction.

## Training

The model is trained using the Adam optimizer and cross-entropy loss. Cosine annealing is employed for learning rate scheduling. Token dropping is applied during training as a regularization technique.

## Evaluation

The model's performance is evaluated on a held-out test set using metrics such as accuracy, precision, recall, and F1-score. A confusion matrix is also generated to visualize the classification results.

## Usage

1. Clone the repository.
2. Install the required dependencies: `pip install -r requirements.txt`.
3. Download the AG News dataset and place it in the designated data directory.
4. Run the code

## Results

The Nano Transformer achieves competitive accuracy on the AG News classification task. The results are presented in the evaluation script output and visualized in the generated plots.

## Contributing

Contributions to this project are welcome! Feel free to open issues or submit pull requests for bug fixes, enhancements, or new features.
