# Applied Data Science, Block 2

*June 7-8, 2019*

---

### Reading Questions

*from Hinton 2018*

1. Which of the following correctly describes how the number of features (i.e. variables) in a predictive model relates to the number of possible multiway interaction terms?
  - The number of possible interaction terms is given by 2*M, where M is the number of features, i.e. it increases linearly with M.
  - The number of possible interaction terms is given by 2^M, where M is the number of features, i.e. it increases exponentially with M.
2. As an alternative to interaction terms, neural networks utilize a limited number of hidden factors that are themselves nonlinear functions of many input variables.
  - True
  - False
3. Which of the following is *not* mentioned by the author as a factor supporting the resurgence of artificial neural networks?
  - the common task framework
  - faster computers
  - big data
  - improved algorithms (i.e. training)
4. Backpropagation is a method for determining how a small change in model parameters will affect the loss function.
  - True
  - False
5. Which of the following better captures the author's views on interpretability:
  - Because neural network parameters are tuned to minimize the loss, there is a single set of parameter values that best reflect the true relationship between the data and labels.
  - Neural networks have multiple valid ways of modeling a given dataset, therefore the final parameter values of the network should not be over-interpreted.

*from Esteva et al. 2017*

6. Which of the following best describes how Inception v3, a convolutional neural network, was trained to detect skin cancer?
  - Inception v3 was trained from scratch (i.e. random parameter values) using labeled images of skin lesions.
  - Inception v3 was originally trained using labeled images of 1,000 object classes from ImageNet, but the entire model was fine-tuned using labeled images of skin lesions.
  - Inception v3 was trained using labeled images of 1,000 object classes from ImageNet. The final layer alone was then trained using labeled images of skin lesions, whereas the weights in other layers remained fixed.
7. The skin lesion labels used to train the model (i.e. training classes) were the same as those used to evaluate its performance (i.e. inference classes).
  - True
  - False
8. Although the model did perform better than the average dermatologist in this study, many of these dermatologists were still trainees.
  - True
  - False

9. The proportion of (a) true negatives over all condition negatives, and (b) false positives over all condition negatives, are known as the:
  - (a) specificity and (b) false positive rate
  - (a) specificity and (b) sensitivity
- (a) negative predictive value and (b) positive predictive value
  - (a) negative predictive value and (b) sensitivity
  
10. The model was evaluated:
  - via cross-validation
  - on a held-out test set of biopsy-proven lesion images
  - both of the above

### Discussion Questions
*To be discussed following lecture 2 on Friday, June 7, 2019*

From the previous block, but not yet discussed:

1. Chen and Asch say that algorithm performance should be compared to "real-world standards of care" rather than "an idealized and unrealizable standard of perfection". Yet in practice, we're often less willing to tolerate errors made by technology than those made by humans. What benchmark should a machine learning model exceed before it's used in clinical decision-making, e.g. performance of the average expert, the best expert, or something else?

New discussion questions:

2. Is the comparison to dermatologists (in *Esteva et al.*) a fair and/or meaningful one? Supposing that convolutional neural networks are indeed better than human experts at classifying skin lesions, how disruptive will this be to the practice of dermatology?
3. What are the barriers to clinical adoption of the technologies presented in this block (e.g. skin lesion classification, colon polyp detection, diabetic retinopathy detection, ultrasound segmentation)? Who will be — or should be — the "early adopters" of deep learning based diagnostics?
