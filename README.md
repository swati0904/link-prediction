# __Link Prediction between Facebook Users using Machine Learning__
This project aims to predict **potential connections or links between Facebook users** using machine learning techniques. The project utilizes Python libraries such as pandas, numpy, networkx, logistic regression, catboost, and xgboost to build and evaluate the predictive model. Additionally, the node2vec library is employed for feature extraction based on natural language processing (NLP) techniques.

### Project Structure
__The project is structured as follows:__
#### Preprocessing: 
The initial phase involves cleaning and preprocessing the dataset to ensure **data quality and consistency**. This includes handling missing values, removing duplicates, and transforming the data into a suitable format for further analysis.
#### Feature Extraction:
In this phase, the **node2vec** NLP library is utilized to extract relevant features from the Facebook user data. The library employs graph embedding techniques to capture the semantic meaning of nodes in a network, enabling the extraction of meaningful features for link prediction.
#### Model Development:
The extracted features are used as inputs to train machine learning models. The project employs **logistic regression, catboost, and xgboost** models to predict the likelihood of links between Facebook users. Each model is trained on a labeled dataset consisting of existing connections.

## Dependencies
__The following Python libraries are required to run the project:__

- __pandas__: Used for data manipulation and preprocessing.  
- __numpy__: Required for numerical computations and array operations.      
- __networkx__: Used for graph creation and manipulation.  
- __logistic regression__: A machine learning algorithm utilized for link prediction.  
- __catboost__: A gradient boosting library used for building predictive models. 
- __xgboost__: Another gradient boosting library employed for model development.
- __node2vec__: A Python library for graph embedding and feature extraction.

## Conclusion
By leveraging machine learning algorithms, NLP techniques, and the power of graph-based feature extraction, this project aims to predict potential connections between Facebook users. The project demonstrates the usage of various Python libraries and provides insights into the accuracy of different machine learning models for link prediction tasks.
