I have done basic standard data preprocessing wherein I have reshaped and scaled data.

I implemented simple ANN wherein I defined a function to plot training loss and accuracy using subplots. I extracted data from the history object of my neural networks
I used PyTorch to construct an ANN with 1 hidden layer with 512 neurons. I did not get good accuracy, thereafter I used batch normalization, dropout regularization and relu activation function. I also used validation split to improve accuracy.

I implemented my CNN model in similar fashion with one hidden layer and max pooling with relu activation and softmax for my classification problem.

I then compare the CNN and ANN model and it was obvious that CNN was easier to understand, efficient and quicker to train and more accurate when I ran lesser number of epochs. 

I then go on to use AlexNet CNN architecture. Since AlexNet is trained on a 224x224 image dataset I had to resize my images, I also used data augmentation to improve accuracy after I found the accuracy to be low initially without the implementation of the said features.  I used random horizonatal flip and random crop functions to get the desired results along with converting the PIL images to tensors and normalising the data. I then proceded to load and wrap the data set from pytorch as opposed to keras earlier which gives numpy arrays instead of PIL images. I froze the initial layers of alex net and added multiple ending layers to increase accuracy which I found to be low as mentioned earlier. I then evaluated the model using the standard procedure of measuring accuracy.

I then go on to study the resnet architecture structure as I aim to freeze the earlier layers and set multiple ending layers in similar fashion. I use cross entropy loss and train only those layers which are trainable. I then use classes of CIFAR10 to print accuracy and classification report and confusion matrix. 

