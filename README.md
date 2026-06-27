## Observations

The model achieved a test accuracy of 92.62%, which is a strong result for 
predicting loan approval decisions.

The model performs slightly better at identifying "Rejected" loans (95% 
precision, 93% recall) compared to "Approved" loans (88% precision, 92% 
recall), but both classes are predicted well overall.

Training accuracy improved steadily across epochs without large gaps between 
training and validation loss, showing the model learned properly without 
overfitting.

The cibil_score feature likely played a major role in the predictions, since 
credit score is a key factor banks use when approving loans.
