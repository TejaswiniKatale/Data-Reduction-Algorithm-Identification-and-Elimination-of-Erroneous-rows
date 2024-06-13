Data Reduction without the removal of exact,
 correct rows is a crucial pre-processing step. Large
 Datasets make it difficult to model data effectively or
 forecast results accurately. Additionally, they demand
 lengthy processing times, sophisticated complexity
 software and thorough data cleaning. The incorrect and
 irrelevant rows may produce inaccurate results that
 impair the performance of the model. For better and
 more accurate outcomes it is crucial to properly detect
 and remove inaccurate data. The proposed algorithm
 calculates the Initial Recall value of the Dataset. It
 eliminates least correlated features using the Correlation
 Matrix. Using Gaussian Curve, for all the columns it
 identifies and eliminates rows having values which lie
 beyond (µ ± 3σ). Furthermore, it takes into account the
 column with the highest Standard Deviation, selects the
 nearest 50% Left and 50% Right values from that
 column's mean. It selects only those rows and calculates
 the Final Recall value. Negligible difference between
 Initial and Final Recall values implies that the removed
 rows had no or minimal impact on the Dataset's final
 result. This algorithm is implemented on 3 Standard
 Medical Datasets- Pima Diabetes, Heart Attack and
 Breast Cancer. For the Breast Cancer Dataset, this
 algorithm eliminated the highest number of rows that is
 231.
