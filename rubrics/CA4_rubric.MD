CA4 Rubric

Q1 (2.5 points)
- .5 for attempting the question
- Up to 1 point for explaining that the occurrence of these words leads to an increase in the log-odds of the label under which they're listed. The first word on each list is associated with the greatest increase in log-odds.
- Up to 1 point for giving an example of a word on one of these lists that was surprising, and why; or a word they expected to see, and why.

Q2 (2.5 points)
- .5 for attempting the question
- Up to 1 point for providing and explaining a first modification that could potentially improve results
- Up to 1 point for providing and explaining a second modification that could potentially improve results
- Possible modifications include, but are not limited to: using a different classification model, such as an MLP; using 2-grams and/or 3-grams in addition to 1-grams (ie., words); using stemming or lemmatization; improving our list of stop words; changing our vocabulary, for example by adjusting the minimum count required for a word too be included; using a different version of tf-idf or otherwise modifying our count-based features

Q3 (2.5 points)
- .5 for attempting the question
- Up to 1 point for describing a limitation of SWEM not shared by the previous (bag of words) model. Possible answers include, but are not limited to:
  - SWEM relies on us having word vectors, and these word vectors must adequately encode the meaning of words in our dataset. For biomedical text, this can be challenging because the meaning of words isn’t the same as it might be in another context (e.g. Twitter, Wikipedia). It’s possible that our word vectors aren’t doing a good job encoding the meaning of relevant words in our dataset.
  - Having a feature for each word in our vocabulary, as in BoW (but not SWEM), prevents us from taking advantage of synonyms, but it can be advantageous in some settings. Suppose there’s a specific keyword that’s always associated with the outcome. In SWEM, we convert this word to its attributes, and then we look for an association between the attributes and the outcome. But in BoW, we can directly associate that specific word with the outcome. There are cases where this is better. This exercise seems to be one of them.
  - In this specific SWEM implementation we are not fine-tuning our word vectors, which is likely the primary reason why the model is not performing well.
  - We are not weighting word vectors by their term frequency or document frequency as we did in the BoW model.
- Up to 1 point for describing a second limitation of SWEM that may or may not be shared by the previous (BoW) model. Possible answers include the following in addition to those listed above:
  - Both approaches fail to consider words in context. In SWEM, this is because we’re using summary statistics rather than an RNN or transformer, for example.
  - We're using a simple linear model, which is limited in all the usual ways: no interactions, linear decision boundary, no feature hierarchy, etc.

Q4 (2.5 points)
- .5 for attempting the question
- Up to 1 point for providing a clinical application that is plausible
- Up to 1 point for a thoughtful description of this application, including why it might be impactful