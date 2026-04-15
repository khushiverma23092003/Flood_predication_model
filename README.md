🌊 Flood Prediction System using Machine Learning

A robust, data-driven system designed to predict flood risks at the district level using historical rainfall patterns. This project leverages Machine Learning to analyze monthly and seasonal rainfall data to provide early warnings and risk assessments.

🚀 Project Overview
Flood disasters cause significant economic and life loss annually. This project aims to mitigate these risks by using a **Random Forest Classifier** to identify districts at high risk of flooding based on precipitation anomalies.

The model is trained on a comprehensive dataset containing state-wise and district-wise monthly rainfall data, achieving an accuracy of **80-85%**, making it reliable for general risk assessment.

✨ Key Features
- **District-Wise Analysis:** Predicts flood risk for specific districts across the country.
- **Seasonal Analysis:** Incorporates seasonal totals (Monsoon, Winter, etc.) for better context.
- **High Accuracy:** Optimized to maintain a balance between precision and recall (80-85% Accuracy).
- **Interactive Visualization:** Generates confusion matrices and feature importance charts to show which months contribute most to floods.
- **Risk Probability:** Provides a percentage likelihood of flood occurrence for any selected district.

🛠️ Technology Stack
- **Language:** Python 
- **Environment:** Google Colab 
- **Libraries:**
  - `Pandas`: For data manipulation and analysis.
  - `NumPy`: For numerical computations.
  - `Scikit-Learn`: For model building, training, and evaluation.
  - `Matplotlib` & `Seaborn`: For data visualization.

📊 Dataset Structure
The system utilizes a CSV file (`flood_data.csv`) with the following structure:
- **STATE_UT_NAME**: Name of the State/UT.
- **DISTRICT**: Specific district name.
- **JAN - DEC**: Monthly rainfall values in mm.
- **ANNUAL**: Total yearly rainfall.
- **Jan-Feb, Mar-May, Jun-Sep, Oct-Dec**: Seasonal rainfall totals.

