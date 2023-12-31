# Enhancing Risk Aware Decision in Healthcare through Probabilistic Modeling of Uncertainty
The work was done in collaboration with **Crystalytic AI** (https://www.crystalytic.ai)
## Abstract 
In domains with high stakes, like healthcare and medicine, trustworthy and robust decision making is crucial due to the potential risks associated with misclassification. However, many traditional machine learning classifiers lack calibrated predictions, and reliable uncertainty estimates for new unseen data. This paper addresses the challenge of uncertainty quantification in text classification in healthcare and proposes a three fold approach to support robust and trustworthy decision making by medical practitioners. To evaluate our solution, we implement it on a multilabel medical transcription dataset from Kaggle. Our study demonstrates three significant results: the ability of our model to reject uncertain predictions by providing a null set, the provision of set predictions with guaranteed coverage for further investigation, and the prioritization of decision making based on confidence levels of predictions with the same label. Additionally, we tackle the issue of imbalanced datasets in the medical domain by employing the Mondrian Conformal Predictor with a Naïve Bayes classifier. Our findings are expected to enhance the risk-aware decision making process in the medical field.

<img width="1197" alt="Screenshot 2023-09-21 at 2 30 29 PM" src="https://github.com/rahvis/KDD2023/assets/64368687/1a21969f-a591-4643-9835-b756929c34e2">

## Citations 

```
@misc{rahul_vishwakarma_2023_8170271,
  author       = {Rahul Vishwakarma and
                  Jinha Hwang and
                  Benyamin Ahmadnia},
  title        = {{Enhancing Risk Aware Decision in Healthcare 
                   through Probabilistic Modeling of Uncertainty}},
  month        = aug,
  year         = 2023,
  note         = {{KDD'23 Southern California Data Science Day, 
                   Applied Data Science (ADS) Track, Long Beach, CA}},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.8170271},
  url          = {https://doi.org/10.5281/zenodo.8170271}
}
```
https://zenodo.org/record/8170271
