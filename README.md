# Tg Prediction from Molecular Structures using Machine Learning

This project develops a machine learning model to predict the **glass transition temperature (Tg)** of molecules based on their SMILES (Simplified Molecular Input Line Entry System) strings. The model leverages cheminformatics tools like **RDKit** to extract **molecular descriptors** and **fingerprints**, which are then used as features in various regression models.

## 📂 Project Structure

- `Ml_tg_prediction.ipynb` — Main Jupyter Notebook containing data processing, feature extraction, model training, and evaluation.
- `smiles_tg.csv` — Directory containing SMILES strings and Tg values.


## 🔍 Key Features

- **SMILES Parsing** using RDKit.
- **Descriptor and Fingerprint Calculation** for molecular representation.
- **Machine Learning Models** such as Random Forest, Gradient Boosting, or others.
- **Performance Evaluation** using metrics like RMSE, R², MAE.

## 🧪 Libraries Used

- `rdkit` — for chemical informatics and SMILES handling.
- `pandas`, `numpy` — for data manipulation.
- `scikit-learn` — for machine learning models and preprocessing.
- `matplotlib`, `seaborn` — for visualization.

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. manually install:

```bash
pip install rdkit pandas scikit-learn matplotlib seaborn
```

3. Run the `Ml_tg_prediction.ipynb` notebook.

## 📊 Example Output

The notebook includes visualizations like:

* Feature importance plots
* Predicted vs. actual Tg values
* Error distribution graphs

## 🧠 Future Work

* Hyperparameter tuning
* Testing on external datasets
* Deployment via Flask or Streamlit for user interface

## 📜 License

This project is open-source and free to use under the MIT License.

