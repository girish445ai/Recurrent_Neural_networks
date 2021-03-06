# Recurrent_Neural_networks
Contains code for Assignment 3 based on RNNs,LSTMs,GRUs for CS6910 - taught by Dr. Mitesh M. Khapra, IIT MADRAS

In this project we implement a sequence to sequence model for learning problems using Recurrent Neural Networks, compare different cells such as vanilla RNN, LSTM and GRU, implement attention networks to overcome the limitations of vanilla seq2seq model and visualise the interactions between different components in an RNN based model. We use wandb for hyper parameter configuration using the validation dataset and visualisation of test data.

The codes are implemented for both vanilla sequence to sequence and *With attention* .We have used Telugu Language for our model.

The codes can be used on any other indian language from the Dakshina dataset by replacing the te by the language of your choice while setting the train, dev, test set path from the folder dakshina_dataset_v1.0/hi/lexicons/. 

How to run the code:
### Transliteration without Attention:
1. Run all the cells in the notebook in order for training. 
2. The last subsection is sweep , ignore if only training is needed.

The link to the notebook is https://github.com/girish445ai/Recurrent_Neural_networks/blob/main/Transliteration_without_attention_FINAL.ipynb

### Testing Transliteration without Attention:
1. Run all the cells in the order.
2. the wandblinks are commented , no need to change them .
3. After running the code a predictions_vanilla.tsv file is generated which contains the columns of latin language ,actual, predicted forms of telugu language . 

The link to the notebook is https://github.com/girish445ai/Recurrent_Neural_networks/blob/main/TESTING_Transliteration_without_attention_FINAL.ipynb
### Transliteration with Attention:
1. Run all the cells in the notebook in order.

The link to the notebook is https://github.com/girish445ai/Recurrent_Neural_networks/blob/main/Transliteration_with_attention_FINAL.ipynb
### Poem generation:
1. Run all the cells in the notebook 

The link to the notebook is https://github.com/girish445ai/Recurrent_Neural_networks/blob/main/PoemGeneratorTransformers.ipynb



### The wandb report link is this :
https://wandb.ai/girishrongali/assignment3/reports/CS6910-Assignment_3-Report--VmlldzoxOTU4ODU1



References :
For attention:
https://medium.com/datalogue/attention-in-keras-1892773a4f22
For dropout :
https://machinelearningmastery.com/use-dropout-lstm-networks-time-series-forecasting/
For beam_search decoder:
https://machinelearningmastery.com/beam-search-decoder-natural-language-processing/
