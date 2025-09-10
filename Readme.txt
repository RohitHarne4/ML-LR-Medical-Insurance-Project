# Medical Insurance Price Prediction

This project is a web application built with Flask that predicts medical insurance charges based on user input. The prediction is powered by a trained Linear Regression model.

## Features

- Predicts insurance charges using age, gender, BMI, children, smoking status, and region.
- User-friendly web interface.
- Model trained and saved as `Build_new_model_Medical_insurance.pkl`.

## Project Structure

- `main.py` — Flask web app ([main.py](main.py))
- `Build_new_model_Medical_insurance.pkl` — Trained model file
- `labelEncoding.json` — Label encoding for categorical variables
- `templates/index.html` — Web page template ([templates/index.html](templates/index.html))
- `static/` — Static files (images)
- `config.py`, `Utils.py` — Utility/configuration scripts

## Setup Instructions

1. **Clone the repository**  
   ```
   git clone <repo-url>
   cd ML-LR-Medical-Insurance-Project
   ```

2. **Install dependencies**  
   ```
   pip install flask numpy scikit-learn
   ```

3. **Run the app**  
   ```
   python main.py
   ```
   The app will start at [http://localhost:5000](http://localhost:5000).

## Usage

1. Open the web page in your browser.
2. Fill in the required details (age, gender, BMI, children, smoker, region).
3. Click **Predict Charges** to view the predicted insurance price.

## Model Training

- Model training and evaluation are documented in [Build new Model for Medical Insurance Price Prediction.ipynb](Build%20new%20Model%20for%20Medical%20Insurance%20Price%20Prediction.ipynb).
- The trained model is saved as `Build_new_model_Medical_insurance.pkl`.

## License

This project is for