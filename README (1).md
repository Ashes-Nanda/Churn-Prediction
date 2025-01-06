# Customer Churn Prediction Application

This repository contains a **Streamlit-based web application** for predicting customer churn. The application leverages a trained deep learning model built with TensorFlow and integrates with various preprocessing tools, such as scalers and encoders, to ensure accurate predictions.

---

## Features

- **Interactive Web UI**: Built using Streamlit for user-friendly input and result visualization.
- **Churn Prediction**: Predict the likelihood of a customer churning based on multiple features like geography, gender, age, and more.
- **Preprocessing Pipelines**: Handles data scaling, encoding, and preparation for model input.
- **Trained Deep Learning Model**: Utilizes TensorFlow for accurate churn predictions.

---

## Installation

### Prerequisites

- Python 3.7 or higher
- Pip package manager

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/customer-churn-prediction.git
   cd customer-churn-prediction
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Place the required model and preprocessing files in the project directory:
   - `model.h5`
   - `label_encoder_gender.pkl`
   - `onehot_encoder_geo.pkl`
   - `scaler.pkl`

4. Run the application:
   ```bash
   streamlit run app.py
   ```

---

## Usage

1. Navigate to the Streamlit app in your browser.
2. Provide the necessary input features:
   - **Geography**: Dropdown selection
   - **Gender**: Dropdown selection
   - **Age**: Slider
   - **Balance**: Number input
   - **Credit Score**: Number input
   - **Estimated Salary**: Number input
   - **Tenure**: Slider
   - **Number of Products**: Slider
   - **Has Credit Card**: Dropdown (Yes/No)
   - **Is Active Member**: Dropdown (Yes/No)
3. View the **Churn Probability** and prediction result.

---

## File Structure

- **`app.py`**: Streamlit app for user interaction and predictions.
- **`requirements.txt`**: List of dependencies required for running the project.
- **Model Files**: Pretrained TensorFlow model and preprocessing tools.

---

## Technologies Used

- **Python**
- **TensorFlow**
- **Streamlit**
- **Scikit-learn**
- **Pandas**
- **NumPy**

---

## Contributing

Contributions are welcome! Please fork this repository and create a pull request to propose changes.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgments

- Inspired by real-world churn prediction use cases.
- Developed using TensorFlow and Streamlit.
