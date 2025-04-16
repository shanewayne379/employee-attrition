# Attrition Prediction Streamlit Project

This project aims to predict employee attrition using machine learning models and provides a Streamlit interface for users to interact with the model.

## Project Structure
```
Attrition-prediction-streamlit/
├── Dataset/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── Models/
│   └── Attrition.pkl
├── attrition.py
├── model.py
└── requirements.txt
```

### Folder and File Details

- **Dataset/**
  - `WA_Fn-UseC_-HR-Employee-Attrition.csv`: The dataset containing employee information used for training and evaluating the model.

- **Models/**
  - `Attrition.pkl`: The serialized machine learning model saved as a pickle file.

- **attrition.py**
  - Contains code for data preprocessing, feature engineering, and other data-specific tasks related to attrition prediction.

- **model.py**
  - Contains code for training the machine learning model and saving it as `Attrition.pkl` in the `Models` folder.

- **requirements.txt**
  - Lists all the required Python libraries to run the project.

## Getting Started

### Prerequisites

- Python 3.x

### Creating a Virtual Environment

1. Navigate to the project directory.
2. Create a virtual environment with your desired name:

   ```bash
   python -m venv <your_env_name>

3. Activate the virtual environment:
   - On Windows:

     ```bash
     <your_env_name>\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source <your_env_name>/bin/activate
     ```

### Installation

1. Clone the repository.
   ```bash
   git clone https://github.com/meet3264/Employee_Attrition_Prediction_Streamlit.git
   cd Employee_Attrition_Prediction_Streamlit
2. Navigate to the project directory (if not already there).
3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt

### Usage

1. Ensure that `WA_Fn-UseC_-HR-Employee-Attrition.csv` is available in the `Dataset` folder.
2. Run `attrition.py` and `model.py` as needed to train and evaluate the model, and save it as `Attrition.pkl` in the `Models` folder.
3. Deploy the model using Streamlit.

### Running the Streamlit App

To start the Streamlit app, use:

```bash
streamlit run <your_main_app_file>.py
```

Make sure to replace <your_main_app_file>.py with the name of your main Streamlit application file (for example, app.py).

### Dataset

This project uses an HR Employee Attrition dataset, which contains features related to employee demographics, job role, satisfaction, and more, to help predict the likelihood of employee attrition.

   
