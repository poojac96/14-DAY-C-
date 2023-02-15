## Problem statement:
CT Scan Image Classification

Data Overview

This dataset contains 1252 CT scans that are positive for SARS-CoV-2 infection (COVID-19) and 1230 CT scans for patients non-infected by SARS-CoV-2, 2482 CT scans in total. These data have been collected from real patients in hospitals from Sao Paulo, Brazil. The aim of this dataset is to encourage the research and development of artificial intelligent methods which are able to identify if a person is infected by SARS-CoV-2 through the analysis of his/her CT scans.
1-Download this data from here - 

https://drive.google.com/drive/folders/1jHZlFLjaHHBet8T6KvQOTBV0N0cAmDZP?usp=sharing

2 - The images are in different sizes so you have to take a fixed size on which you have to work.

3 - Do data augmentation on it, mention at least 5 args inside it ex-width_shift_range,height_shift_range like this.

4 - Train Model on it you only have to use resnet from resnet you can pick any layer model like - ResNet-18, ResNet-34, ResNet-50, ResNet-101, ResNet-110, ResNet-152, ResNet-164, ResNet-1202.
And mention early stopping and modelcheckpoint while training.

5 - Do Prediction and mention multiple performance metrics

