# Applied Data Science
*Master of Management in Clinical Informatics (MMCi) Program*

- **Course Director:** Matthew Engelhard
- **Teaching Assistant:** Bob Brassil

## Course Materials

- **[Please review the syllabus by clicking here](syllabus.md)**
- Materials for each course weekend are linked in the *Schedule* below

### Readings and Quizzes
- There will be a brief quiz due before each weekend *except* weekend 6.
- Each quiz (see *Schedule*) links to one to two articles that should be read before taking it.
- All articles are also available as .pdf in the *Resources* section of [Sakai](https://sakai.duke.edu).
- Your answers must be entered in the *Tests and Quizzes* section of [Sakai](https://sakai.duke.edu) before the beginning of class.
- You may take each quiz *as many times as you like* prior to the deadline.

### Group Assignments
- At the beginning of the course, you will choose one of two pathways for your group assignments.
- Both pathways require four assignments in total, which will be due at the beginning of each course weekend (weekends 2-5). Each assignment relates to the application of a specific machine learning method we will study in class to a clinical or healthcare problem.
- Students choosing the *model development* pathway will learn to work with health-related datasets and train and evaluate predictive models by modifying Python code in a series of Jupyter notebooks.
- Students choosing the *model evaluation* pathway will learn to critically evaluate machine learning models presented in the clinical literature by rigorously analyzing a series of clinical papers.

**Pathway 1:** *Model Development*
- Assignments will guide you through the model development process, from loading and preprocessing data to training and evaluating models.
- Students choosing this pathway should either (a) have prior experience working in Python, or (b) have prior experience working in another scientific computing language (e.g. R, Matlab) and be willing to learn Python syntax sufficient to modify and extend code blocks in the model development assignments. If you are not sure, please take a look at the [posted model development assignments](notebooks) to get a better feel for what will be required.
- To complete the assignments, you may either [install Anaconda](https://www.anaconda.com/products/individual#Downloads) on your computer or work in [Google Colaboratory](colab.research.google.com), which allows you to write and execute Python code in your browser.
- Recommended Python resources include [Duke Library tutorials](https://library.duke.edu/data/tutorials), the [Python Crash Course book](https://www.amazon.com/Python-Crash-Course-Eric-Matthes-ebook/dp/B07J4521M3/ref=sr_1_1_sspa?dchild=1&keywords=Python+book&qid=1618331896&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEzSVNYTDhDUExZQktDJmVuY3J5cHRlZElkPUEwODgwNjQwM0RNT0U2Nk9XTDdDQiZlbmNyeXB0ZWRBZElkPUEwOTg4NjEyODc5U0ZROVNEQkZEJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==), and [Google Python class](https://developers.google.com/edu/python/).

**Pathway 2:** *Model Evaluation*
- Assignments will train you to critically evaluate machine learning models presented in the clinical literature by briefly answering questions related to (a) the data source, (b) model development, (c) model evaluation, and (d) model deployment.
- You will answer the same set of questions for a clinical paper in each of the following four areas:
  - methods for tabular clinical data
  - methods for electronic health record data
  - computer vision for medical imaging
  - natural language processing for clinical text
- Questions are provided in the [model evaluation questionnaire](model_evaluation.md). Please note that not all questions apply to each paper, and a brief list of questions to omit for a given paper will be provided prior to the assignment.

### Final Project
- The course will culminate in a design project in which you propose to apply data science methods to a clinical topic of your choosing.
- Project instructions and grading details are [here](final_project.md).
- **Proposals are due** before class on weekend 3, and the **project is due** before class on weekend 6.

## Course Schedule

Weekend | *Before* Class | *During* Class | *After* Class
--- | --- | --- | ---
1: Evaluating Predictive Models | - Review Course Site<br>- Read [Obermeyer and Emanuel, 2016](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5070532/)<br>- Read [Chen and Asch, 2018](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5953825/)<br>- Complete [Quiz 1](quizzes/q1.md) in Sakai | *Asynchronous*<br>- [AL1: Predictive Models](lectures/al1.pdf)<br>- [AL2: Logistic Regression](lectures/al2.pdf)<br><br>*Saturday*<br>- Lecture: [Intro to Health DS](lectures/ll1.pdf)<br>- Activity: [Understanding Logistic Regression](activities/logistic_regression.pdf) ([key](activities/logistic_regression_key.pdf))<br>- Lecture: [Performance Measures](lectures/ll3.pdf) | *Model Development Pathway*<br>- [CE1: Welcome to the Jupyter Notebook](notebooks/ce1.ipynb)<br>- [CE2: Visualizing Features of Breast Cancer Samples](notebooks/ce2.ipynb)<br><br>*Model Evaluation Pathway*<br>- Evaluate [Khera et al., 2021](https://jamanetwork.com/journals/jamacardiology/fullarticle/2777055)
2: Learning in Neural Networks | - Read [Engelhard et al., 2021](https://jamanetwork.com/journals/jamacardiology/article-abstract/2777054)<br>- Complete [Quiz 2](quizzes/q2.md) in Sakai | *Friday*<br>- Activity: [Calculating Performance Measures](activities/psa_performance.xlsx)<br>- Lecture: [Multilayer Perceptron](lectures/mlp_updated.pdf)<br>- Activity: [Understanding the MLP](activities/multilayer_perceptron.pdf)<br><br>*Saturday*<br>- Lecture: [Model Learning](lectures/ll5.pdf)<br>- Activity: [Guess & Check Regression](activities/mortality_example.xlsx)<br>- Lecture: The Model Development and Evaluation Process | *Model Development Pathway*<br>- [CE3: Predicting malignancy from features of breast cancer samples](notebooks/ce3.ipynb)<br>- [CE4: Exploring Overfitting](notebooks/ce4.ipynb)<br><br>*Model Evaluation Pathway*<br>- Evaluate [Tomašev et al., 2019](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6722431/)
3: Medical Image Analysis | - Read [Hinton, 2018](https://jamanetwork.com/journals/jama/fullarticle/2701666)<br>- Read [Wilson, 2019](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7735021/)<br>- Complete [Quiz 3](quizzes/q3.md) in Sakai | *Asynchronous*<br>- [AL4: Motivating CNNs](lectures/al4.pdf)<br>- [AL5: Spatial Convolution](lectures/al5.pdf)<br>- [AL6: Deep CNNs](lectures/al6.pdf)<br><br>*Saturday*<br>- [LL7: Medical Image Analysis](lectures/ll7.pdf)<br>- Model Evaluation, Generalization, and Overfitting<br>- Activity TBD | *Model Development Pathway*<br>- [CE5: Identifying Handwritten Digits](notebooks/ce5.ipynb)<br>- [CE6: Better MNIST Predictions](notebooks/ce6.ipynb)<br>- [CE7 (Optional): Transfer Learning](notebooks/ce7.ipynb)<br><br>*Model Evaluation Pathway*<br>- Evaluate [Esteva et al., 2017](https://www.nature.com/articles/nature21056)
4: Biomedical Text Processing | - Complete [Final Project Proposal](final_project.md#proposal-1-page)<br>- Read [Hirschberg and Manning, 2015](https://science.sciencemag.org/content/349/6245/261)<br>- Complete [Quiz 4](quizzes/q4.md) in Sakai | *Friday*<br>- [LL10: Bag of Words Models](lectures/ll10.pdf)<br>- Building Text Features<br>- [LL11: Biomedical NLP](lectures/ll11.pdf)<br>- [AL7: Word Embeddings & VSWEM](lectures/al7.pdf)<br>- [AL8: Learning Word Embeddings](lectures/al8.pdf)<br><br>*Saturday*<br>- Eric Poon Guest Lecture<br>- Exploring Word Embeddings | *Model Development Pathway*<br>- [CE8: Text Pre-Processing](notebooks/ce8.ipynb)<br>- [CE9: Bag of Words Models](notebooks/ce9.ipynb)<br>- [CE10 (Optional): A Simple Word Embedding Based Model](notebooks/ce10.ipynb)<br><br>*Model Evaluation Pathway*<br>- Evaluate [Taggart et al., 2018](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2706498)
5: Working with Multi-Modal Health Data | - Watch [Beede et al.](https://youtu.be/-7VR8fZFOT4)<br>- Complete Quiz 5 in Sakai | *Asynchronous*<br>- Multi-Modal Health Data<br>- [LL4: Dx Prediction Case Study](lectures/ll4.pdf)<br><br>*Saturday*<br>- Explaining Model Predictions<br>- Activity TBD | Complete Final Project
6: Course Projects | [Final Project Report](final_project.md#report-3-pages-single-spaced) | Beyond Supervised Learning | Graduate!
