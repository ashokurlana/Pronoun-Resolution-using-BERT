# Pronoun resolution on GAP Dataset

This repository contain relevant code (in form of .ipynb) to perform the task of pronoun resolution using end-to-end neural co-reference resolution system. Our implementation makes use of BERT based embeddings to generate vector representation for spans of text. It then uses a FFNN to ranking candidate antecedent spans for the given pronoun.

The current code performs pronoun resolution on the [GAP Dataset](https://github.com/google-research-datasets/gap-coreference).

## Running the code
Start up a IPython server instance to load the file and execute all cells. You can download the trained model from [here](https://iiitaphyd-my.sharepoint.com/:u:/g/personal/srinidhi_pv_research_iiit_ac_in/EdPYPqDMmG5IuYw3wNcbYjkBtd8xLuo1f9QHCDDTe7Xp6A) and load it to test the co-reference system.
