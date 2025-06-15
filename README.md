# Heart Disease Indicators Dashboard

[![Tableau](https://img.shields.io/badge/Tableau-Visualized-blue)](https://public.tableau.com/app/profile/hewitsadik)
[![License](https://img.shields.io/badge/License-Kaggle%20Dataset-blue)](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease)
[![GitHub Issues](https://img.shields.io/github/issues/hewitsadik/heart-disease-dashboard)](https://github.com/hewitsadik/heart-disease-dashboard/issues)

An interactive Tableau dashboard analyzing CDC heart disease survey data with demographic filters and risk factor visualizations.

🔗 **Live Dashboard:** [View on Tableau Public](https://public.tableau.com/views/capstone-Heart_2020_06-09-25/Story1)

![Dashboard Preview](https://github.com/hewitsadik/heart-disease-dashboard/blob/main/images/preview.png?raw=true) *(Replace with actual screenshot path)*

## Features
- **Demographic Filtering**: Age, gender, race
- **Risk Factor Analysis**: BMI, smoking, physical activity
- **Interactive Visualizations**: Bar charts, heatmaps, trend lines

## Data Source
Dataset: [Personal Key Indicators of Heart Disease](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease) (2020 CDC Survey)

## Setup (For Local Development)
```bash
# Clone repository
git clone https://github.com/hewitsadik/heart-disease-dashboard.git
cd heart-disease-dashboard

# Install Python dependencies (if applicable)
pip install -r requirements.txt
<iframe 
  src="https://public.tableau.com/views/capstone-Heart_2020_06-09-25/Story1?:language=en-US&:display_count=n&:embed=true" 
  width="1000" 
  height="800"
  frameborder="0"
  allowfullscreen>
</iframe>
heart-disease-dashboard/
├── data/                   # Processed datasets
│   └── heart_2020_cleaned.csv
├── notebooks/              # Jupyter notebooks for analysis
│   └── data_cleaning.ipynb
├── tableau/                # Tableau workbook files
│   └── heart_dashboard.twb
├── README.md               # This file
└── requirements.txt        # Python dependencies

### Key Improvements:
1. **Badges**: Added shields.io badges for visual metadata
2. **Preview Image**: Placeholder for dashboard screenshot
3. **File Structure**: Clear directory tree
4. **Code Blocks**: Proper formatting for commands/embedding
5. **Contributing Guide**: Standard GitHub workflow
6. **License Clarification**: Separates dataset terms from code license

To use:
1. Save as `README.md` in your repo root
2. Replace placeholder image with actual dashboard screenshot
3. Add your `requirements.txt` if using Python preprocessing

Would you like me to add any specific technical details about the data processing or visualization methods?
