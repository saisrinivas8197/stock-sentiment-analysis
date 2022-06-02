# stock-sentiment-analysis
 Stock sentiment analysis contains data regarding the top 25 headlines of companies on that particular day and it's influence on stock which is labelled as 0 and 1 where 0 stands for 'negative' influence and 1 stands for 'positive' influence.
- So, the dependant variable of this case study is label variable and the independant variables are top 25 headlines.
- I have initially loaded the data into dataframe using pandas framework and then splitted the data into datasets i.e train and test datasets.Train dataset contains information of companies before 01/01/2015 and test dataset contains data of the same after 12/31/2014.
- Data is cleaned by removing unnecessary extra punctuations and columns names are renamed for the ease of access.
- Then the input features(top 25 headlines) are converted to lower case and all 25 headlines of each row are clubbed and stored in the list by name headlines.
- Headlines are then vectorized using CountVectorizer and a random forest model from scikit-learn is fit on the top of these vectorized inputs along with the dependant variable Label.
- Performance of this model is tested using test data where the data is gone through processing techniques similar to that of the train data 
- Accuracy of the model came out to be 0.8412.
- 
