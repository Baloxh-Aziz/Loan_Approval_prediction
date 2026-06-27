# Loan Approval Prediction — ANN

## Overview

This project uses an Artificial Neural Network (ANN) to predict whether a
loan application will be approved or rejected, based on the applicant's
financial and personal information.

## Results

Test Accuracy: 92.62%
Test Loss: 0.2096

## Classification Report:
              precision    recall  f1-score   support

    Rejected       0.95      0.93      0.94       537
    Approved       0.88      0.92      0.90       317

    accuracy                           0.93       854
   macro avg       0.92      0.93      0.92       854
weighted avg       0.93      0.93      0.93       854

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
