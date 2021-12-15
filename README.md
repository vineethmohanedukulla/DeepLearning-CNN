# ICP-10

#### Complete the following:
```
Name: Edukulla Vineeth Mohan
Email: vekfd@umsystem.edu
```
---
```
Partner Name:  Maheswarrao Badrapu
Partner Email: mbfb6@umsystem.edu
Partner ICP-Link:  https://github.com/UMKC-APL-PythonDeepLearing/icp-10-Maheswarrao1
```

##  In this lesson we will review regression techniques

      video link: https://github.com/UMKC-APL-PythonDeepLearing/icp-10-vekfd/raw/main/video/icp10-1.mp4
      
### **Question 1**
1. Follow the instruction below and then report how the performance changed.(apply all at once)

     • Convolutional input layer, 32 feature maps with a size of 3×3 and a rectifier activation function.

   • Dropout layer at 20%.

   • Convolutional layer, 32 feature maps with a size of 3×3 and a rectifier activation function.

   • Max Pool layer with size 2×2.

   • Convolutional layer, 64 feature maps with a size of 3×3 and a rectifier activation function.

   • Dropout layer at 20%.

   • Convolutional layer, 64 feature maps with a size of 3×3 and a rectifier activation function.

    • Max Pool layer with size 2×2.

    • Convolutional layer, 128 feature maps with a size of 3×3 and a rectifier activation function.

    • Dropout layer at 20%.

    • Convolutional layer,128 feature maps with a size of 3×3 and a rectifier activation function.

    • Max Pool layer with size 2×2.

    • Flatten layer.

    • Dropout layer at 20%.

    • Fully connected layer with 1024 units and a rectifier activation function.

    • Dropout layer at 20%.

    • Fully connected layer with 512 units and a rectifier activation function.

    • Dropout layer at 20%.

    • Fully connected output layer with 10 units and a softmax activation function


### **Question 2**    
    
    2. Change the previous model into Keras Functional API model.
        2.1 Apply the following callbacks to the model:
          - ModelCheckPoint.
          - EarlyStopping
### **Question 3**
   
  3. Predict the first 4 images of the test data. Then, print the actual label for those 4 images (label means the probability associated with them) to check if the model predicted correctly or not.
### **Question 4**
4. Build your own dataset by collecting images from the internet for example:
- Transportation images (Airplanes, Trains, Cars, ..)
- Animals (Cats, Dogs, ..)
 
    4.1 Train the model on your dataset and report the accuracy and type of pre-processing that needed to be done.

     4.2 Plot the training and validation accuracy.

     4.3 Save the model as a file and load the model again and predict on some images
    

    

## Softwares Required :
1. About CNN
2. Hyperparameters of CNN
3. Image classification with CNN

## Implementation:
1. Assignment was provided with steps for image_classification dataset.
2. We need to run the preprocessing  to preprocess the data before sending it to the model for input
3. split the data into to train and test data for training and testing the model.
4. predicted the images


## Tasks Performed

### **Question 1: Code Development**


Below are the outputs:
![Screenshot (26)](https://user-images.githubusercontent.com/78897209/141601040-f153fd0f-abe9-4b7b-91bd-d88a48bb736f.png)


### **Question 3: Code Development**


Below are the outputs:
Below are the outputs:
![Screenshot (27)](https://user-images.githubusercontent.com/78897209/141601041-e7ead71f-6902-4022-b4fa-b7f9f49b85ec.png)
![Screenshot (28)](https://user-images.githubusercontent.com/78897209/141601029-bd984543-362d-4d6f-80d9-5a65ed1897b9.png)
![Screenshot (29)](https://user-images.githubusercontent.com/78897209/141601030-4555dd87-5f70-48d8-a310-7f616fc05f99.png)
![Screenshot (30)](https://user-images.githubusercontent.com/78897209/141601031-3573052c-9067-4621-b579-f3b6108da2fd.png)
![Screenshot (31)](https://user-images.githubusercontent.com/78897209/141601032-aa3b0859-7c8f-494f-be9c-b3f2d00d2446.png)

![Screenshot (32)](https://user-images.githubusercontent.com/78897209/141601033-e2581575-0bb0-47a0-a8d8-e8d93b67845c.png)

### **Question 4: Code Development**


Below are the outputs:

![Screenshot (33)](https://user-images.githubusercontent.com/78897209/141601034-78ecfc4e-9ae9-4886-993b-334d47a1af6e.png)
![Screenshot (34)](https://user-images.githubusercontent.com/78897209/141601035-67484fe1-1a3f-43b2-8c6e-fdad3d3c7658.png)
![Screenshot (35)](https://user-images.githubusercontent.com/78897209/141601037-182118fe-5354-40af-b520-2d22938a4bfc.png)
![Screenshot (36)](https://user-images.githubusercontent.com/78897209/141601038-75dbfd12-bfd2-46de-a36d-61765c495295.png)
![Screenshot (37)](https://user-images.githubusercontent.com/78897209/141601039-fc1cab3f-b893-495d-b0c7-96808511f1fe.png)

**Note:** 
Before executing the python notebook, keep the code and the python dataset in same folder.

Explanation Video:
https://github.com/UMKC-APL-PythonDeepLearing/icp-10-vekfd/raw/main/video/icp10-1.mp4
