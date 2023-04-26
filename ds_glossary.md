## List of Data Science Terms
*MMCi Applied Data Science*

---

## Weekend 1

During and after weekend 1, please begin to familiarize yourself with the following terms and definitions.

### Intro to Predictive Models

- **Algorithm:** A process or set of rules to be followed in calculations or other problem-solving operations, especially by a computer
- **Classification Model:** A predictive model for which the predicted value is a categorical label
- **Dependent variable:** Also called a label and often representing a clinical outcome, a dependent variable (often denoted *y*) is a value that a predictive model is trained to predict
- **Feature:** Also called a predictor or indepedent variable, a feature (often denoted *x*) most often refers to an input to a predictive model
- **Independent Variable:** Also called a predictor or feature, an independent variable (often denoted *x*) is an input to a predictive model
- **Label:** Also called a dependent variable and often representing a clinical outcome, the label (often denoted *y*) is the value that a predictive model is trained to predict
- **Learning (in machine learning)**: Adjusting the parameters of a predictive model in order to improve model performance
- **Model:** A mathematical equation defining a possible relationship between variables and typically containing parameters that can be _learned_ from data
- **Parameters:** Numeric values in a predictive model that define a specific relationship between the indepenedent variables (i.e. features) and dependent variables (i.e. label), and are updated during learning
- **Predictive Model:** A mathematical model (see: **Model**) used to predict the value of an unknown (i.e. dependent) variable based on a set of known (i.e. independent) variables
- **Predictor:** Also called a feature or indepedent variable, a predictor (often denoted *x*) most often refers to an input to a predictive model
- **Regression Model:** A predictive model for which the predicted value is numeric
- **Weights:** In the content of machine learning, a *weights* are another term for the parameters in a predictive model

### Logistic Regression

- **Generalized Linear Model:** A generalization of linear regression in which a linear model is related to the dependent variable via *link function* such as the logit function.
- **Logistic Regression:** A generalized linear model commonly used to predict the probability of a binary dependent variable or outcome
- **Logistic (i.e. sigmoid) function:** An S-shaped function used in logistic regression and elsewhere to convert log-odds values to probabilities. It is the inverse of the logit function.
- **Odds:** The ratio of the probability that an event of interest *will* occur to the probability that it *will not* occur
- **Probability:** A number between 0 and 1 quantifying a belief about how likely it is that a given event will occur

### Performance Measures

- **Area under the ROC Curve (AUROC):** A common performance metric for binary classification that can be computed by (a) quantifying the area under the receiver operating characteristic (ROC) curve *or* (equivalently) the sensitivity-specificity curve; or (b) calculating the probability that a randomly selected positive example has a higher predicted probability of being predicted positive than a randomly selected negative example
- **Average Precision (AP):** Also called the average positive predictive value (PPV), the average precision is an estimate of the area under the precision (i.e. PPV) versus recall (i.e. sensitivity) curve
- **Binary classification:** A prediction task in which the label y belongs to one of two classes or categories (e.g. positive/negative, yes/no)
- **Confusion Matrix:** A cross-tabulation of true labels versus model predictions used to summarize the performance of a classification model
- **False Negative:** Also called a Type II error, a false negative is a positive case that is incorrectly believed or predicted (e.g. by a predictive model) to be negative
- **False Positive:** Also called a Type I error, a false positive is a negative case that is incorrectly believed or predicted (e.g. by a predictive model) to be positive
- **Negative predictive value:** The probability that an individual predicted to be negative by a predictive model truly is negative for the condition or outcome of interest
- **Operating Point:** A specific threshold used to convert model-predicted probabilities into binary predictions
- **Positive predictive value:** The probability that an individual predicted to be positive by a predictive model truly is positive for the condition or outcome of interest
- **Precision:** Another term for positive predictive value
- **Sensitivity:** The proportion of positive cases correctly identified (i.e. predicted) as positive by a prediction model or diagnostic test
- **Specificity:** The proportion of negative cases correctly identified (i.e. predicted) as negative by a prediction model or diagnostic test
- **Recall:** Another term for sensitivity
- **Receiver Operating Characteristic Curve (ROC curve):** A graph showing the relationship between the sensitivity and specificity of a binary classification model across the full range of possible classification thresholds- **True Negative:** A negative case that is correctly believed or predicted (e.g. by a predictive model) to be negative
- **True Positive:** A positive case that is correctly believed or predicted (e.g. by a predictive model) to be positive

### Fields and Subfields Related to Data Science

- **Artificial Intelligence:** An interdiscplinary field focused on development of *thinking* machines that process information and make decisions
- **Deep Learning:** The branch of machine learning concerned with development of *deep* neural networks (i.e. containing many hidden layers)
- **Machine Learning:** A subfield of artificial intelligence that incorporates elements of statistics, computer science, and other disciplines to develop systems that learn parameters of a statistical model from data to make predictions or decisions
- **Supervised Learning:** The branch of machine learning that focuses on learning a function that maps inputs to outputs based on example input-output pairs- Training (training similar to learning): Model training in machine language is the process of feeding an ML algorithm with data to help identify and learn good values for all attributes involved.

