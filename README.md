# IMDb-Movie-Review-Sentiment-Analysis
This project involves classifying IMDb movie reviews as either positive or negative using text mining techniques. The goal is to extract meaningful insights from user feedback, enabling marketers, filmmakers, and production companies to better understand audience sentiment and make more informed, data-driven decisions.

**Objectives:**

Analyze unstructured review text to extract underlying sentiment.
Develop a classification model to categorize reviews as positive or negative.
Assess model effectiveness through multiple cross-validation techniques.
Illustrate how text analytics can inform marketing strategies and production decisions.

**Dataset**
Source: Kaggle – IMDb Reviews Dataset (https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews?resource=download)
Attributes:
review_text: User-generated movie review content
Target Variable: Sentiment (positive / negative)

**Methodology**

***** Text Preprocessing

Tokenized the review text
Removed stop words to eliminate irrelevant terms
Applied case normalization for consistency
Performed stemming to reduce words to their root form

***** Feature Engineering

Identified significant attributes using RapidMiner’s Select Attributes operator
Assigned appropriate roles for input and output variables

***** Modeling Techniques

Implemented k-Nearest Neighbors (k-NN) with multiple distance metrics (Euclidean, Manhattan)
Applied Support Vector Machine (SVM) for linear text classification.

***** Model Evaluation

Performed 3-fold, 20-fold, and 200-fold cross-validation
Assessed model accuracy and analyzed performance trade-offs.

**Insights:**

Lower k values yield higher sensitivity but increase overfitting risk.
Higher k values improve stability and generalization.
Increasing the number of folds enhances reliability but raises computational cost.

**💡 Business Impact**

Positive reviews can be harnessed to strengthen marketing campaigns.
Negative reviews help identify areas for storytelling or product improvement.
Overall, the model supports data-driven decision-making for improving customer engagement and strategic planning.
