# MUSK-_Internship_task
Name : Rounak Tikmani





Libraries used:
-nltk
-sklearn
-pandas
-numpy
THe pos_tagging.ipynb file requires a new article text file in the same folder after running it creates a csv file as required by the problem description.

The news_classification.ipynb code is based on tf_idf vectorization of the text and then 3 model  namely "random forest", "naive-bayes" and "logistic-reg' were applied with 5-fold corss-validation on 80-20 split of train_data. The best working model was logistic regresion and has been used to make predictions of test data.

Accuracy(80:20 train:val with top 5-fold cv 97%) 

I tried deep convolution classification using keras and tensorflow with embeeding from Glove-100d but it didn't give good accuracy I have uploaded the file with name News_ARTICLE_DEEP_Neural.ipynb it requires embeeding from glove100d which is available on stanford website. But I have worled with this model on other dataset and hope it would work if dataset were larger.

