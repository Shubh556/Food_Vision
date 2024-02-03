## Classifying Food From the Food 101 Dataset

The code uses TensorFlow and TensorFlow Datasets to build a deep learning model for the Food101 dataset classification task. It starts by loading the dataset, visualising sample images, and preprocessing them to ensure efficient training. The model architecture is based on the EfficientNetB7 pre-trained model, with the final layers tailored to 101 classes. The code employs mixed precision training to improve computation and memory efficiency. It uses callbacks such as ReduceLROnPlateau and EarlyStopping for dynamic learning rate adjustment and model checkpointing, respectively. The training process shows steady improvement in both loss and accuracy, but it stops when validation accuracy reaches a plateau. Finally, it assesses the model's performance on the test set, which yields approximately 70% accuracy. The code also visualises training and validation metrics with Matplotlib. Overall, it provides a comprehensive deep learning pipeline for image classification tasks, applying cutting-edge techniques and best practices for model training and evaluation.

## Dataset Download 
The code  determines whether the "food101" dataset is available in TensorFlow Datasets (TFDS). If it finds the dataset, it loads it and divides it into training and validation sets. The dataset contains images of various foods for training a machine learning model. If there are any errors during the loading process, it prints an error message. This code segment provides access to the Food101 dataset, which is required for training models to recognise and classify various types of food. It is a fundamental step in developing machine learning systems for food recognition tasks.

![Data Set Download](https://github.com/Shubh556/Food_Vision/blob/main/Images/Data-set_Download.png?raw=true)

## 20 image labels

![Checking 20 image labels](https://github.com/Shubh556/Food_Vision/blob/main/Images/Class-names.png?raw=true)

## Ploting Random Images  

![Checking 20 image labels](https://github.com/Shubh556/Food_Vision/blob/main/Images/visvalizing-image.png?raw=true)

## Model 

![Checking 20 image labels](https://github.com/Shubh556/Food_Vision/blob/main/Images/model.png?raw=true)

## Accuracy and Loss Curves 

![Checking 20 image labels](https://github.com/Shubh556/Food_Vision/blob/main/Images/curves.png?raw=true)

## Evaluating Model on Test Data 

![Checking 20 image labels](https://github.com/Shubh556/Food_Vision/blob/main/Images/test-data.png?raw=true)





