### Other Relevant Terms

- **Categorical variable:** A variable that can take on one of a limited and usually fixed number of possible values. Common examples in healthcare include sex, race, diagnosis codes, procedure codes, and medications
- **Ordinal variables:** A variable that is similar to a categorical variable, but the categories are ordered. *Example:* rating scales / Likert scales
- **Preprocessing:** Steps taken to clean, organize, filter, or transform raw data to prepare it for another purpose, such as training a predictive model
- **Vector:** For our purposes a vector is simply an ordered list of numbers, such as a list of input features or parameters in a predictive model

<!-- 

## Weekend 2 and Beyond

- **Active learning:** A special case of machine learning in which a learning algorithm can interactively query a user to label new data points with the desired outputs
- **Bag of words model:** An approach to natural language processing in which document features are based on word or phrase counts only without considering the relative positions of words and phrases within the document as a whole
- **Black box:** After a model is trained it can sometimes become difficult to understand the inner workings of the model and the manner in which it arrives at decisions, especially in deep neural networks. The model is then considered a ‘Black Box’
- Clustering: A way of the data points into different clusters consisting of similar data points
- **Computable phenotype:** a set of rules or criteria used to identify a specific clinical diagnosis, event, or finding using electronic health record data
- **Computer vision:** A field combining elements of machine learning, robotics, and signal processing to interpret image data and use these data to make predictions or decisions
- **Convolution (computer vision):** A mathematical operation used to quantify the similarity between a given filter and each region of an image or other feature map
- **Convolutional Neural Network (CNN):** A deep neural network containing multiple convolutional layers (i.e. layers implementing the convolution operation). CNNs are most common in image processing but can be applied to a wide variety of data modalities
- **Cross-entropy loss:** The usual loss function used to train classification models. It quantifies the correspondence between predicted probabilities and true labels. Mathematically, it is the negative log likelihood of a categorical random variable corresponding to the label
- **Data filtering:** Applying inclusion and/or exclusion criteria to remove individuals or data points from an analysis
- Data Model: the process of producing a descriptive diagram of relationships between various types of information that are to be stored in a database. One of the goals of data modeling is to create the most efficient method of storing information while still providing for complete access and reporting. 1
- Data parameter: A set of properties whose values determine the characteristics of something. A limit or boundary of the data.
- Data Partitioning: the technique of distributing data across multiple tables, disks, or sites in order to improve query processing performance or increase database manageability
- Decision surface: A (hyper) surface in a multidimensional state space that partitions the space into different regions. Data lying on one side of a decision surface are defined as belonging to a different class from those lying on the other
- Early stopping: In machine learning, early stopping is a form of regularization used to avoid overfitting when training a learner with an iterative method, such as gradient descent. Such methods update the learner so as to make it better fit the training data with each iteration
- Embedding: Dense numerical representations of real-world objects and relationships, expressed as a vector.
- Explainable Model: refers to the concept of being able to understand the machine learning model.
- Filter or Convolutional Filter: Filters detect spatial patterns such as edges in an image by detecting the changes in intensity values of the image.
- Fully connected layers: Fully Connected layers in a neural networks are those layers where all the inputs from one layer are connected to every activation unit of the next layer.
- Gradient descent: Gradient descent is an optimization algorithm used to find the values of parameters (coefficients) of a function (f) that minimizes a cost function (cost).
- Ground truth: information that is known to be real or true, provided by direct observation and measurement (i.e. empirical evidence)
- Hyperparameter: Hyperparameters are parameters that are established before a model is trained and remain fixed through the training process. The hyperparameters generally affect the parameters that are learned during training and can have a large influence on the final accuracy. One of the difficulties in machine learning is in determining sets of hyperparameters that optimize the model fit.
- Image Segmentation: Image segmentation divides an image into different partitions known as segments.
- Imputation: The process of replacing missing data with substituted values.
- Interpretable Model: Models who explain themselves, for instance from a decision tree you can easily extract decision rules.
- Latent Features ( put with features): Features that we don't directly observe but can be extracted typically by some algorithm
- Life-long learning: accumulating past knowledge that it then uses in future learning and problem solving
- Link Function: A link function in a Generalized Linear Model maps a non-linear relationship to a linear one.
- Loss:
- Likelihood:
- **Model architecture:** The form of the equation that is applied to the input features to generate an output. Equivalently, the structure of the graph that links the input features to the output. *Example*: A multilayer perceptron with a single hidden layer of size 100 units and sigmoid activations
- Model calibration: The act of improving our model such that the distribution and behavior of the probability predicted is similar to the distribution and behavior of probability observed in training data.
- Model Generalization: refers to your model's ability to adapt properly to new, previously unseen data, drawn from the same distribution as the one used to create the model.
- Model interpretability: The degree to which a human can consistently predict the model’s result
- **Motif:** A pattern present in an image that can be detected with a convolutional filter.
- **Multi-class classification:** A prediction task in which the label y belongs to one of three or more classes or categories
- Multi-Layer Perceptron (MLP): A supplement of feed forward neural network. It consists of three types of layers—the input layer, output layer and hidden layer. The input layer receives the input signal to be processed. The required task such as prediction and classification is performed by the output layer. An arbitrary number of hidden layers that are placed in between the input and output layer are the true computational engine of the MLP. Similar to a feed forward network in a MLP the data flows in the forward direction from input to output layer. The neurons in the MLP are trained with the back propagation learning algorithm.
- **Natural Language Processing (NLP):**  A branch of machine learning concerned with training algorithms to understand, analyze, manipulate, and generate human language
- Neural network: A series of algorithms that endeavors to recognize underlying relationships in a set of data through a process that mimics the way the human brain operates.
- **Numeric variable:** A variable whose value describes a measurable quantity, such as 'how many' or 'how much'. Therefore numeric variables are quantitative variables
- **Object Detection:** A computer vision technique that allows objects in an image or video to be located and identified
- Online Learning: A method of machine learning in which data becomes available in a sequential order and is used to update the best predictor for future data at each step, as opposed to batch learning techniques which generate the best predictor by learning on the entire training data set at once
- Outlier: An observation that lies an abnormal distance from other values in a random sample from a population.
- Overfitting: Overfitting is a scenario in which a machine learning model is trained to predict the training data too well, such that it does not generalize to new data sets. In theory, any set of data can be fit with a mathematical model if large numbers of parameters are entered into a mathematical model. This overfitting can occur even if there is no logical relationship between the data and the outcome. For example, a reasonably good fit can be obtained using regression to determine the relationship between age, cholesterol, and sex, to stroke because each of these variables has a physiological relationship with the development of atherosclerosis and subsequent stoke. The mathematical model relating these risk factors and stroke can have a better fit if more parameters than these are entered into the model, even if those parameters have nothing to do with stroke. The resulting model may not perform well clinically if its fit relies on these extra variables. When the model is applied to a different data set than the one on which it was developed, its predictive ability may fail.
- Pre-training: Pre-training is a method which trains shallow neural networks using an unsupervised objective before stacking them to create deep neural networks
- Probability distribution: The “shape” of your data set.  A statistical function that describes the likelihood of the occurrence of possible values that a variable can take and plots them to a visual graph. A common example visually is the bell curve
- **Reference Standard:** For a diagnostic test, a reference standard is the reference against which the proposed method is compared. The reference standard is often a widely accepted test or gold standard for the diagnosis, but it can also be based on diagnoses provided by expert clinicians
- Regularization: A technique used to reduce the errors by fitting the function appropriately on the given training set and avoid overfitting.
- **Reinforcement Learning:** A branch of machine learning in which an agent (e.g. an algorithm) learns to make predictions or decisions that maximize its accumulated reward or utility over time. A reinforcement learning agent is able to perceive and interpret its environment and take actions, and it learns through trial and error
- **Semi-supervised learning:** A type of machine learning in which some labels are known, and others are not known
- Sequential Data: Sequential Data is any kind of data where the order matters to the observation.
- Sparse: Features with sparse data are features that have mostly zero values. This is different from features with missing data. Examples of sparse features include vectors of one-hot-encoded words or counts of categorical data
- Structured and unstructured data: Structured data is highly specific and is stored in a predefined format, where unstructured data is a conglomeration of many varied types of data that are stored in their native formats.
- **Tabular data:** Data stored in a table or spreadsheet format
- **Test Set:** Data not used in model development that is instead used to obtain an unbiased estimate of prediction performance
- Time-Series Data: Time series data is a collection of observations obtained through repeated measurements over time.
- Training Set: 
- Transfer learning: Transfer learning (TL) is a research problem in machine learning (ML) that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem
- Tuning: The process of adjusting the hyperparameters of a trained model to increase the model’s fit to the tuning set. When tuning a machine learning model, hyperparameters are repeatedly adjusted, each time training a new machine learning model on the training set and evaluating that machine learning model on the tuning set. The optimal hyperparameter configuration is typically the configuration that leads to the best tuning set accuracy.
- Unsupervised Learning: A machine learning technique in which the users do not need to supervise the model.
- Validation Set: A set of examples used to tune the parameters of a classifier, for example to choose the number of hidden units in a neural network.
- Variables:  any characteristics, number, or quantity that can be measured or counted
- Vectorization: process of flattening a matrix of numeric values to a vector
- Vocabulary (in nlp context): The set of unique words used in the text corpus is referred to as the vocabulary.

 -->

