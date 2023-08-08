# IPL Win Predictor

Predict the outcome of Indian Premier League (IPL) cricket matches using machine learning!

## Introduction

This project aims to predict the outcome of IPL cricket matches based on various in-game factors using a machine learning model. It takes into consideration the batting and bowling teams, host city, runs left, balls left, wickets, and other match statistics to estimate the probability of a team winning.

## Table of Contents

- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#projectstructure)
- [Algorithm](#algorithm)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine for development and testing purposes.


## Dependencies
The following libraries are required for this project:

* NumPy
* pandas
* scikit-learn
* matplotlib
  
--> You can install them using the following command:

* pip install numpy pandas scikit-learn matplotlib
  
 ## Installation :

1.Clone this repository to your local machine:

Copy code

git clone https://github.com/your-username/ipl-cricket-prediction.git

2.Navigate to the project directory:

Copy code

cd ipl-cricket-prediction

3.Download the necessary dataset files (matches.csv and deliveries.csv) and place them in the project directory.

4.Run the Jupyter Notebook or Python script to preprocess the data, train the model, and generate predictions.

## Usage: 

* Follow these steps to use the project effectively:

1.Make sure you have the required dependencies installed (NumPy, pandas, scikit-learn, matplotlib).

2.Prepare the dataset files (matches.csv and deliveries.csv) and place them in the project directory.

3.Execute the Jupyter Notebook or Python script to preprocess the data, train the model, and make predictions.

## Project Structure:

* The project directory is organized as follows:

1.README.md: This document, providing project details and instructions.

2.matches.csv: A dataset containing match information.

3.deliveries.csv: A dataset containing ball-by-ball details.

4.ipl_prediction.ipynb: Jupyter Notebook containing code for data preprocessing, model training, and prediction.

5.pipe.pkl: The trained model saved using pickle.

6.sample_output.png: A sample output graph depicting match progression.

## Algorithm :

* The core of this project involves the following steps:

1.Data Preprocessing: The historical match and delivery data are read and merged. Preprocessing includes handling missing values and transforming categorical features.

2.Feature Engineering: Key features such as the current score, runs left, wickets in hand, and more are calculated to provide input for the prediction model.

3.Model Training: The project employs a logistic regression algorithm. One-hot encoding is used for categorical features. The model is trained using historical match data.

4.Outcome Prediction: The trained model predicts the outcome of a match's second inning based on input features.

## Results :

The accuracy of the model on the test set is calculated and displayed, giving insights into its predictive performance. A function is included to visualize the match progression graphically.

## STREAMLIT APP :-

  ![App Screenshot](r"C:\Users\saura\Downloads\Movie_recommender_system-(UI)_2.png")


This repository contains the code for a Streamlit app that predicts the probability of winning an Indian Premier League (IPL) cricket match using machine learning. The app takes input such as the batting and bowling teams, host city, target score, current score, overs completed, and wickets fallen, and provides a prediction of the winning probabilities for the batting and bowling teams.

## Getting Started

To run the app locally, follow these steps:

1. Clone this repository to your local machine.
   
   
   git clone https://github.com/your-username/ipl-win-predictor.git
   

2. Navigate to the project directory.
   
   
   cd ipl-win-predictor
   

3. Create a virtual environment (optional but recommended).
   
   
   python -m venv venv
   source venv/bin/activate
   

4. Install the required dependencies.
   
   
   pip install -r requirements.txt
   

5. Run the Streamlit app.
   
   
   streamlit run app.py
   

6. Access the app in your web browser by visiting `http://localhost:8501`.

## Usage

1. Select the batting and bowling teams from the dropdown menus.
2. Choose the host city from the available options.
3. Enter the target score and your team's current score, overs completed, and wickets fallen.
4. Click the "Predict Probability" button to get the predicted winning probabilities for both teams.

## Model and Data

The prediction is made using a machine learning model trained on historical IPL match data. The model is stored in a pickle file `pipe.pkl` and is loaded into the app for predictions.

## Contributing

Contributions are welcome! If you find any issues or want to enhance the app, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize the content according to your preferences and the specifics of your project. Make sure to replace placeholders like `your-username` with your actual GitHub username. Also, consider adding sections like "References" or "Acknowledgments" if necessary.
