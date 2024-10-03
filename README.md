# Personality Prediction System

This project is a GUI-based system built using Python, Tkinter, and scikit-learn's logistic regression model. It predicts a candidate's personality based on inputs such as their age, gender, and scores on the Big Five personality traits. Additionally, it parses the resume of the candidate using the Pyresparser library to extract key information.

## Features

- **Train a Logistic Regression Model**: The model is trained on a dataset to predict personality traits based on various inputs.
- **Predict Personality**: The system allows the user to input their details and personality-related scores, which are used to predict their personality traits.
- **Resume Parsing**: Extracts important information like skills, experiences, etc., from the applicant's resume.
- **Tkinter GUI**: The system is user-friendly with a graphical interface allowing the user to input details easily.

## Personality Traits

The system uses the Big Five personality traits:
1. **Openness**: Enjoy new experiences and being imaginative.
2. **Conscientiousness**: Being organized and thorough.
3. **Extraversion**: Preference for social interactions.
4. **Agreeableness**: Being kind and cooperative.
5. **Neuroticism**: Experience of negative emotions like mood swings.

## Libraries Used

- **Pandas**: For data manipulation.
- **NumPy**: For array handling.
- **Tkinter**: For the graphical user interface.
- **Pyresparser**: To extract information from resumes.
- **Scikit-learn**: For implementing logistic regression and training the model.

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/hritikranjan1/Personality-Prediction-System.git
   cd Personality-Prediction-System
2.Install the Required Libraries: You can install the necessary libraries using pip:
 ```bash
pip install -r requirements.txt
 
