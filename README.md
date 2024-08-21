# Training a GCN-based Edge Classifier

This Jupyter notebook demonstrates how to train a Graph Convolutional Network (GCN) for
edge classification tasks using various approaches. It begins with a basic method of
generating random node features and edges for each graph independently, then explores
more sophisticated approaches where learnable node embeddings are used. However, it also
highlights the pitfalls of treating all graphs in a batch as part of a single large
graph without properly adjusting the edge indices.

## Prerequisites

1. A unix or unix-like x86 machine
1. python 3.10 or higher.
1. Running in a virtual environment (e.g., conda, virtualenv, etc.) is highly
   recommended so that you don't mess up with the system python.
1. Install the requirements by running `pip install -r requirements.txt`

## Jupyter Notebooks

- [Training a GCN-based edge classifier](gnn-edge-classifier.ipynb)

## Contributing

Contributions are what make the open source community such an amazing place to be learn,
inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
1. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
1. Run `make test && make style && make quality` in the root repo directory, to ensure
   code quality.
1. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
1. Push to the Branch (`git push origin feature/AmazingFeature`)
1. Open a Pull Request

## Authors

- [Taewoon Kim](https://taewoon.kim/)
