# ⚡ Energy Theft Detection using Machine Learning

An intelligent system designed to detect energy theft in power distribution networks using machine learning algorithms. This project leverages historical energy consumption data to identify patterns indicative of unauthorized usage, aiding in the reduction of non-technical losses (NTL) in the energy sector.

---

## 📌 Overview

Energy theft poses significant challenges to power distribution companies, leading to substantial revenue losses and grid instability. This project aims to develop a machine learning model capable of:

- **Identifying** unusual consumption patterns
- **Classifying** instances of potential energy theft
- **Predicting** future occurrences based on historical data

By automating the detection process, the system enhances operational efficiency and supports timely interventions.

---

## 🧠 Technologies Used

| Component     | Technology |
|---------------|------------|
| Programming   | Python     |
| Libraries     | scikit-learn, pandas, numpy |
| Model Format  | Pickle (.pkl) |
| Data Format   | CSV        |

---

## 📁 Project Structure

```
Energy-Theft-Detection-using-Machine-Learning/
├── ML Code.ipynb        # Jupyter Notebook containing model training and evaluation
├── energy_data.csv      # Dataset used for training the model
├── model.pkl            # Trained machine learning model
├── scaler.pkl           # Scaler used for feature normalization
├── README.md            # Project documentation
```

---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab

### 🛠 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/faizanl09/Energy-Theft-Detection-using-Machine-Learning.git
   cd Energy-Theft-Detection-using-Machine-Learning
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook ML Code.ipynb
   ```

4. Follow the instructions within the notebook to train the model and evaluate its performance.

---

## 📊 Dataset

The dataset (`energy_data.csv`) comprises historical energy consumption records, including features such as:

- Customer ID
- Consumption metrics
- Temporal data (e.g., time of day, day of week)

These features are utilized to train the machine learning model to recognize patterns associated with energy theft.

---

## 🧪 Model Details

The machine learning model is trained using the dataset to classify instances of potential energy theft. The model is serialized and saved as `model.pkl`, and the feature scaler is saved as `scaler.pkl` for consistent preprocessing during inference.

---

## 📈 Future Enhancements

- **Integration with Real-Time Data:** Incorporate real-time consumption data for dynamic monitoring.
- **Advanced Models:** Explore deep learning techniques for improved accuracy.
- **Deployment:** Develop a web interface or API for easy access and integration with existing systems.

---

## 📎 License

This project is open-source and available under the [MIT License](LICENSE).

---

