CA3 Rubric

Q1 (2.5 points)
- .5 for attempting the question
- Up to 1 point for explaining that the filter weights are positive (i.e. bright) in locations where the digit they detect tends to be positive/bright, because positive/bright values in those locations are associated with an increase in the log-odds of that digit. When filter and image are matched, the log-odds will be high; when they are not matched, log-odds will be low.
- Up to 1 point for explaining that each filter must identify all different styles and variations of the digit they detect, hence their blurry appearance, which is a weighted average of all these styles.

Q2 (2.5 points)
- .5 for attempting the question
- Up to 1 point for describing a first advantage of the MLP
- Up to 1 point for describing a second advantage of the MLP
- Possible answers include: non-linear decision boundary, non-linear function, more flexible function, feature hierarchy, interactions between features, can capture multiple handwriting styles (or patient profiles in clinical prediction problems), can model the data in multiple ways simultaneously (i.e. can be viewed as an ensemble of models)

Q3 (2.5 points)
- .5 for attempting the question
- Up to 1 point for stating that the CNN would NOT be able to identify rotated digits
- Up to 1 point for explaining that this is because its filters are trained to identify features that look like themselves. These filters are moved across the image but never rotated, so they will not match a rotated version of the feature they were trained to detect (unless that feature happens to be rotationally symmetric)

Q4 (2.5 points)
- .5 for attempting the question
- Up to 1 point for for providing a clinical application that is plausible
- Up to 1 point for a thoughtful description of this application, including at least one obstacle that might be encountered during its development or implementation