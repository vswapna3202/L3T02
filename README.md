# L3T02 - Supervised Learning - Decision Trees
## Decision Tree for Titanic Survival Prediction

### Overview
This task involves creating a Decision Tree classifier to predict the survival of passengers on the Titanic. The dataset `titanic.csv` is provided in the `decision_tree_titanic.ipynb` file. The objective is to train a decision tree model and evaluate its accuracy on the development set. Additionally, different values of `max_depth` [2-10] are explored to analyze their impact on model performance.

### Dataset
- **titanic.csv**: Contains data on passengers aboard the Titanic. [Source](<titanic.csv>)

### Instructions
#### Setup and Installation
1. **Clone the Repository**
   - Clone this repository to your local machine:
     ```
     git clone https://github.com/vswapna3202/L3T02.git
     ```
2. **Navigate to the Project's Folder**
   - Navigate to the folder containing the project:
     ```
     cd L3T02 or cd <your-task-folder>
     ```

### Workflow
1. **Select Relevant Variables and Split Data**
   - Use relevant variables from the dataset and split the data into training, development, and test sets.

2. **Train a Decision Tree**
   - Train a decision tree classifier on the training data.
   - Make a plot of the decision tree.

3. **Model Evaluation**
   - Compute the accuracy of the model on the development set.
   - Experiment with different values of `max_depth` [2-10].
   - Create plots of the decision trees and store accuracies on both the training and development data for each value of `max_depth`.
   - Plot a line graph of training accuracies and development accuracies to observe trends.

4. **Final Model Evaluation**
   - Report the accuracy of the final decision tree model on the test data.

### Running the Notebook
1. **Start Jupyter Notebook**
   - Start Jupyter Notebook:
     ```
     jupyter notebook
     ```
2. **Open the Notebook**
   - Open the Jupyter notebook `decision_tree_titanic.ipynb` to begin the analysis.

