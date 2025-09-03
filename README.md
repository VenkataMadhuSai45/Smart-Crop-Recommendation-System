# Smart Crop Recommendation System

This project is a machine learning-based web application that recommends the most suitable crop to grow based on various environmental and soil parameters. It is designed to help farmers and agricultural professionals make informed decisions to maximize yield and sustainability.

## Features
- Crop recommendation using trained ML models
- User-friendly web interface
- Input parameters: Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, Rainfall
- Visualizations and crop information

## Technologies Used
- Python (Flask for backend)
- HTML, CSS, JavaScript (for frontend)
- Scikit-learn (ML models)
- Pandas, NumPy

## Getting Started

### Prerequisites
- Python 3.x
- pip
- Git

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/VenkataMadhuSai45/Smart-Crop-Recommendation-System.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Smart-Crop-Recommendation-System
   ```
3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application
1. Start the Flask server:
   ```bash
   python app.py
   ```
2. Open your browser and go to `http://localhost:5000`

## Project Structure
- `app.py` : Main Flask application
- `model.pkl`, `minmaxscaler.pkl`, etc. : Trained ML models and scalers
- `static/` : Images and static assets
- `templates/` : HTML files (if using Flask templates)
- `Crop_recommendation.csv` : Dataset used for training
- `README.md` : Project documentation


