# Dogs-Breeds-classification
project image classification , is based on dogs breeds classification
the model saved as my_model3 , is deployed on streamlit app


The streamlit application is deployed drom the notebook : tp_breeds_percent
tp_breeds_percent : is a final version of a first notebook whom was splitted 60,20,20
the tp_breeds_percent : is then splitted 70,30,10, has show that the low accuracy of the CNN from scratch (model_1) is due to the low number of data for the trainning .


Then, i have uploades images 5/classes to the data source : images 
(which are not enough , due to the computational time on colab, you can see on the tp_breeds_percent i had colab pro , which does'nt worth it)


we can see a lower amelioration of the accuracy(model3, finetuned on MobileNet)

, also after a droupout : 0.5(model_2) and a lower learnin_rate


for further amelioration:
-more data for the trainning
-lowering the learning rate 
-early_stopping
-hyperoptimization 
-fine tuning mobileNet, ResNet 
