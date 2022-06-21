# Predicting-cancer-diagnosis
Using SVM (Support Vector Machines) to predicting cancer diagnosis
# Task
•	Predicting if the cancer diagnosis is benign or malignant based on several observations/features
  
30 features are used, examples:

•	  - radius (mean of distances from center to points on the perimeter)

•	  - texture (standard deviation of gray-scale values)

•	  - perimeter

•	  - area

•	  - smoothness (local variation in radius lengths)

•	  - compactness (perimeter^2 / area - 1.0)

•	  - concavity (severity of concave portions of the contour)

•	  - concave points (number of concave portions of the contour)

•	  - symmetry 

- fractal dimension ("coastline approximation" - 1)

•	Datasets are linearly separable using all 30 input features

•	Number of Instances: 569

•	Class Distribution: 212 Malignant, 357 Benign

•	Target class:

•	   - Malignant

•    - Benign

# Methods

•	Get data from .csv

•	Visualization
   
   o	Visualization with seaborn ad matplotlib

•	Model training
   
   o	SVM (Support Vector Machines)
# Result
Using SVM (Support Vector Machines). The result is shown in the table below:

Target: Benign: 0, Malignant: 1

|	          |precision|recall|f1-score|support|
|-----------|---------|------|--------|-------|
|0	        |1.00     |0.92  |0.96    |48    |
|1	        |0.94    |1.00  |0.97    |62     |
|accuracy   |-	      |-	   |0.96	  |114    |
|macro avg  |0.97     |0.96  |0.96	  |114   |
|weighted avg|0.97    |0.96  |0.96	  |114   |
