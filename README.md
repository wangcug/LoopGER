# LoopGER
The Readme explains what is contained in the LoopGER repository. The code and data are attached to the Paper titled "Loop Iteration-Based Different-Grained Geological Entity Recognition: A Case Study for Porphyry Copper Deposits!
"

The model folder stores the training model in .h5 file format.
The test_data folder is used to store the test data set
The model training code is stored in the Train folder, which can be opened using jupyter notebook. The file format is .ipynb.

The training data is stored in the train_data folder, and the file format is the same as that in the test_data folder.

The word vector training file is stored in the w2v folder, and the file format is .txt.

The word_dict folder is used to store the vocabulary corresponding to the training model. Each model training will regenerate the vocabulary and overwrite the vocabulary file. Please note that the corresponding vocabulary is also saved when the model is saved; the vocabulary file is in .txt format.
The acc.ipynb file is the code for calculating accuracy (precision, recall, F value), which can be opened using jupyter notebook.

The lemanddel.ipynb file is the code for part-of-speech restoration and removal of stop words, which can be opened using jupyter notebook.

The wordembedding.ipynb file is the code for word vector training, which can be opened using jupyter notebook.
