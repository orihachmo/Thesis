# Thesis
Code documentation for the thesis titled "On Intrinsic Dimensionality of Data Sets and Neural Networks" submitted to the Air Force Institute of Technology in the Operations Research department, class of March 24'

The code presented is one of many almost identical Jupyter notebooks used for the research on which my thesis was based (some "bupasses" and other such tweaks were required in certain cases). The specific Wisconsin Breast Cancer data set was, as all other data sets used, downloaded from Kaggle.

A full list of data sets used for the research, all well-known benchmark data sets used in machine learning:
1. Wisconsin Breast Cancer
2. Sonar
3. Pima Indian Diabetes
4. Banknote
5. Ionosphere
6. NBA
7. Cleveland Heart Disease (the binary version of the data set where it is simply indicated whether the patient had heart disease)
8. Iris
9. Wheat Seeds
10. Wine Quality - used for binary classification for scores of up to 5 and 6 or above (division chosen to maximize class balance)
11. Wine Quality - used for three class classification for scores of up to 5, 6 and 7 or above (division chosen to maximize class balance)
12. Boston House Price - used for binary classification for prices below or above median (division chosen to maximize class balance)
13. Boston House Price - used for three class classification for prices in the lower, middle or upper thirds (division chosen to maximize class balance)
14. Abalone - used for binary classification for ages below or above median (division chosen to maximize class balance)
15. Abalone - used for three class classification for ages in the lower, middle or upper thirds (division chosen to maximize class balance)

The code presented in the result of our own original work, discussions with ChatGPT and documentation of the PyTorch library (as well as some limited use of the documentation of other libraries).

Some of the figures in the thesis were created using code that is not presented here. However, this code was never of key importance and any piece of code that was used to generate the main results is available in this GitHub. Another piece of code that is not presented is the training of NN for ID prediction (as described in section 3.5 in the thesis). However, this code is pretty trivial and simply includes the hyperparameter optimization, training and testing of a fully connected neural network.

My main occupation is far from coding and therefore I am completely aware that parts of this code could be rewritten "cleaner" and more efficiently :)
