README file to run and execute neural network implementations against the given dataset.

Download the dataset from here.
"http://deeplearning.net/tutorial/gettingstarted.html"


1) Copy and store the given "mnist.pkl.gz" dataset in the every folder of the implementations. 
2) Make sure this dataset and the recognizer.py file end up in the same child direcory.
3) Open the Recognizer.py file and change the values of HL_count, learning_rate, lmda and 
	batchsize as per your requirement in the main function. These variables stand for Hidden 
	layers in the neural network, learning rate of the neural network, regularization parameter  
	and the size of the smaller batches against which the neural network is getting trained. 
	These values may affect the accuracy of the recognizer. Save and close the files.
4) Run the recognizer file and wait till the neural network trains and tests itself. The output
	be displayed on the console screen after each iteration of the test. there will be 30 tests
	or 45 tests conducted based on the type of implementation executed by the user. This can be
	editted as well where the "stochasticGradientDescent" function is being called in the main
	method.