# 🏡 GeoPricePredictor: Ames Housing Price Prediction with GIS Integration

This project combines data science, geographic information systems (GIS), and web development technologies to create a comprehensive system for predicting housing prices in Ames, Iowa. Developed using the Kaggle House Prices competition dataset, the project is enhanced with spatial analysis capabilities.

## 🚀 Project Features

### 🤖 Data Science and Machine Learning
- Advanced regression techniques (XGBoost, LightGBM, CatBoost)
- Feature engineering and selection
- Model performance optimization
- Model interpretability with SHAP values
- Cross-validation and hyperparameter optimization

### 🗺 Geographic Information Systems (GIS)
- Interactive map visualizations with Folium
- Neighborhood-based price analysis
- Impact of spatial features on prices
- Location-based price predictions
- Price distribution analysis with heat maps

### 🗄 Database and Backend
- PostgreSQL database integration
- Efficient data storage and querying
- Data pipeline automation
- Model results storage in database

### 🌐 Web Interface
- Interactive user interface with Streamlit
- Real-time price predictions
- Dynamic map visualizations
- User-friendly form interface
- Responsive design

## 🛠Technical Stack

### Technologies Used
- **Programming Language:** Python 3.9+
- **Data Processing:** Pandas, NumPy
- **Machine Learning:** Scikit-learn, XGBoost, LightGBM, CatBoost
- **Visualization:** Matplotlib, Seaborn, Plotly
- **GIS:** Folium, Geopy
- **Web Framework:** Streamlit
- **Database:** PostgreSQL
- **Deployment:** Heroku
- **Version Control:** Git/GitHub

### 📁 Project Structure
```
├── data/                  # Raw and processed data
├── notebooks/            # Data analysis and modeling notebooks
├── src/                  # Source code
│   ├── data/            # Data processing scripts
│   ├── models/          # ML model training and evaluation
│   ├── gis/             # GIS analysis and visualization
│   ├── database/        # Database operations
│   └── web/             # Streamlit web application
├── tests/               # Unit tests
├── requirements.txt     # Project dependencies
└── README.md           # Project documentation
```

## ⚙ Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/bersinada/GeoPricePredictor_Ames.git
cd GeoPricePredictor_Ames
```

2. Create and activate virtual environment:
```bash
python -m venv venv
# For Windows:
venv\Scripts\activate
# For Linux/Mac:
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## ▶ Usage

1. Database setup:
```bash
# Create PostgreSQL database and import tables
python src/database/setup_database.py
```

2. Model training:
```bash
python src/models/train_model.py
```

3. Launch web application:
```bash
streamlit run src/web/app.py
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact

[Berat Sinan Ada](https://www.linkedin.com/in/berat-sinan-ada-349673219/) 