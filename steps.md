# Machine Learning Workflow

1. Data Collection
2. Understanding Data
	i. importing necessary libraries
	ii. check row and columns
	iii. check data types
	iv. Check data distribution
3. Data Cleaning
	i. Handle datatype issues
	ii. Maintain Data Consistency
	iii. Check if data contains outliers or if the data is not normally distributed to decide between mean or median
	iv. Identify missing values
	v. Handle missing values by-
		 a.Drop missing values
		 b. Mean, median or mode imputation
		 c. Prediction Model
		 d. replace missing values
	vi. Duplicate data detection and treatment
	vii. Repeat data cleaning
4. Data Splitting
	i. Split the dataset into training, validation, and test sets.
5. EDA
	i. Variable Identification
		 a. Identify predictor and features
		 b. Identify types or category of data
	ii. Univariate Analysis
	iii. Bi-variate Analysis
	iv. Outlier detection and treatment
	v. Encoding
	vi. Feature Engineering
	       	 a. Feature selection by reducing dimensionality
	vii. Variable Transformation
		 a. Normalization
		 b. Scaling
	viii. Variable Creation
6. Model Building
	i. Model Training on training set
	ii. Model Evaluation and cross validate
	iii. Fine Tuning or Model optimization
	iv. Model selection
7. Evaluate model accuracy with test data.


Sometimes step 4 and 5 comes before data cleaning.
