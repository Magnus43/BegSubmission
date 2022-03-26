# BegSubmission
Beginners hypothesis submission for DSG
Approach for submission
Started with applying SVR model to predict model similar to the one shown in lecture 2 of the lecture series
However, the accuracy of SVR approach ws getting limited at around 2.1.... even after a lot of changes (Selecting the 10 variables with maximum correlation to snow depth, cleaning up data by removing rows with negative value of snow fall, changing the ratio of data taken for training and testing)
Therefore, changed my approach to now use Keras API to build a nueral network to predict snowfall
Most information about syntax of creating and training the model was taken from this page - https://www.freecodecamp.org/news/how-to-build-your-first-neural-network-to-predict-house-prices-with-keras-f8db83049159/
using that, I was able to bring down the error down to 1.7..... The Keras file is the final submission
