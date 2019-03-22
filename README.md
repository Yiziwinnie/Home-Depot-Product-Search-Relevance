# Home-Depot-Product-Search-Relevance
@ Joshua Smith @ Wenyi (Alex) Yan on March 19, 2019

>Tool: Python<br/>
Public Score:  0.47453 [First Place in Competition]* <br/>
Private Score: 0.47336 [First Place in Competition]* <br/>


### Introduction 
Home Depot is an American home improvement supplies retailing company that sells tools, construction products, and services1. To improve the online shopping experience of their customers, we intend to develop models that can better predict the relevance score of search results so that customers can get exactly what they want through the search engine.
During this process, we applied information retrieval knowledge, calculating different similarities, machine learning knowledge, domain knowledge, feature engineering, and the creation of ensemble models. Ultimately, the best model was obtained using a Gradient Boosting Regressor which achieved a RMSE of 0.47453 (Public - 30% of test set) and RMSE of 0.47336 (Private - 70% of test set), ranking first on Kaggle (March 17, 2019 submission).<br/>

### Data Overview
Four datasets are used in this project:<br/>
1.train_new.csv<br/>
2.test_new.csv<br/>
3.product_descriptions_new.csv<br/>
4.attributes_new.csv<br/>
Those four datasets include features which are listed as below.<br/>
id - a unique Id field which represents a (search_term, product_uid) pair<br/>
product_uid - an id for the products<br/>
product_title - the product title<br/>
product_description - the text description of the product (may contain HTML content) search_term - the search query<br/>
relevance - the average of the relevance ratings for a given id<br/>
name - an attribute name<br/>
value - the attribute's value<br/>

### Data Processing
In this part, our project covers Spelling Correction,String Cleaning through Regular Expression,Remove stop words,Tokenization, Stemming,Lemmatization,

### Data Engineering 

### Model
Random Forests model
Gradient Boosting model and Xgboost model

### Presentaion 
<https://www.youtube.com/watch?v=vKeUY2v5xx0&feature=youtu.be>
