# Applied Data Science, Block 4

---

### Reading Questions

*from Che et al., 2018*

1. Imputation is the process of filling in missing values in a dataset.
  - True
  - False
2. Which of the following correctly describes missing values in MIMIC-III?
  - values are missing at random, satisfying a key assumption of many imputation strategies
  - values are rarely missing, and patterns of missingness, although not random, are not informative or correlated with outcomes such as mortality
  - values are frequently missing, and patterns of missingness are correlated with mortality and other outcomes
3. Which of the following imputation strategies is *not* used by the authors (and not advisable)?
  - fill in missing values with zeros
  - fill in missing values with the last observed measurement of that type
  - fill in missing values with a predictive model trained on observed values
4. When used in combination with a non-RNN model, more sophisticated imputation strategies (e.g. MICE and MissForest) performed better than simple strategies (e.g. Mean, Forward, Simple).
  - True
  - False
5. The authors' proposed model, the GRU-D, makes all of the following assumptions about missing values *except*:
  - when the last observed value is recent, the imputed value should be similar to it
  - when the last observed value is not recent, the imputed value should be similar to a default value
  - the default value is the empirical mean of all measurements of that type
  - the rate of transition from the last observed value to the default value should be the same for all measurement types

*from Choi et al., 2016*

6. Which of the following correctly describes how the authors converted events from the EHR into feature vectors?
  - events were encoded as one-hot vectors, where each element of the vector represents a distinct event type
  - events were encoded as one-hot vectors, where each element of the vector represents a group of related events
  - events were encoded as low-dimensional medical concept vectors that were learned using a neural network model (i.e. similar to word vectors)
  - all of the above were explored
7. Which of the following best describes the authors' imputation strategy?
  - Missing values were imputed by carrying the last observed measurement forward
  - The dataset has very few missing values, so the authors were able to discard them without losing much data
  - The data were sequences of events rather than a time series of measurements, so there were no missing values
8. The benefit of the RNN was greater for the longer, 18-month observation window.
  - True
  - False
9. The output of each block of a gated recurrent unit (GRU) depends only on the current input and the previous N inputs, where N is typically very small (i.e. <5).
  - True
  - False
10. Using medical concept vectors (rather than one-hot encoding) improved performance, but also substantially increased the training time of the recurrent neural network model.
  - True
  - False

