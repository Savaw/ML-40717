# Machine Learning Course Projects

## Multi-Layer Perceptron

Implementation of an MLP model using PyTorch library. It also utilizes CUDA as device if available.

### Code

The code with description and comments can be found in [MLP.ipynb](MLP.ipynb).

### Dataset - FashionMNIST

This dataset contains 28*28 grayscale images of clothing items labeled into ten categories based on clothing type.
It includes a total of 60000 training samples and 10000 samples for testing.


## Learning To Rank

In this project, pairwise learning to rank strategy using logistic regression is implemented.

Implementation using Gradient Descent from scratch and the SKLearn library are both available.

### Code

The code with description and comments can be found in [LearningToRank.ipynb](LearningToRank.ipynb).

It expects the "MQ2007" dataset to be in the same directory as the notebook.

### Dataset - MQ2007

You can find the dataset [here](https://www.microsoft.com/en-us/research/project/letor-learning-rank-information-retrieval/letor-4-0/).

From the linked page:
> Each row is a query-document pair. The first column is relevance label of this pair, the second column is query id, the following columns are features, and the end of the row is comment about the pair, including id of the document. The larger the relevance label, the more relevant the query-document pair. A query-document pair is represented by a 46-dimensional feature vector.
