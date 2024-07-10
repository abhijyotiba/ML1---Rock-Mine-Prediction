# ML1---Rock-Mine-Prediction



## Project Focus
AI and Machine Learning


## Tools & Environment
- **Programming Language:** Python
- **Platform:** Google Collaboratory (cloud-based)
  - No need to install Python locally
  - Supports running Python scripts in the browser

## Use Case Description
**Scenario:** Submarine detecting mines vs rocks using sonar data.  
Sonar signals are used to differentiate between metal (mines) and rocks.  
**Objective:** Create a model to predict whether an object is a mine or a rock based on sonar data.

## Project Workflow
### Data Collection
- Collect sonar data using laboratory experiments.
- Data is obtained from sound signals bouncing off metal cylinders (mines) and rocks.

### Data Preprocessing
- Preprocess the raw data to make it suitable for machine learning models.
- Analyze the data to understand its structure and content.

### Train-Test Split
- Split the preprocessed data into training data and test data.
- Typically, 90% for training and 10% for testing.

### Model Training
- Use Logistic Regression for the classification task (binary classification: mine or rock).
- Train the model using training data.

### Evaluation
- Evaluate the model using test data to determine its accuracy.

### Prediction System
- Create a system that uses the trained model to predict new data instances as mine or rock.

## Data & Libraries Used
### Data
- **Dataset:** Sonar Data (CSV file)
  - Available on platforms like Kaggle and UC machine learning repositories.
  - Consists of 208 instances and 61 columns (60 features + 1 label: 'R' for rock, 'M' for mine).

### Libraries
- **NumPy:** For numerical operations
- **Pandas:** For data manipulation and analysis
- **Scikit-Learn:**
  - **train_test_split:** For splitting data
  - **LogisticRegression:** For training the model
  - **accuracy_score:** For evaluating the model
  - 
## Conclusion

Successfully built a predictive model to distinguish between mines and rocks using sonar data.

- **Logistic Regression** was effective for this binary classification task.
- Practice and try to implement more advanced models and larger datasets for better accuracy.
