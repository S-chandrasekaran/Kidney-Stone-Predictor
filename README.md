🧪 Kidney Stone Prediction App

This Streamlit web app predicts the risk of kidney stone formation based on user-input urine parameters. It uses a machine learning model trained on clinical data to classify individuals as high or low risk.

🚀 Features
- Interactive sliders for inputting urine test values
- Real-time prediction using a trained Random Forest model
- Clean and intuitive user interface
- Deployable on Streamlit Cloud

📊 Dataset
The model is trained on a dataset (kidney_stone_data.csv) containing the following features:
- Urine Specific Gravity
- Urine pH
- Osmolality
- Conductivity
- Urea (mg/dL)
- Calcium (mg/dL)
- Target (binary: 0 = Low Risk, 1 = High Risk)

🧠 Model
- Algorithm: Random Forest Classifier
- Preprocessing: StandardScaler for feature normalization
- Evaluation: Classification report and confusion matri

🛠️ Installation
- Clone this repository:
git clone https://github.com/your-username/kidney-stone-predictor.git
cd kidney-stone-predictor
- Install dependencies:
pip install -r requirements.txt
- Run the app:
streamlit run app.py

☁️ Deployment (Streamlit Cloud)
To deploy:
- Push your code to a public GitHub repository
- Include app.py, requirements.txt, and kidney_stone_data.csv
- Go to Streamlit Cloud and link your repo
- Click “Deploy"

📁 File Structure
├── app.py                 # Streamlit app
├── kidney_stone_data.csv # Dataset
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation

📌 Requirements
pandas
scikit-learn
streamlit
numpy
joblib

🙋‍♂️ Author
Chandrasekaran
Machine Learning Enthusiast | Streamlit Explorer
