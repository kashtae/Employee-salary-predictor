![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-1.25-FF4B4B?style=for-the-badge&logo=streamlit)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-1.3-F7931E?style=for-the-badge&logo=scikit-learn)
![XGBoost](https://img.shields.io/badge/XGBoost-1.7-00639C?style=for-the-badge&logo=xgboost)

A sophisticated web application built with Streamlit that predicts employee salaries using a powerful XGBoost machine learning model. This project demonstrates an end-to-end data science workflow, from model training to a polished, interactive, and deployable web application.

---

### **Live Application:** [**🚀 View the Deployed App Here!**](https://employe-salary-prediction-using-ml-4xk5frvaqtl3fuvwn5w5cu.streamlit.app/)

<!-- Add a screenshot of your beautiful app! -->
![AI Salary Oracle Screenshot](https://github.com/kashish-singh/Employe-Salary-Prediction-Using-ML/blob/main/Screenshots/Website.png)

---

## ✨ Key Features

*   **Interactive UI with Glassmorphism:** A stunning and modern user interface built with Streamlit and custom CSS, featuring a "glassmorphism" design for a professional look and feel.
*   **Powerful XGBoost Model:** Utilizes a highly accurate `XGBoost Regressor` model to provide reliable salary predictions.
*   **Dynamic Salary Range Prediction:** Instead of a single value, the app predicts a realistic salary range, better communicating the model's confidence.
*   **Animated & Engaging UX:** Incorporates Lottie animations for a more engaging and responsive user experience.
*   **Model Performance Insights:** Users can view the model's evaluation plot and R² score in a clean, expandable section.
*   **Fully Deployable:** The project is structured with all necessary files (`requirements.txt`, etc.) for seamless deployment on platforms like Streamlit Community Cloud.

---

## 🛠️ Tech Stack & Libraries

*   **Core Language:** Python
*   **Web Framework:** Streamlit
*   **Machine Learning:** Scikit-learn, XGBoost
*   **Data Manipulation:** Pandas
*   **Model Persistence:** Joblib
*   **Animations:** Streamlit Lottie

---

## 🚀 How to Run Locally

To get a local copy up and running, follow these simple steps.

### Prerequisites
*   Python 3.9+
*   Git

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/kashish-singh/income-predictor.git
    cd income-predictor
    ```

2.  **Create and activate a virtual environment:**
    ```bash
    # For macOS/Linux
    python3 -m venv venv
    source venv/bin/activate

    # For Windows
    python -m venv venv
    .\venv\Scripts\activate
    ```

3.  **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

### Running the Application

Once the dependencies are installed, run the Streamlit app with this command:

```bash
streamlit run app.py
