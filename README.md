## MLCAS24 Competition

This repository contains data and code from the team Brigtado for the MLCAS24 Corn Yield Prediction Challenge

## Reproducing results

*  Clone this repository and run the jupyter notebook **Agri_Challenge_Prepare_Data_Train_Test.ipynb** in order to preprocess data, train and test all at once. Jupyter Notebook contains various sections that allow you to run different steps.
*  Some of the dependencies that need to be installed are pandas, matplotlib, scikit-learn, rasterio, numpy, PIL, opencv, torch. If you encounter that any of the required dependencies are not installed on your system, you can install them by running 'pip install dependency_name' on your command line
*  Download data from the link provided in the notebook
*  You can also download processed data from these links:
*  Train and val - https://drive.google.com/file/d/1q-O1Kq2t6kweqBN2fQm5GhcTQ9P1-s0P/view?usp=sharing
*  Test - https://drive.google.com/file/d/1CNJbrTITo7cQah_wOCR9veQ9BGv51_B8/view?usp=sharing
*  To reproduce similar results to our submission, it is suggested to train on the train_val dataset provided above because data preparation in the notebook can change the samples in train and validations sets on every run which in turn can change the accuracy
