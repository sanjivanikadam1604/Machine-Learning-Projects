# Spam Mail Detection using Machine Learning

## About the Project

This project focuses on detecting whether a message is **Spam** or **Ham (Not Spam)** using Machine Learning and Natural Language Processing (NLP).

The SMS messages are converted into numerical features using **TF-IDF Vectorization**, and multiple machine learning models are trained and compared to find the best-performing algorithm.


## Dataset Information

- Dataset: SMS Spam Collection Dataset
- Total Messages: 5,572
- Categories:
  - Ham (Not Spam)
  - Spam


## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- TF-IDF Vectorizer



## Steps Performed

1. Loaded and cleaned the dataset
2. Removed unnecessary columns
3. Converted labels into numerical values
4. Split data into training and testing sets
5. Applied TF-IDF Vectorization
6. Trained multiple machine learning models
7. Evaluated and compared model performance



## Models Used

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 96.05% |
| Decision Tree | 96.77% |
| Random Forest | 97.91% |
| K-Nearest Neighbors | 93.31% |



## Best Model

**Random Forest Classifier** achieved the highest accuracy of **97.91%** and showed the best overall performance for spam detection.



## Results

The project successfully classifies SMS messages as Spam or Ham with high accuracy. Model comparison helped identify the most effective algorithm for this dataset.


## Future Improvements

- Build a Streamlit web application
- Deploy the model online
- Perform hyperparameter tuning
- Add visualizations and insights
- Explore Deep Learning approaches


## Author

**Sanjivani Kadam**  
B.Tech Robotics and Artificial Intelligence  
COEP Technological University
