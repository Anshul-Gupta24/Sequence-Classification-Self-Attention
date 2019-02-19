# Isolated-Word-Recognition-Self-Attention

## Implementation of an isolated word recognition system in Keras. The input consists of a sequence of features passed to two layers of LSTM. Self attention is applied on top of the outputs of the second LSTM and the final weighted context is supplied to two dense layers with softmax classification.