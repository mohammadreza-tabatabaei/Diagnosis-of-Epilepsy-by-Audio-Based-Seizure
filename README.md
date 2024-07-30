# Requirements:
###### 1.Google Colab
###### 2.TensorFlow
###### 3.Keras
###### 4.Numpy
###### 5.Glob
###### 6.Matplotlib
###### 7.Sklearn
###### 8.mne




# Dataset:
I used Epileptic EEG Dataset. This dataset includes the EEG of 6 epileptic patients recorded at the Epilepsy monitoring unit of the American university of Beirut Medical Center between January 2014 and July 2015. The data represents measurements from 21 scalp electrodes, following the 10-20 electrode system, sampled at 500 Hz . All channels have been bandpass filtered between 1/1.6 Hz and 70Hz while filtering out the 50Hz (electrical utility frequency).  Some channels have been omitted from specific recordings due to artifact constraints. 

# Feature Exraction Phase:
The feature extraction stage was performed by CNN and LSTM algorithms.

# Recognition Phase:
This phase focuses on recognizing Epileptic. The recognition phase makes use of SVM algorithm classifire.
