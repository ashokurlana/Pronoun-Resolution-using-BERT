# Pronoun resolution on GAP Dataset

This repository contain relevant code (in form of .ipynb) to perform the task of pronoun resolution using end-to-end neural co-reference resolution system. Our implementation makes use of BERT based embeddings to generate vector representation for spans of text. It then uses a FFNN to ranking candidate antecedent spans for the given pronoun.

The current code performs pronoun resolution on the [GAP Dataset](https://github.com/google-research-datasets/gap-coreference).

## Running the code
Start up a IPython server instance to load the file and execute all cells.
