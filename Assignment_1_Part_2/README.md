## Semi-Supervised Learning on Ionosphere Dataset

### Problem
  - Classification of Ionosphere data as Good or Bad. 

### Approach Used
  - Train the Auto Encoder model on the dataset. Get the hidden represenations of the data from the intermediate hidden layers. 
  - Generate the raw input for each label - Good and Bad based on the prediction using the hidden representation/weights of the trained model.
  - Using the generated raw inputs to classify as Good or Bad.

### Dataset
  - The dataset consists of radar scans of the ionosphere from a radar array based on Goose Bay.
  - It consists of two classes. “Good” or "g" means that some structure was detected in the ionosphere, “bad” or "b" means that nothing was detected.
