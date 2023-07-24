Next word Predicition using the twitter Dataset from Kaggle


(i) The user can give a multiple words and model can predict the final word of the sentense using the NLP and we can call this as Sequence to Vector

(ii) In the first stage we have to do the text preprocessing like to lower the string and removal of special characters using the regex pattern.

(iii) Then i used the Tokenization method to give the token index to the each word.

(iv) Then i created the sequence of indexes uisng for loop to get all the sequence in the dataset.

(v)  we have to exclude the last word of the sequence for all the columns, however the last word is the output for our model to predict

(vi) Then i did pre-padding for all the rows in the dataset.

(vii) And we have to consider all as training except the last word of the each sentence as i mentioned earlier last word is our output like our model is going to predict.

(viii) Then i build the architecture using the Embedding layer and LSTM.

(ix) Embedding is used to find the relationship between the words and in LSTM we have seperate gate for the each activation function function and the gates are 
                              (i) input gate
                              (ii) forget gate
                              (iii) output gate.

  (x) Then i did the compilation for our model and after completing that i saved the model and did real time prediction.
  (xi) I got 60% accuracy and i am still working on it to increase the accuracy.



Note: 

we can also do the Transfer learning to download the data from the google and we call as "Glove.6B.300d" 

I dont have efficiency machine to train the transfer learning model so i am mentioning here the steps to do Transfer learning and it takes hours or day to train the models.





