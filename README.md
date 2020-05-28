# News_classfication
Simple sentiment analysis on stock NEWS 
This file demonstrate my ability to apply sequential deep learning techniques on real life problem.
The flow of the code as follows:
  1) Loding data set: 
                    1) News sentiment data set downloaded from kaggle link
                    2) IMDB sentiment analysis dataset downloaded from kaggle link
  2) Text preprocessing:
                    1) Remove all the spl char and number in the sentance
  3) Splitting the dataset set in to train, test, val.
  4) Tokanization transform on all three split with Tokanization_fit on train set.
  5) Downloading Glove pretrained 6B, T=100 from http://nlp.stanford.edu/data/glove.6B.zip
  6) Creating embedding layer and transferring the pretrained weights from glove(to be added in first layer of the model)
  7) Creating a BiLSTM based architecture.(monitoring f1 score and save best model based on val_f1)
  8) GD optimization algo used : ADAM
  9) Tesing on Test set
  10) Testing on NEWS sentance
  
  
