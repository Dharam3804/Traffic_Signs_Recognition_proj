# Traffic_Signs_Recognition_proj
We will build a deep neural network model that can classify traffic signs present in the image into different categories. 
In the world of Artificial Intelligence and advancement in technologies, many researchers and big companies like Tesla, Uber, Google, Mercedes-Benz, Toyota, Ford, Audi, etc are working on autonomous vehicles and self-driving cars. So, for achieving accuracy in this technology, the vehicles should be able to interpret traffic signs and make decisions accordingly.

# What is Traffic Signs Recognition?
There are several different types of traffic signs like speed limits, no entry, traffic signals, turn left or right, children crossing, no passing of heavy vehicles, etc. Traffic signs classification is the process of identifying which class a traffic sign belongs to.

# Prerequisites
This project requires prior knowledge of Keras, Matplotlib, Scikit-learn, Pandas, PIL and image classification.
To install the necessary packages ,enter the below command in your terminal:
           pip install tensorflow keras sklearn matplotlib pandas pil

Our approach to building this traffic sign classification model is discussed in 5 steps:
   Create a Python script file and name it traffic_signs.py in the traffic_sign_recognition_proj folder.
1: Explore the dataset
     The dataset contains more than 40,000 images of different traffic signs. It is further classified into 43 different classes.

2: Build a CNN model

3: Train and validate the model

4: Test the model with test dataset
   In the end, we are going to save the model that we have trained using the Keras model.save() function.
      model.save(‘traffic_classifier.h5’)

5:Traffic Signs Classifier GUI
   we are going to build a graphical user interface for our traffic signs classifier with    Tkinter.Make a new file in the traffic_sign_recognition_proj folder and Save it as        gui.py  .In this file, we have first loaded the trained model ‘traffic_classifier.h5’ using Keras.



In this Python project ,we have successfully classified the traffic signs classifier with 95% accuracy and also visualized how our accuracy and loss changes with time, which is pretty good from a simple CNN model.
