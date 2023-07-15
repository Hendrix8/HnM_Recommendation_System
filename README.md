# H&M Recommendation System 

The following repository contains my solution to the kaggle competition : https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations

If you want to run the files, due to the amount of data I would suggest you first pass it to google drive via the kaggle API and then run the ipynb files in colab, this will need a lot of RAM (at times more than 25gb) and for that you will need the runtime with GPU A100 offering 85gb ram which is available in colab pro.

The ipynb files are two, data_prep.ipynb and Model.ipynb where in the first the data is prepared and LSH is applied for clustering, and in the second a classification model is applied on this data.
