# Type 1 Diabetes Microbiome Classification

University of Florida — ALS 3200C: AI in Agriculture and Life Sciences — Fall 2025

## What I did

I studied whether gut-microbiome patterns could distinguish Type 1 diabetes cases from controls. Using Python and TensorFlow/Keras, I compared a linear baseline, an LSTM, a Conv1D network, and several Transformer configurations.

I built and ran each experiment with the same training and validation process. I adjusted the Transformer's representation size, attention heads, depth, and dropout; used early stopping; and compared model performance and training time.

I also reran the strongest Transformer setup with a different data split to see whether its performance was consistent.

## What I learned

The LSTM performed best on the main split, while the Conv1D model produced similar results with less training time. Increasing the Transformer's capacity and adding dropout improved it, but it did not outperform the LSTM or Conv1D models. The alternate data split also changed the results, showing why a model should be tested more than once before drawing conclusions.

## Tools and methods

Python, TensorFlow/Keras, NumPy, pandas, scikit-learn, neural-network comparison, train-validation testing, early stopping, and model evaluation.
