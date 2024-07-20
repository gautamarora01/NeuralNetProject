So this is a Neural Net simulator in C++ and it is demonstrating fundamental concepts of feedforward neural networks and backpropagation.
We can teach the neural net to solve a simple task using some training data. 

The only issue that could happen is that trainingData.txt when run is encoded in UTF 16 LE
To resolve this click on file->save as-> convert it to UTF 8

Possible tweaks for fun -> eta, alpha, try changing training data and implement different stuff

How to run code on terminal -> 

g++ makeTrainingSamples.cpp -o makeTrainingSamples
./makeTrainingSamples > trainingData.txt
g++ NeuralNet.cpp -o NeuralNet
.\NeuralNet > out.txt
notepad out.txt
