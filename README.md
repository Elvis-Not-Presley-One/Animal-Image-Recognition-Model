# Animal-Image-Recognition-Model

![GitHub last commit](https://img.shields.io/github/last-commit/Elvis-Not-Presley-One/Animal-Image-Recognition-Model?style=flat-square&logo=github&color=yellow)
![GitHub License](https://img.shields.io/github/license/Elvis-Not-Presley-One/Animal-Image-Recognition-Model%20?style=flat-square&logo=github)
![GitHub User's stars](https://img.shields.io/github/stars/Elvis-Not-Presley-One?style=flat-square&logo=github&logoSize=auto&color=pink)

This is a image recognition model project that uses Tensorflows CNN(Convolutional Neural Network) architecture. 
 - This was a class projectcode was writen by four people 

# what is a Convolutional Neural Network(s) 
- A Convolutional Neural Network is a type of neural network architecture that is popular use cases are for:
  -  image reconition
  -  object detection
  -  image classification
  -  video recognition
 
 - A Neural Network is composed of 3 Layers : 
    - Input Layer: Takes in raw data, like pictures or numbers. 
    - Hidden Layers: Process and combine the data to find patterns.
    - Output Layer: Gives the final result, like “This is a cat.” 

 - Learning Through Mistakes:
     - At first, guesses are random. The network learns by fixing mistakes, repeating until it gets better.
 - Connection Strength:
     - The links between neurons are like wires. Learning strengthens important connections and weakens less useful ones.


  # How Tensorflow Works 
  -  For this project we decided to use tensorflow as our main lib 
     -  TensorFlow helps create and train models for applications like image recognition, language processing, and predictions.
     - TensorFlow uses "tensors," which are multi-dimensional arrays, to process and analyze data. It offers user-friendly tools for beginners and advanced features for experts and works on different platforms, including computers and mobile devices, making it flexible for various projects.
   
       
   ![](https://miro.medium.com/v2/resize:fit:720/format:webp/1*CnNorCR4Zdq7pVchdsRGyw.png)



# Results
- The Model Produced around a ~98% accuracy
  
![](https://github.com/Elvis-Not-Presley-One/Animal-Image-Recognition-Model/blob/main/ss.png)

# Dataset
- Since github will not allow me to include the dataset we made the link for the Kaggle page will be below
  - About 3gb worth of images:
    - comprising of Googles recaptcha v2 images for most non-animal images and landscapes;
    - The other half comes from 4 diffrent large animla datasets with over 50+ diffrent species
      
  https://www.kaggle.com/datasets/tylerelvis/animal-vs-non-animal-image-recognition-dataset

      
# Rrequirements
- All Libs that need to be downloaded to the latest verstion
  
    ```!pip install tensorflow opencv-python matplotlib```


# Links That Helped Us Along The Way 
Important links:
-	https://www.datacamp.com/tutorial/cnn-tensorflow-python
    -	In-depth info about tensors and how image recognition works 
- https://www.youtube.com/watch?v=jztwpsIzEGc
    -	Great video, guy goes really in-depth with everything 
-	https://www.tensorflow.org/api_docs/python/tf/all_symbols
    -	TensorFlow Documentation 
-	https://github.com/billy-enrizky/TensorFlow-Image-Classification/blob/main/index.ipynb
    -	Really good example project 


