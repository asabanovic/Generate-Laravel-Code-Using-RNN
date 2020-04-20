## Generate Laravel Code Using Recurrent Neural Network (RNN)

This is a fun overnight project I wanted to do for a while now. 

The idea was to try to generate new Laravel code and see how RNN model learns with as little as I could give him (a dataset of 1.8MB which is decent for this occasion).

You can also read the whole article with my comments right https://laravel-recipes.com/ai-created-new-laravel-code-will-you-lose-your-job/

# RNN Model

When it comes to the model itself, I used a char-by-char RNN model with an Embedding layer, followed by and LSTM layer.

The model parameters were decided according to the size of the dataset, making sure that it doesn't overtake the size of the dataset by too much and risks overfitting.

![alt text](https://laravel-recipes.com/wp-content/uploads/2020/04/RNN-Laravel-generation.png)

# Model Artifacts

In case you want to clone and run this yourself, you already have the model parameters saved, so you can just download and probably comment out the top part where you load the actual dataset since I wasn't able to provide that as it is confidential. 

Have fun!
