
AQI Monitoring Web App
🌫️ Interactive Air Quality Analysis, Visualization, and Machine Learning Prediction

    

✨ A beautiful, modern web app for exploring, modeling, and predicting Air Quality Index (AQI) using machine learning. ✨

🚀 Features
📊 Data Exploration: Visualize AQI data, distributions, and correlations
🧹 Preprocessing: Handle missing values, remove outliers, and select features
🤖 Modeling: Train Random Forest, Logistic Regression, or XGBoost models
🏆 Evaluation: View classification reports, confusion matrices, and feature importances
🔮 Prediction: Instantly predict AQI category for new data
💾 Model Saving/Loading: Save and reload trained models
🧪 Testing: Automated tests for data and edge cases
🎨 Modern UI: Clean, responsive, and user-friendly interface
🌈 App Preview
image
image
image

⚡ Quick Start
# 1. Clone the repository
 git clone <your-repo-url>
 cd aqi-monitoring

# 2. Create and activate a virtual environment
 python -m venv .venv
 .venv\Scripts\activate  # On Windows
 # Or
 source .venv/bin/activate  # On Mac/Linux

# 3. Install dependencies
 pip install -r requirements.txt

# 4. Run the Streamlit app
 streamlit run app.py
🧑‍� Usage
Use the sidebar to upload data, select preprocessing, features, and model
Train and evaluate with a click
Predict AQI for new data instantly
Visualize results and download models
�️ Project Structure
├── app.py                # Main Streamlit web app
├── config.py             # Configuration file
├── requirements.txt      # Python dependencies
├── data/                 # Raw and processed data files
├── models/               # Saved models and scalers
├── notebooks/            # Jupyter notebooks (EDA, preprocessing, training, evaluation)
├── tests/                # Unit and edge-case tests
└── screenshots/          # App screenshots (add your own!)
🧪 Testing
Automated tests are provided in tests/.

pytest tests/
� Model Saving/Loading
The app saves and loads models automatically in the models/ directory.

import joblib
# Save model
joblib.dump(model, 'models/aqi_model.pkl')
# Load model
model = joblib.load('models/aqi_model.pkl')
🧐 Data Validation
Built-in checks for missing values, class balance, and outliers
Outlier visualization and feature importance explanations included
🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to fork the repo, open an issue, or submit a pull request.

How to contribute:

⭐ Star this repo to show your support
Fork the project
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
👤 Author
Rahul Sharma
GitHub:Rahul156807
Email: rvyas6277@gmail.com

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.


Made with ❤️ by Rahul Sharma
2025 © All rights reserved.

📄 License
MIT License

