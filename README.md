EV-Vehicle-Charging-Demand-Prediction

Project Overview

The Electric Vehicle (EV) Adoption Forecasting project predicts future adoption of electric vehicles using historical registration data from the Washington State Department of Licensing (DOL).

This forecasting model helps urban planners anticipate infrastructure needs, particularly for EV charging stations, supporting sustainability goals and enhancing user experience.

📊 Dataset

The dataset contains monthly vehicle registration records in Washington State, categorized by vehicle type. Key features include:

Feature	Description
Date	Vehicle registration date (YYYY-MM-DD)
County	Geographic region of the vehicle owner
Vehicle Primary Use	Primary intended use of the vehicle (e.g., Passenger, Truck)
Battery Electric Vehicles (BEVs)	Count of fully electric vehicles
Plug-In Hybrid Electric Vehicles (PHEVs)	Count of hybrid electric vehicles
Electric Vehicle (EV) Total	Sum of BEVs and PHEVs
Non-Electric Vehicle Total	Count of non-electric vehicles
Total Vehicles	All registered vehicles in the county
Percent Electric Vehicles	Percentage of EVs compared to total vehicles
⚙️ Requirements

Install the necessary Python libraries:

pip install pandas numpy matplotlib seaborn scikit-learn streamlit joblib

🚀 How to Run

Option 1: Run locally

Clone the repository:

git clone https://github.com/yourusername/EV-Vehicle-Charging-Demand-Prediction.git
cd EV-Vehicle-Charging-Demand-Prediction


Run the Streamlit app:

streamlit run app.py


Option 2: Launch on Streamlit Cloud

Click the badge below to open the app directly:

🔮 Features

Forecast EV adoption trends for the next 3 years by county.

Visualize historical and forecasted cumulative EVs.

Compare EV adoption trends across up to 3 counties.

Display forecasted percentage growth for selected counties.

📁 File Structure
EV-Vehicle-Charging-Demand-Prediction/
│
├── app.py                    # Streamlit app
|-- Ev_adoption_forecasting.ipynb  
├── forecasting_ev_model.pkl  # Trained ML model
├── preprocessed_ev_data.csv  # Preprocessed dataset
├── ev-car-factory.jpg        # Supporting image for app
└── README.md                 # Project documentation

💡 Contribution

This project was prepared as part of AICTE Internship Cycle 2 by S4F. Contributions and suggestions are welcome.
