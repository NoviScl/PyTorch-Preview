# Quiz for Preview Week 3 

## Part 1: PyTorch For Neural Nets 

Following the notebook of Day 3 on MNIST dataset and Day 4 on SST-2, do some further modifications to improve the model performance.
For example, data augmentations, better model architecture designs (e.g., residual connections), model ensemble, hyper-parameter searching. You are encouraged to do some search online to learn and apply more techniques. (Note: these are just suggestions.)

Please use comments to explain your codes clearly in a notebook and leave the test results section on the notebook so that we can easily verify the performance of your model.

## Part 2: Language Modeling on Penn Treebank (Optional)

I have already downloaded the Penn Treebank (PTB) dataset for your use. The task is to train a model to learn to predict the next word of a given sequence. My suggestion is to start with a simple unidirectional RNN. You may refer to this codebase: https://github.com/yunjey/pytorch-tutorial/blob/master/tutorials/02-intermediate/language_model/main.py for reference. But you should move your codes on a notebook and run there. Leave the experiment results on the notebook so that I can check. For your reference, you should get training perplexity around or below 100 after about 5 epochs. The training should be reasonably fast even on a CPU (about 17 minutes per epoch).

