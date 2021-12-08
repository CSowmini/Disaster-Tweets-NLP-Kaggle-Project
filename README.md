# Disaster-Tweets-NLP-Kaggle-Project
Built a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. 
Model is trained with the Kaggle dataset of 10,000 tweets that were hand classified.

Dataset -> kaggle competitions download -c nlp-getting-started

Submissions are evaluated using F1 between the predicted and expected answers.

F1 is calculated as follows:

True Positive [TP] = your prediction is 1, and the ground truth is also 1 - you predicted a positive and that's true!
False Positive [FP] = your prediction is 1, and the ground truth is 0 - you predicted a positive, and that's false.
False Negative [FN] = your prediction is 0, and the ground truth is 1 - you predicted a negative, and that's false.
