Limited Vocabulary Speech Recognition  
Neha Soni , Nandani Mandawat  and Ekta Choudhary


  Readme file :        
1. Reading the Dataset by using wavfile.read()
   1. Getting the wav file by converting the tensor to array and then decoding the obtained bytes name
   2. Getting labels by double splitting the name of the wav file from right side by ‘/’ and naming the first index value
   3. Output = sample_rates , samples
   4. These samples are arrays.
   5. Reading all wav files and storing them in dataframe
   6. Conversion of each array column to a dataframe of multiple columns by popping the columns and using pd.series function and then concatenating them into the dataframe again
   7. Converting categorical data class into numerical form
   8. Removed the data features with non-uniform lengths
     3.Divided the dataset into features and classes.
     4.spllitting the dataset into train and testing dataset in the ratio of 80:20        
     5.Used the decision tree classifier        
     6.Used the SVM  classifier.        
      7.Reshaped the input arrays.        
      6.Used the CNN classifier.