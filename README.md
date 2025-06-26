# Random-Forest-classifier(Titanic dataset)
I applied a Random Forest classifier to the Titanic dataset to predict passenger survival. After cleaning and encoding categorical features like Deck, Embarked, and Ticket using one-hot encoding, I split the data into training and testing sets. The model was trained on the training data and evaluated on the test set using accuracy as the metric.
## Project Steps

1. Load and explore the Titanic dataset.
2. Handle missing values (e.g., fill missing Cabin data and extract Deck).
3. Drop irrelevant columns like Cabin and Name.
4. One-hot encode categorical variables (`Deck`, `Embarked`, `Ticket`).
5. Split data into training and testing sets.
6. Train a Random Forest classifier.
7. Evaluate model performance using accuracy.

## How to Run

1. Install required packages:
   ```bash
   pip install pandas scikit-learn
