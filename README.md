# NLP-Using-spaCy-for-a-Hotel-Reviews-Data-Set

A Natural Language Processing (NLP) model is developed for a hotel reviews dataset, using spaCy. Each row of this dataset represents one review about the hotel. The number of reviews that are used in this model is 20491. The ratings are between 1 to 5. 

In the file named NLP with spaCy, word frequency analysis is used to check the words that have been repeated in reviews the most. Also, pattern matching is done to see the most repeated adjective and noun combinations. Moreover, the word "bad" is selected and the words that came close to it often are also found. In this file, I put all the riviews together and made a mega string, because I did not want to analyze the reviews seperately. In order to be able to analyze this mega string, I used only 5000 of reviews.

in the file named NLP using spaCy with prediction, I used spaCy and word vector to get predictions. I splited the data into train and test. The independant variable (Review), both for train and test, should become a vector. I used nlp. Then I used some classification algorithms from sklearn to do the classification part and getting the prediction. Accuracy score is used to compare the performance of the algorithms. 

Data source : https://zenodo.org/record/1219899#.YKtUhRozaM8
