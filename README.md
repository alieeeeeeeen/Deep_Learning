# Deep Learning
This repo contains the dominant algorithms in deep learning. The lib that I use for deep learning is `Keras`.


## Classification
Classification is commonly used in deep learning. We add multiple layers to the model, and prevent the overfitting so that the model can learn how to classify the input into corresponding cateogries.

### DataSets
The dataset that I use is `MINST`, which contains the dog and cat two classes. 

### Procedure
- Clean the data, remove the file that is not img.
- Check if the img is right.
- Augment the img, such as flip it or rotate it.
- Prefetch the train data and test data.
- Make the model, add multiple layers, set the epoch that we need to train.
- Compile the model.
- Fit the data to the model.
- Test an img to see if the model make the right choice.

### Note
Since I put the img in the foler /datasets/PetImgs/, if your directory is different than me, please revise the path.