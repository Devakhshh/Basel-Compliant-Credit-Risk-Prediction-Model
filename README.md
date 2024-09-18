
# Basel-Compliant Credit Risk Prediction Model

## Overview

This project develops a **Basel III/IV-compliant credit risk prediction model**. The model is designed to estimate the **Probability of Default (PD)** for borrowers, ensuring compliance with **Basel III/IV regulations**. It integrates advanced machine learning techniques, including data preprocessing, feature engineering, and model interpretability methods. Additionally, it incorporates stress testing to ensure robustness under different economic conditions.

## Project Structure

The repository contains the following files:

- `Basel_Compliant_Credit_Risk_Dataset.csv`: The dataset used for training the predictive models, including over 32,000 borrower entries with demographic and financial details.
- `Source_Code.ipynb`: The Jupyter notebook with the source code for data preprocessing, feature engineering, model training, evaluation, and Basel compliance calculations.
- `Research Paper.pdf`: The research paper providing an in-depth explanation of the development process, methodology, and results.

## Key Features

- **Compliance with Basel III/IV**: The model aligns with the Basel III/IV regulatory frameworks, ensuring that predictions are compliant with risk management and capital adequacy requirements.
- **Machine Learning Models**: The project includes several machine learning models, including **XGBoost**, **Random Forests**, and a **Neural Network**.
- **Stress Testing**: The model's performance is validated under various economic stress conditions, demonstrating its resilience and robustness.
- **Model Interpretability**: Techniques such as **SHAP** (SHapley Additive exPlanations) are used to ensure transparency in model predictions.

## Results

- **ROC AUC Scores**: The best-performing model, a **Stacking Classifier**, achieved a **ROC AUC score of 0.94**, demonstrating excellent predictive capability.
- **Stress Testing**: The model remained stable under economic stress, showing minor performance reductions while maintaining regulatory compliance with Basel III/IV standards.

## How to Run the Project

1. Clone the repository:
   ```
   git clone https://github.com/YourUsername/Basel-Compliant-Credit-Risk-Prediction-Model.git
   ```

2. Install the required libraries:
   - The project requires Python 3.x and several libraries, including:
     - `pandas`
     - `scikit-learn`
     - `xgboost`
     - `shap`
   - Install them using `pip`:
     ```
     pip install -r requirements.txt
     ```

3. Open and run the Jupyter notebook (`Source_Code.ipynb`) to train the model and generate predictions.

## Dashboard

A user-friendly **Gradio** dashboard has been developed to make real-time predictions. Users can input borrower details and receive credit risk predictions directly through the interface.

## Future Work

Future enhancements could include:
- Integrating **non-traditional data sources** like social media and transaction data to further improve prediction accuracy.
- **Optimizing deployment** for smaller financial institutions.
- Developing dynamic, real-time stress testing functionality.

## License

This project is licensed under the MIT License - see the full license text below.

---

### MIT License

```
MIT License

Copyright (c) 2024 [Devadharshni Raju]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
