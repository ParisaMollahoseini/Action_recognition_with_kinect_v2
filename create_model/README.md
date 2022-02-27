
# Create model

### ✅ Explanation
----

In this section we trained a ResNet-50 model on processed data.
Applying ResNet model is one the transfer learning methods which the model's weights are pretrained and there is no need to train the whole model again. 


📌 We used Google Colab framework to use GPU feature and reduce execution time.

The whole process of model preperation and train is explained below:

- Upload dataset
- Install PyTorch library
- Load ResNet-50 model
- Convert data to PyTorch dataset 
- Add some layers to the end of ResNet-50 layers and set the output to 5
- Set model parameters and train model
- Test model on test data

### ✅  How to run
----

Follow these steps to run the code:
➙ First you should upload the dataset on google colab files (preferbly on google drive)
➙ Change the directories to your directories on google colab files.
➙ Run the cells up to train cell.
➙ Change the hardware accelerator to GPU from Notebook settings in edit menu.
➙ Run the rest of cells and see the results. 😊


This model is inspired from the paper named "Learning and recognizing human action from skeleton movement with deep residual neural networks".

### 📝 Paper which is used in this project
Pham, H.-H., Khoudour, L., Crouzil, A., Zegers, P., & Velastin, S. A. (2017). Learning and
recognizing human action from skeleton movement with deep residual neural networks. 8th International
Conference of Pattern Recognition Systems (ICPRS 2017).
