# final-Project-4
readme_content = """# Telecom Churn Prediction
This project predicts customer churn in the telecom industry using machine learning models.

## Files Included:
- **customer_churn_analysis.py**: Python script for data processing and model training.
- **Telecom_Churn_Prediction_Combined.pptx**: PowerPoint presentation with project details and visualizations.
- **README.md**: Project documentation.

## Steps to Run:
1. Install dependencies: `pip install -r requirements.txt`
2. Run `customer_churn_analysis.py` to train models.
3. View `Telecom_Churn_Prediction_Combined.pptx` for insights.

## License:
This project is licensed under the MIT License.
"""

# Save README.md file
with open(f"{LOCAL_REPO_DIR}/README.md", "w") as file:
    file.write(readme_content)

print("README.md created successfully!")

