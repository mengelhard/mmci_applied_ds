## Model Evaluation Questionnaire
*Model Evaluation Pathway*, MMCi Applied Data Science

---

Each question should be answered as briefly as possible. One to two sentences is ideal but not required. A correct or thoughtful response (as appropriate) will receive 1 point, for up to 15 points in total. Note that there are 16 questions.

### Data and source

- What are the predictors?
- What is (are) the predicted outcome(s)?
- Where or how were the data collected, and over what period of time? If multiple datasets were used, please answer this question for each one.
- Were the data filtered in any way, and if so, how (e.g. inclusion/exclusion, outlier removal)?
- What preprocessing or data augmentation steps were completed (e.g. feature extraction, standardization)?

### Model Development

- What model(s) were used to predict the outcome(s) (e.g. logistic regression, CNN)? If multiple approaches were used, specify which one was chosen as the final model.
- Was any kind of pre-training or transfer learning used, or was the model trained from scratch on the current data?
- What data (or portion of the data) were used to train the model (i.e. optimize model parameters)?
- What data (or portion of the data), if any, were used to tune the model (i.e. select hyperparameters)?
- If the model included hyperparameters that were tuned, please describe these hyperparameters. Note: this should include information about regularization, if it was used.

### Model Evaluation

- What data (or portion of the data), if any, were used to evaluate the model?
- Based on performance metrics, please give a brief, practical summary of model performance at a particular operating point (Example: the model can achieve 90% sensitivity at 90% specificity, which would result in an expected 5 false positives and 5 false negatives for each 100 people evaluated at an expected prevalence of 50%).
- What measures were used to evaluate performance?
- Are there any other performance measures that were not used, but that you think are important to the proposed application (e.g. in a clinical scenario)?

### Model Deployment

- What is the primary clinical or healthcare use case for this model envisioned by the authors?
- Are there any other use cases that the authors could consider with this model, or that you believe would be impactful?
