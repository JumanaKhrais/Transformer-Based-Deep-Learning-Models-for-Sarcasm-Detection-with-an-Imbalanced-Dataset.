# Transformer-Based-Deep-Learning-Models-for-Sarcasm-Detection-with-an-Imbalanced-Dataset.
TrainEnglish.csv dataset is from the Semval2022 subtask A of task 6, which is classifying whether a tweet is sarcastic or nonsarcastic.

TestEnglish.csv dataset is from the Semval2022 subtask A of task 6.

The train.csv dataset represents the .85 of the TrainEnglish.csv and the valid.csv represents the .15 of the TrainEnglish.csv (Imbalanced).

trainBal.csv and validBal.csv represent the balanced (downsampled) train and validation versions of the TrainEnglish.csv.

trainAug.csv and validAug.csv represent the augmented train and validation versions of the TrainEnglish.csv.

Downsampling_Code.ipynb represents the code used to downsample the TrainEnglish.csv dataset.

Augmentation_Code.ipynb represents the code used to augment the TrainEnglish.csv dataset.

Ensem.ipynb represents the ensemble method code. // The following links are the links of the BERT and RoBERTa models used in the ensemble // BERT: https://drive.google.com/drive/folders/12lBKYPdShV_2W0EdoK_cXT7DtNHu9RDi?usp=sharing // RoBERTa: https://drive.google.com/drive/folders/103jYpt5xgmrd8Mq02q4tBt38iRx0Vc4c?usp=sharing.

sequentialModels.ipynb represnet the code used to train the RNN-based models. // when using it pay attention to the dataset file location path.

Bert_Code.ipynb represents the code of the BERT model with  a sample of running with the following parameters: (Batch size = 10, Number of epochs = 3, The last 4 layers are trainable)

RoBERTa_Code.ipynb represents the code of the BERT model with  a sample of running with the following parameters: (Batch size = 7 , Number of epochs = 3, The last 3 layers are trainable)














