# Climate Challenge Week 0 - African Climate Trend Analysis

## Project Overview
This project analyzes climate data across African countries as part of the B9W0 Climate Challenge.  
It includes data cleaning, exploratory data analysis (EDA), and comparison of climate trends between countries.

## Project Structure
- notebooks/ → Jupyter notebooks for EDA (Ethiopia, Kenya, Nigeria, etc.)
- data/ → Cleaned datasets (ignored in GitHub)
- app/ → (Optional) Streamlit dashboard
- scripts/ → Utility scripts
- .github/workflows/ → CI pipeline

## Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/your-username/climate-challenge-week0.git
cd climate-challenge-week0
2. Create virtual environment
python -m venv venv
venv\Scripts\activate   # Windows
3. Install dependencies
pip install -r requirements.txt
Running Notebooks

Open Jupyter Notebook or VS Code and run:

notebooks/ethiopia_eda.ipynb
notebooks/kenya_eda.ipynb
notebooks/nigeria_eda.ipynb
notebooks/compare_countries.ipynb
Key Features
Data cleaning (handling missing values and outliers)
Climate trend analysis (temperature, rainfall, humidity)
Country comparison
Visualization of climate patterns
Notes
All CSV data files are excluded using .gitignore
This project follows Git workflow with feature branches and pull requests
