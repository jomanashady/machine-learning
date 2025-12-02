# Healthcare Fraud Detection Project

## Project Overview
Machine learning system to detect fraudulent healthcare providers using Medicare claims data.

## Team Members
- Rawda Tarek
- Jomana Shady
- Karma Kandil
- Mohamed Haytham
- Omar Abdelhady

## Project Structure
- `notebooks/`: Three main Jupyter notebooks for the full pipeline
- `data/`: Raw and processed datasets
- `models/`: Saved models and scalers
- `reports/`: Evaluation results and visualizations

## How to Run
1. Install requirements: `pip install -r requirements.txt`
2. Place your 4 CSV files in `data/raw/`:
   - Train_Beneficiarydata-1542865627584.csv
   - Train_Inpatientdata-1542865627584.csv  
   - Train_Outpatientdata-1542865627584.csv
   - Train-1542865627584.csv
3. Run notebooks in order: 01 → 02 → 03

## Results Summary
- Best Model: Random Forest with SMOTE
- Test F1-Score: 0.724
- Test Recall: 0.851
- Test Precision: 0.628
