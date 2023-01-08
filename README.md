# Hate_Speech_Recognition

Spam classification is important to detect unwanted and unsolicited messages, which are often capable of defrauding the readers and causing losses.     
The dataset that we're using contains 5569 entries, of which 745 are spam.

##  Libraries used  
Pandas    
Numpy   
Sklearn   
Nltk    
Re

##    Process   
First, we manipulate the dataset to remove all Non-Alphabet characters from the data.  
If we will fit this data to train our hate speech detection model, then the model will not generalize any hate speech because the data with context to the hate speech is very less than the positive ones. So in this situation, we need to prepare the data to fit properly in our model.   
For simplicity, we have used the Scikit-Learn's Pipeline for our model.       
<img width="301" alt="Screenshot 2023-01-08 at 11 47 54 AM" src="https://user-images.githubusercontent.com/72307339/211183240-738ab2ed-98bb-4d1a-9179-deaa2f1deb22.png">      
We get an Accuracy score of 96.9%, which is appreciable.    
Thank you!
