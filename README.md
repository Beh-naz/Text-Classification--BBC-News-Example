# Text-Classification--BBC-News-Example
Analyzed and clustered 1,500 BBC news articles into clusters such as business and sports comparing different models and choosing the logistic regression model based on its performance.

The code is stored in "MyTextClassification.ipynb" file.

## Data:
The dataset "BBCNewsDataset" is uploaded to this repository.
 
## Sections:

### Environment Preparation
Before running the script, make sure to install the required packages:

pandas, numpy, openpyxl, matplotlib, seaborn, scikit-learn, yellowbrick, nltk


### Data Exploration

The dataset consists of news articles categorized into five classes: business, entertainment, politics, sport, and tech. Here are some details about the dataset:

Number of records: 1440

Number of columns: 2 (Text, Category)

Data types: object (Text, Category)

### Train and test data splits
Split the dataset into training (80%) and testing (20%) sets. Split the training set into training (80%) and validation (20%) sets.

### Models Training and Evaluation
Four models are trained and evaluated using k-fold cross-validation:

Logistic Regression

K-Nearest Neighbors

Naive Bayes

Random Forest

The models are evaluated based on their accuracy scores, confusion matrices, and classification reports.

### Best Model Selection
The best-performing model (Logistic Regression) is selected based on its performance with $95\%$ accuracy on the test set.
