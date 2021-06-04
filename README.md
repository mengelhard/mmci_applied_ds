# Applied Data Science
*Master of Management in Clinical Informatics (MMCi) Program*

**Course Director:** Matthew Engelhard

## Course Materials

- **[Please review the syllabus by clicking here](syllabus.md)**
- Materials for each course weekend (*i.e.,* block) are linked in the *Schedule* below

### Readings and Quizzes
- There will be a quiz due before each block *except* block 6.
- Each quiz (see *Schedule*) links to two articles that should be read before taking it.
- All articles are also available as .pdf in the *Resources* section of [Sakai](https://sakai.duke.edu).
- Your answers must be entered in the *Tests and Quizzes* section of [Sakai](https://sakai.duke.edu) before the beginning of class.
- You may take each quiz as many times as you like prior to the deadline.

### Computational Assignments (CAs)
- There will be computational assignments due before blocks 2-6.
- Each assignment will present code + output and ask you to interpret what you see based on principles from class.
- **You will not need to code** to complete the assignments, which can be viewed in any web browser.
- If you *do* have coding experience, you are encouraged to explore further by modifying the code. We recommend either [installing Anaconda](https://www.anaconda.com/products/individual#Downloads) or working in [Google Colab](colab.research.google.com).
- Recommended Python resources include [Duke Library tutorials](https://library.duke.edu/data/tutorials), the [Python Crash Course book](https://www.amazon.com/Python-Crash-Course-Eric-Matthes-ebook/dp/B07J4521M3/ref=sr_1_1_sspa?dchild=1&keywords=Python+book&qid=1618331896&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEzSVNYTDhDUExZQktDJmVuY3J5cHRlZElkPUEwODgwNjQwM0RNT0U2Nk9XTDdDQiZlbmNyeXB0ZWRBZElkPUEwOTg4NjEyODc5U0ZROVNEQkZEJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==), and [Google Python class](https://developers.google.com/edu/python/).

### Final Project
- The course will culminate in a design project in which you propose to apply data science methods to a clinical topic of your choosing.
- Project instructions and grading details are [here](final_project.md).
- **Proposals are due** before class on weekend/block 3, and the **project is due** before class on weekend/block 6.

## Course Schedule

Block | Topic | Friday / Async | Saturday | Due Before Next Block
--- | --- | --- | --- | ---
0 | Preliminaries | None | None | - Review Course Site<br>- [Read Obermeyer and Emanuel](https://www.nejm.org/doi/full/10.1056/NEJMp1606181)<br>- [Read Chen and Asch](https://www.nejm.org/doi/full/10.1056/NEJMp1702071)<br>- [Q1: 2 Views of Health DS](quizzes/q1.md)
1 | Intro to Health DS | - [AL1: Predictive Models](lectures/al1.pdf)<br>- [AL2: Logistic Regression](lectures/al2.pdf)<br>- [AL3: Multilayer Perceptron](lectures/al3.pdf) | - Course Intro<br>- [LL1: Intro to Health DS](lectures/ll1.pdf)<br>- [Coding Resources](#computational-assignments-cas)<br>- [Q1 Discussion](quizzes/q1.md#discussion-questions)<br>- [LL2: DS Principles](lectures/ll2.pdf) | - [Read Khera et al., 2021](https://jamanetwork.com/journals/jamacardiology/fullarticle/2777055)<br>- [Read Engelhard et al., 2021](https://jamanetwork.com/journals/jamacardiology/article-abstract/2777054)<br>- [Q2: Model Selection](quizzes/q2.md)<br>- [CA1: Visualizing Features](notebooks/assignment1.ipynb)
2 | Learning and Evaluation | - Q&A on AL1-3<br>- [LL3: Performance Measures](lectures/ll3.pdf)<br>- [LL4: Dx Prediction Case Study](lectures/ll4.pdf) | - [LL5: Model Learning](lectures/ll5.pdf)<br>- [Guess & Check Regression](worksheets/mortality_example.xlsx)<br>- [LL6: Training and Overfitting](lectures/ll6.pdf)<br>- [Q2 Discussion](quizzes/q2.md) | - [Final Project Proposal](final_project.md#proposal-1-page)<br>- [Read Hinton, 2018](https://jamanetwork.com/journals/jama/fullarticle/2701666)<br>- [Read Esteva et al., 2017](https://www.nature.com/articles/nature21056)<br>- [Q3: Medical Image Analysis](quizzes/q3.md)<br>- [CA2: Predicting Malignancy](notebooks/assignment2.ipynb)
3 | Medical Image Analysis | - [AL4: Motivating CNNs](lectures/al4.pdf)<br>- [AL5: Spatial Convolution](lectures/al5.pdf)<br>- [AL6: Deep CNNs](lectures/al6.pdf) | - [LL7: Medical Image Analysis](lectures/ll7.pdf)<br>- [LL8: Envirotyping Case Study](lectures/ll8.pdf)<br>- [Q3 Discussion](quizzes/q3.md)<br>- [LL9: Beyond Classification](lectures/ll9.pdf) | - [Read Hirschberg and Manning, 2015](https://science.sciencemag.org/content/349/6245/261)<br>- [Read Taggart et al., 2018](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2706498)<br>- [Q4: Biomedical NLP](quizzes/q4.md)<br>- [CA3: Handwritten Digits](notebooks/assignment3.ipynb)
4 | Biomedical NLP | - [LL10: Bag of Words Models](lectures/ll10.pdf)<br>- [Q4 Discussion](quizzes/q4.md)<br>- [LL11: Biomedical NLP](lectures/ll11.pdf) | - [LL12: Word Embeddings](lectures/ll12.pdf)<br>- Group Exercise TBD<br>- [LL13: VSWEM](lectures/ll13.pdf) | - [Read Che et al., 2018](https://www.nature.com/articles/s41598-018-24271-9)<br>- [Read Choi et al., 2016](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5391725/)<br>- [Q5: Clinical Time Series](quizzes/q5.md)<br>- [CA4 Coming Soon](about:blank)
5 | Sequential Data | - [AL7: Sequential Models](lectures/al7.pdf)<br>- [AL8: Intro to RNNs](lectures/al8.pdf)<br>- [AL9: Neural Attention](lectures/al9.pdf) | - [LL14: Back to Dx Prediction](lectures/ll14.pdf)<br>- [Q5 Discussion](quizzes/q5.md)<br>- [LL15: Seq. Decision-Making](lectures/ll15.pdf)<br>- [LL16: Beyond Sup. Learning](lectures/ll16.pdf) | - [Final Project Report](final_project.md#report-3-pages-single-spaced)<br>- [Final Project Slides](final_project.md#presentation-15-minutes)<br>- [CA5: Beyond Sup. Learning](notebooks/assignment5.ipynb)
6 | Course Projects | - Project Presentations | - Project Presentations | None
