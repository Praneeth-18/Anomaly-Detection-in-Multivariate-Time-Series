

[**Research Paper Link**]( https://arxiv.org/pdf/2308.03171.pdf)

[**Medium Article link**](https://medium.com/@saipraneethk181200/detection-of-anomalies-in-multivariate-time-series-4acf4fef81e4)

[**Youtube Video link**](https://www.youtube.com/watch?v=bSf8LRmLkw4)

[**Slideshare PPT Link**](https://www.slideshare.net/saipraneethk181200/short-story-on-anomaly-detection-in-multivariate-time-series)





# Detection of Anomalies in Multivariate Time Series Using Ensemble Techniques

### Authors
- Anastasios Iliopoulos, Harokopio University of Athens, Athens, Greece
- Christos Diou, Harokopio University of Athens, Athens, Greece
- John Violos, Harokopio University of Athens, Athens, Greece
- Iraklis Varlamis, Harokopio University of Athens, Athens, Greece

## Abstract
This research focuses on anomaly detection in multivariate time series, a significant challenge in many fields. The study introduces a feature-bagging technique that considers subsets of features and applies a transformation based on nested rotations computed from Principal Component Analysis (PCA) to enhance effectiveness and generalization. The methodology also includes an ensemble technique combining multiple base models for improved prediction performance. The proposed approach is validated experimentally on the Skoltech Anomaly Benchmark (SKAB) dataset.

## Key Contributions
- Introduction of a feature-bagging technique for anomaly detection in multivariate time series.
- A transformation based on nested rotations to improve model effectiveness.
- An ensemble technique combining multiple models for enhanced performance.
- Experimental validation of the methodology using the SKAB dataset.

## Methodology
The paper proposes a multi-step approach combining feature bagging with nested rotations and stacking models for anomaly detection. The process involves:
1. **Feature Bagging**: Creating subsets of features and training multiple models.
2. **Nested Rotations**: Applying PCA for transformation and diversity.
3. **Ensemble Technique**: Combining the models' outputs, using majority voting in unsupervised setup and a Logistic Regressor in semi-supervised setup.

## Experimental Setup and Results
- Implemented in Python using frameworks like NumPy, pandas, Scikit-learn, TensorFlow 2, and Keras API.
- Evaluated on the Skoltech Anomaly Benchmark dataset.
- The ensemble technique demonstrated significant improvement in performance, with an increase in anomaly detection accuracy.

## Conclusions
The study highlights the effectiveness of combining feature bagging and nested rotations in an ensemble approach for anomaly detection in multivariate time series. The ensemble methods outperform base models, suggesting a robust strategy for anomaly detection tasks.

## Acknowledgment
This work was supported by the European Union’s Horizon 2020 research and innovation programme under Grant Agreement No. 965231 for the project REBECCA (REsearch on BrEast Cancer induced chronic conditions supported by Causal Analysis of multi-source data).

