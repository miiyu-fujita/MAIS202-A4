# MAIS202-A4
MAIS202 Assignment 4 - Kaggle Competition

To reproduce results:

1. Open the following notebook in Google Colab: https://colab.research.google.com/drive/1Ksrv59QVDyS8toLwm0vHYhyr_1-WvZ9m?usp=sharing
> Run the first cell in Colab to mount google drive. This will make it much simpler to access google drive from the VM environment
2. Run all cells under "1. Importing Kaggle Data"
> You will be installing the required datasets as well as python libraries necessary to execute the rest of the code. You will also be preprocessing and cleaning the dataset images in this step. 
> The final cell will allow you to visualize a few images from the dataset
3. It is now time to create the CNN model! Run all cells under "2. Creating Our CNN Model"
> The following cells will create a custom CNN model (Sequential CNN). 
4. Now that you have created the model, you must train it. Run the cells under "3. Training Our Model" to do so. 
> note: The last cell in this section will copy your trained model into your google drive. This allows you to back up your model, in case the VM environment kicks you out due to inactivity or other possible reasons. 
5. Finally, it is time to test the model. Run the cells under "4. Evaluating Our Model" to do so.
> If all goes well, you should see graphs for Loss Function, Accuracy and a Confusion matrix. 
6. To see how the model works on an image from the test set, run the **_first_** cell under "5. Applying the Model to the Test Set". 
> You do NOT need to run the cells for submission to reproduce results. 
