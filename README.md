# Neutral-tweet-identification-on-OLID-using-Neutrosophy
The above code was executed in google Colab.
Instructions for using:
1. Copy the files into your Google drive.
2. Add GloVe embeddings and dataset files to the drive. Dataset can be downloaded from [here](https://sites.google.com/site/offensevalsharedtask/olid). You may need to make changes in paths in the code.
3. The embeddings are available at [this link](https://nlp.stanford.edu/projects/glove/)
4. For Transformer models the models are downloaded as part of transformers package.
5. Open the python notebook on Colab where it can be executed (The notebook may not open in Github due to large size).
6. The code has been run on tensorflow 1.x for BiLSTM based models.
7. The code has been run on tensorflow 2.x for Transformer (BERT, ALBERT, MPNet, RoBERTa) based models on a TPU environment.
