![oil-spill](https://github.com/user-attachments/assets/569f5df2-4bd4-43ce-a769-485db59a971c)


# Overview
This project presents an approach for oil spill detection using CNNs to classify images into one of two categories: those containing oil spills and those that do not. By training our CNN on the oil spill dataset, we aim to enhance detection performance by generating a confusion matrix to assess how well the model differentiates between oil spills and non-oil spills.



# Dataset
The Oil Spill Dataset was obtained from Kaggle's repository. It is a meticulously balanced dataset of 4000 RGB images portraying scenes from seas and oceans. Each image varies in size and resolution, capturing a mix of clean environments and instances of oil spills. 

LINK: https://www.kaggle.com/datasets/vighneshanand/oil-spill-dataset-binary-image-classification



#  Modeling
The final CNN model consisted of a single convolutional layer utilizing ReLU activation. This was followed by a max-pooling layer to reduce spatial dimensions. The resulting feature maps were flattened into a 1D vector, followed by a dropout layer. The network concluded with a single-unit dense layer using sigmoid activation for binary classification. The model was trained on the training set, achieving a test accuracy of 99.2%, Precision 99.3% and Recall 99% . The confusion matrix indicated that the model performed exceptionally well for both classes.

