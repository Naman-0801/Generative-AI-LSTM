# LSTM Text Generation – Generative AI Task

## Dataset
Shakespeare Complete Works (Public Domain)  
Source: https://www.gutenberg.org/files/100/100-0.txt

## Preprocessing
- Lowercasing
- Removing punctuation
- Word-level tokenization
- Sequence length = 20

## Model Architecture
- Embedding Layer
- LSTM Layer
- Dense Softmax Output

## Training
- Loss: Sparse Categorical Crossentropy
- Optimizer: Adam
- EarlyStopping used

## Text Generation
The model generates text iteratively based on a seed input.

## Sample Output
Generated text samples are included in the notebook.
