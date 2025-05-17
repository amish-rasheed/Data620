# NYC Dining Final Project

This project analyzes and visualizes NYC dining data, leveraging APIs (Yelp, Google Maps) and sentiment analysis to provide insights into restaurant reviews and locations.

## Features
- Data analysis and visualization of NYC dining options
- Integration with Yelp and Google Maps APIs
- Sentiment analysis of restaurant reviews using VADER

## Setup Instructions

### 1. Clone the Repository
```
git clone <repo-url>
cd 620_final_project
```

### 2. Install Dependencies
It is recommended to use a virtual environment:
```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### 3. Set Up API Keys
Create a `.env` file in the project root directory with the following content:
```
YELP_API_KEY=your_yelp_api_key
GOOGLE_MAPS_API_KEY=your_google_maps_api_key
```
Replace `your_yelp_api_key` and `your_google_maps_api_key` with your actual API keys.

### 4. Run the Jupyter Notebook
```
jupyter notebook nyc_dining_final_project.ipynb
```
Open the notebook in your browser and run the cells to execute the analysis.

## Notes
- Ensure you have valid API keys for Yelp and Google Maps.
- If you encounter missing package errors, double-check your virtual environment and `requirements.txt`.