# FACEBOOK-FREIND-RECOMMENDATION

About Dataset:
  - The dataset is in the format of directed graph data.
  - There are an approx. 1.86M nodes and 9.43M edges.
  - Data was obtained from kaggle. You can get data from here https://www.kaggle.com/c/FacebookRecruiting

Performance metric:
  - Precision and recall are used as performance metric for this project.
 
Training Dataset preperation:
  - We consider Yi = 1 if an edge is present and Yi = 0 if an edge is not present.
  
Featurizations:
  * Similarity measures
    - Jaccard Distance
    - Cosine distance
  * Ranking Measure
    - Page Ranking (https://en.wikipedia.org/wiki/PageRank)
  * Graph Features
    - Shortest Path
    - Checking for same community
    - Adamic/Adar Index
    - Is following back
    - Katz Centrality
    - Hits Score
    - num followers
    - num followees
  * Weight Features
  * SVD features using Adjancy matrix. (n_components = 6)
  
  Models:
  The two models used were - RandomForest and XGBOOST.
  
  
