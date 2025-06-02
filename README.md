# Data Science Nanodegree: ML Pipelines Project

This project demonstrates the implementation of machine learning pipelines using Scikit-learn. It focuses on creating reproducible, maintainable, and production-ready ML workflows.

## Getting Started

These instructions will help you set up and run the project on your local machine for development and testing purposes.

### Dependencies

You need jupyter notebook to run the code. Instructions on how to install jupyter notebook can be found [here](https://jupyter.org/install).

You need the following dependencies (used versions in parentheses!):

- scikit-learn (1.6.1)
- pandas (2.2.3)
- spacy (3.8.7)
- notebook(7.4.3)
- matplotlib (3.10.3)


### Installation

1. Clone this repository to your local machine:

```
git clone https://github.com/yourusername/dsnd-pipelines-project.git
```

2. Navigate to the project directory:

```
cd dsnd-pipelines-project`
````

3. Create and activate a virtual environment (optional but recommended):


```
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

4. Install the dependencies:

```
pip install -r requirements.txt
```

## Testing

there are no tests yet

## Project Instructions

The project is contained in the `starter.ipynb` file.
It covers the following steps:

1. <b>Data Loading and Exploration </b></br>
   - Loads the data from the csv file and performs some basic exploration.
2. <b>Data Preparation</b></br>
   - Preparing features (`X`) & target (`y`)
   - Split the data into training and test sets.
3. <b>Feature Engineering</b>
   - Split data into numerical and categorical features
   - Plot some charts to understand the data
4. <b>Build the pipelines</b>
   - numerical pipeline (imputation and scaling)
   - categorical pipeline (imputation and encoding)
   - text pipeline (preprocessing and vectorization)
   - full pipeline (combining all the above pipelines and add Random Forest classifier)
5. Evaluate the model
   - fit the model
   - calculate the accuracy score
   - plot the confusion matrix
6. Model Fine-tuning
   - Perform hyperparameter tuning using RandomizedSearchCV
   - Perform hyperparameter tuning using RandomizedSearchCV
   - Evaluate the model with the best hyperparameters
     - calculate the accuracy score
     - plot the confusion matrix

## License

[License](LICENSE.txt)
