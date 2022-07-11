This repository contains the code for [[Impact of the composition of
feature extraction and class sampling in medicare fraud
detection]{.ul}](https://arxiv.org/abs/2206.01413) research paper.

**Dataset links**

1.  Medicare Part D dataset

> [[Medicare Part D Prescribers - by Provider and
> Drug]{.ul}](https://data.cms.gov/provider-summary-by-type-of-service/medicare-part-d-prescribers/medicare-part-d-prescribers-by-provider-and-drug/data/2018)

2.  LEIE dataset

> [[LEIE Downloadable
> Databases]{.ul}](https://oig.hhs.gov/exclusions/exclusions_list.asp)

**Setup**

For the environment setup:

1.  Upload the above datasets in google drive and change the directory
    > path to dataset loaction in read_csv function.

2.  Install CatBoost, LightGBM, AdaBoost and XGBoost classifiers.

**Supporting resources**

This work uses following resources:

1.  For feature extraction, [[Credit Card Fraud
    > Detection]{.ul}](https://colab.research.google.com/github/dpanagop/ML_and_AI_examples/blob/master/Credit_Fraud_detection_with_autoencoders.ipynb)
    > is followed.

2.  For classified selection, [[Gradient Boosted Decision Tree
    > Algorithms for Medicare Fraud
    > Detection]{.ul}](https://www.researchgate.net/publication/351432766_Gradient_Boosted_Decision_Tree_Algorithms_for_Medicare_Fraud_Detection)
    > is followed.

**Execution**

To execute the code, run all the google colab files to obtain the best
performing architecture for medicare fraud detection.
