# Flowers-Classification
Classified images of flowers by creating an image classifier using keras Sequential model. Efficiently load a dataset off disk and identified overfitting and applyied techniques to mitigate it, including data augmentation and dropout
<h1>Implementation</h2>
  
<ul><li>Created a batch of 35 that contains image of size 200 x 200
</li><li>Configured dataset by  buffering and prefetching so there is no I/O blocking
</li><li>Standarized RGB values to 0 and 1
</li><li>Created Convolution neural network with 3 blocks conv2D, max pooling, and dense layer with relu activation function
</li><li>Trained model with 15 epochs 
</li><li>Reduced overfitting to decrease validation loss with training loss
</li><li>Trained model again with 20 epochs
</li><li>Take a new picture of flower and classify

<ul>
