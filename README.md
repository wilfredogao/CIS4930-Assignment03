# CIS4930-Assignment03

Data Description: This dataset is a subset of the Toronto emotional speech set (TESS) in which a set of 200 target words were spoken in the carrier phrase "Say the word _____' by multiple actresses (aged 26 and 64 years), and recordings were made of the set portraying each of seven emotions. In this assignment the dataset used in this assignment contains 400 audio clips for 4 emotions: sad, angry, happy, and fear. Please Download the dataset here.

What you need to do:
Step 1: Split the dataset into training and testing sets. In the dataset, we have 100 audio clips for each of the abovementioned 4 emotions. For each emotion category, randomly select 70 as training samples and the remaining 30 as testing samples. 
Step 2: Exploratory Data Analysis. This stage is the very initial stage of your data analysis. You may want to know the label distribution of the dataset. You may also want to select sample audio, listen to them and plot them in both the time and frequency domain.
Step 3: Acoustic Feature Extraction. You will extract acoustic features by using librosa or openSMILE. They are both popular Python libraries for automatic acoustic feature extraction.
Step 4: Feature Post-processing. Please refer to the slide of this class.
Step 5: Build your audio emotion recognition model. Provide the extracted set of acoustic features from the training dataset to your classification model. Note that this is a multi-class classification problem. Please select appropriate classifiers since some of the classifiers are not applicable here (e.g., logistic regression).
Step 6: Model evaluation. Evaluate your model performance with the testing dataset. Please compare the performance of different classifiers using the same acoustic feature and the performance of the same classifier using different acoustic features. Finally, discuss your experimental results and submit the assignment report.
