# Model Evaluation Questionnaire
*Model Evaluation Pathway*, MMCi Applied Data Science

## Instructions

- Please answer each question as briefly as possible. One to two sentences is ideal but not required.
- For **Assignment 1** (evaluate [Khera et al.](https://jamanetwork.com/journals/jamacardiology/fullarticle/2777055)), please answer questions 1-4, 6, and 11-16 only. There are 11 questions in total. Each correct or thoughtful response (as appropriate) will receive 1 point, and the assignment will be graded on a 10-point scale.
- For **Assignment 2** (evaluate [Tomašev et al.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6722431/), please skip question 7 but answer all other questions. Questions 5 and 10 will be graded leniently, and we'll be exploring these topics in more detail in later course weekends. There are 15 questions in total. Each correct or thoughtful response (as appropriate) will receive 1 point, and the assignment will be graded on a 13-point scale.
- For **all other assignments**, please answer all questions. There are 16 questions in total. Each correct or thoughtful response (as appropriate) will receive 1 point, and the assignment will be graded on a 15-point scale.

## Questions

### Data and source

1. What are the predictors?
2. What is (are) the predicted outcome(s)?
3. Where or how were the data collected, and over what period of time? If multiple datasets were used, please answer this question for each one.
4. Were the data filtered in any way, and if so, how (e.g. inclusion/exclusion, outlier removal)?
5. What preprocessing or data augmentation steps were completed (e.g. feature extraction, standardization)?

### Model Development

6. What model(s) were used to predict the outcome(s) (e.g. logistic regression, CNN)? If multiple approaches were used, specify which one was chosen as the final model.
7. Was any kind of pre-training or transfer learning used, or was the model trained from scratch on the current data?
8. What data (or portion of the data) were used to train the model (i.e. optimize model parameters)?
9. What data (or portion of the data), if any, were used to tune the model (i.e. select hyperparameters)?
10. If the model included hyperparameters that were tuned, please describe these hyperparameters. Note: this should include information about regularization, if it was used.

### Model Evaluation

11. What data (or portion of the data), if any, were used to evaluate the model?
12. Based on performance metrics, please give a brief, practical summary of model performance at a particular operating point (Example: the model can achieve 90% sensitivity at 90% specificity, which would result in an expected 5 false positives and 5 false negatives for each 100 people evaluated at an expected prevalence of 50%).
13. What measures were used to evaluate performance?
14. Are there any other performance measures that were not used, but that you think are important to the proposed application (e.g. in a clinical scenario)?

### Model Deployment

15. What is the primary clinical or healthcare use case for this model envisioned by the authors?
16. Are there any other use cases that the authors could consider with this model, or that you believe would be impactful?
