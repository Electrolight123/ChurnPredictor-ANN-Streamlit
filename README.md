# ChurnPredictor-ANN-Streamlit

ChurnPredictor-ANN-Streamlit is a machine learning project designed to predict customer churn using Artificial Neural Networks (ANN). The model is trained using the Churn_Modelling dataset and deployed through a user-friendly Streamlit interface. Additionally, the project includes hyperparameter tuning using GridSearchCV and model performance visualization using TensorBoard.

## Features
- Customer churn prediction using ANN.
- Data preprocessing with encoding and scaling.
- Hyperparameter tuning using GridSearchCV.
- Streamlit interface for user interaction.
- TensorBoard visualization for training monitoring.

## Installation

1. **Clone the repository:**  
```bash
git clone https://github.com/yourusername/ChurnPredictor-ANN-Streamlit.git
cd ChurnPredictor-ANN-Streamlit
```

2. **Create a virtual environment and activate it:**  
- On Unix/Mac:  
```bash
python -m venv env
source env/bin/activate
```

- On Windows:  
```bash
python -m venv env
env\Scripts\activate
```

3. **Install dependencies:**  
```bash
pip install -r requirements.txt
```

4. **Download the dataset and place it in the main directory.**

## Usage

1. **Train the model:**  
Run the notebooks in the `notebooks/` directory to train the model.

2. **Start the Streamlit app:**  
```bash
streamlit run app.py
```
Access the app at [http://localhost:8501](http://localhost:8501).

## Hyperparameter Tuning
To perform hyperparameter tuning using GridSearchCV, run the `hyperparametertuningann.ipynb` notebook.

## TensorBoard Visualization
To monitor model training using TensorBoard:

```bash
tensorboard --logdir=logs/fit
```
Access TensorBoard at [http://localhost:6006](http://localhost:6006).

## Contributing
Feel free to fork the repository and submit pull requests.

## License
This project is licensed under the MIT License.
