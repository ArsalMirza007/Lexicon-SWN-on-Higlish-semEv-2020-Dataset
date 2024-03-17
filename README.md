# Lexicon-SWN-on-Higlish-semEv-2020-Dataset

# Instructions:
Sure, here are the bold headings with their descriptions:

1. **Library Imports and Setup**:
   - Importing necessary libraries/modules and downloading NLTK resources.

2. **Tweet Class Definition**:
   - Defining a class `Tweet` with attributes `uid`, `content`, and `sentiment`.

3. **Tweet Cleaning Functions**:
   - Defining functions for cleaning tweets (`cleanTweet`) and loading stop words (`load_stop_words`).

4. **Data Reading and Preprocessing**:
   - Reading training and test data files, cleaning tweets, and calculating sentiments for each tweet in the training set.

5. **Feature Extraction and Label Preparation**:
   - Extracting features (`x_train`) and labels (`y_train`) from the training set.
   - Loading actual labels for the test set and preparing features and labels for the test set.

6. **Model Evaluation and Prediction**:
   - Evaluating a model on the test data and predicting labels on the test data.
   - Decoding predicted and actual labels and showing classification report and confusion matrix.

7. **Visualization: Pie Chart**:
   - Creating a pie chart to visualize the sentiment distribution of the predicted labels.

8. **Visualization: Combined Bar Graph**:
   - Creating a combined bar graph to visualize precision, recall, and F1 measure.

9. **Visualization: Combined Line Graph**:
   - Creating a combined line graph to visualize precision, recall, and F1 measure.

10. **Exporting Processed Data**:
    - Exporting the processed data to a CSV file named 'output.csv'.
   

# Screenshots:
![actual](https://github.com/ArsalMirza007/Lexicon-SWN-on-Higlish-semEv-2020-Dataset/assets/121928372/869b78f9-6ad1-44d3-9a7c-a2e46335d3ff)
![predicted](https://github.com/ArsalMirza007/Lexicon-SWN-on-Higlish-semEv-2020-Dataset/assets/121928372/da2335c6-b0a1-456b-b014-a6c4a59e65fc)
![line](https://github.com/ArsalMirza007/Lexicon-SWN-on-Higlish-semEv-2020-Dataset/assets/121928372/a1e0f556-4b1d-4b15-ac0d-ce88e1b6dcbb)
![confusion2](https://github.com/ArsalMirza007/Lexicon-SWN-on-Higlish-semEv-2020-Dataset/assets/121928372/2f0202b9-bee0-4d1b-9011-ed9a41c9d5f2)
![bar](https://github.com/ArsalMirza007/Lexicon-SWN-on-Higlish-semEv-2020-Dataset/assets/121928372/aaafb96f-9576-4725-aaf4-da26cefeb6b2)
![at one fit cycle of max lr (2e-07)](https://github.com/ArsalMirza007/Lexicon-SWN-on-Higlish-semEv-2020-Dataset/assets/121928372/fda93210-fd6c-467c-91b0-6ba7efcaa482)
![classification report](https://github.com/ArsalMirza007/Lexicon-SWN-on-Higlish-semEv-2020-Dataset/assets/121928372/c0485295-69a4-42ba-b8a5-3dcecc1cf0e9)
