The sinking of the Titanic is one of the most infamous shipwrecks in history.On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. 
Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.
This project is all about predicting the survivors involved in the RMS Titanic shipwreck.
The initial steps involved in this project was the extracting of data from Kaggle website and applying some exploratory data analysis techniques on the data to see the basic information and trends shown by the data.
The next step was to convert all the categorical features that were present in the dataset so as to work and analyse the data in it's complete and true form.
Also, after the above steps, the importance of every feature was also checked and analysed and it helped us to make the model more accurate.
Next, the stacking up of the model was done and Random Forest Classifier was used in this project as the problem was of classification and not of regression.By, this we were able to achieve a pretty decent training accuracy of 84%
After this, model tuning was done with Randomized SearchCV for a better accuracy and performance.
And by this, we were able to achieve a slight increase in the accuracy i.e 85%.
But, we had a problem in this very stage of the analysis, as we faced an overfitting condition for the test accuracy. And because of this, we applied another model to this project which was XGBoost Classifier.
On applying the extreme gradient boosting algorithm, we had a dip in the accuracy which was approxiately 82% but now the overfitting condition was much improved which made the model more accurate to predict the survivors involved in the RMS Titanic shipwreck.
I scored a rank of 8398 out of almost 18000 teams invovled in the competition.
