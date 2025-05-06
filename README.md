# Evaluating Model Performance for Predicting 30-Day Hospital Readmissions Using Structured Clinical Data and Word Embeddings


Eric Jia, Scott Yamamoto


This repository contains the two notebooks we used to pre-process the MIMIC-3 data and subsequently train/test various machine learning model architectures on the data. The first notebook covers the majority of the pre-processing steps taken to filter the initial dataset. Please note that in order to access the MIMIC-3 data, you must complete both a mandatory CITI training and sign the Data Use Agreement after registering an account on their website here: https://physionet.org/content/mimiciii/view-dua/1.4/

After accessing all of the data, you will only need the 6 tables linked in the paper / notebook. The local paths must also be changed to your computer's directory structure. However, once you have the data, it should be straightforward to run all of the steps in nb1 first, then take that dataframe and use it for notebook 2's final processing steps and model training. Please let us know if you have any questions!
