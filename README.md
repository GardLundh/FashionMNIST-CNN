# School project on the FashionMNIST dataset. 

The batch size of 100 worked well while having three convolutional layers.
I tried different learning rates and number of epochs. And ended up using 5 epochs and a learning rate of 0.0005.
Having more than 5 epochs made the model overfit, and less than 5 epochs was underfitting. 
So i think 5 epochs is the sweet spot for my chosen parameters. 
I tried different parameters for the learning rate, and while a learning rate of 0.0005 didn't differ much from 0.0001 or 0.0002, it seemed to make the model more consistent, and didn't overfit.
I tried making the learning rate higher, and a rate of 0.1, 0.01 and 0.001 made the model overfit and inconsistent. I also tried using Stochastic gradient descent for optimizing, which requiered a higher learning rate. The model with SGD performed more inconsistently than it did with Adam, and didn't yield any better results.
In the end i think my chosen parameters works well.  
