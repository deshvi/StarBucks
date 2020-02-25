**Project Title**

This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

Not all users receive the same offer, and that is the challenge to solve with this data set.



**Getting Started**

All files required to run this project are saved in vd-ds/Starbucks  repository.

"Starbucks_Capstone_notebook.ipynb" python notebook  serves as reference document.

This notebook analyses StarBucks data, which was provided. Three separate datasets were provided.

1. Offer dataset - Sample of offers (10 offer to be precise)
2. Customer data - Sample of Customer data (17k customers)
3. Transaction data - Sample of sales data (306k transactions)

I've began with understanding data, read features, understand relationships, cleanup the data, re-engineering of features for making it easier to put it into algorithm.

Few graphs were generated for ease of understanding and to demonstrate to the audience.

Finally, few statistical models were used to fit the data so that the most efficient model can be derived.

**Prerequisites & installation**

Installation of conda is desired for ease of use of libraries. More information for installation of conda and repositories can be found at https://docs.conda.io/en/latest/. Python 3.7.4 is the version of python. IPython 7.9.0 is used explicitly to run the code for simplicity and ease of use.

**Deployment**

Required data and program files are stored in the root repository necessary to run this code. 

**Conclusion**

Model Accuracy Score

 Naive predictor accuracy 0.4732 
 LogisticRegression model accuracy 0.699

######  ***RandomForestClassifier model accuracy 0.762***


  Model f1 Score

 Naive predictor f1-score 0.6425
 LogisticRegression model f1-score 0.697

######  ***RandomForestClassifier model f1-score 0.753***

From the scores above, it was demonstrated that Random Forest Classifier model had produced better results without overfitting of the data.

Few points to note:

1. Data set had limited number of features. More features could've produced even better results such as, geographical location, marital status, time of the day etc.
2. While appreciating the amount of data made available for this assignment, a larger dataset would predict better customer behavior thereby improvement of scope for better offers & tuned offers which results in better customer experience/ satisfaction rating ultimately results in profits.