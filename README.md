# COVID19-predictor-using-chestxray
Project that is used to predict whether a patient is corona positive or not.
It uses CNN(Convolutional Neural Network) for the processing of the chest x ray image. Reason for choosing this method is because it si more cheap, economical and accurate as compared to other methods.
## Links for chest x-ray Database
- for corona positive dataset [https://github.com/ieee8023/covid-chestxray-dataset.git] <br />
- for corona negative dataset [https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia]
## How to use the database
First thing first download the database and store it in the folder where the `database preparation pynotebook` is stored. Then in the dataset creation file add the `image path` in the `image variable` and `csv` file in the file variable.<br />
Similarly store the file in the respective variable and use that to acess the database.<br />
After making a saperate list of covid positive and negative patients you can further segregate both dataset to train and validation set and use it in the COVID19 DETECTOR file. But here in this file I've used an already prepared train and validation set. 
### **IMPORTANT NOTE**
I've just made and trained a neural network. You can use this and save it in different format to deploy it in different and do the modification of your own to make it even better.
