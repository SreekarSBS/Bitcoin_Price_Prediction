# 📈 Bitcoin Price Prediction 

![Bitcoin Price Prediction Banner](https://img.shields.io/badge/Bitcoin-Price%20Prediction-orange?logo=bitcoin)  
![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter) ![License](https://img.shields.io/badge/License-MIT-green)

---

## 🌟 Overview
This project leverages historical Bitcoin (BTC-USD) data to predict future closing prices using machine learning. The pipeline includes:
- **📥 Data Fetching**: Historical data from Yahoo Finance (2005–2025).
- **🔁 Data Processing**: Using `pandas` and `numpy`.
- **🔮 Prediction**: Forecast closing prices for the next 10 days.
- **📊 Visualization**: Plot predictions with annotations.
- **💾 Model Saving**: Save the trained model as `model.keras`.

---
![image](https://github.com/user-attachments/assets/4b418970-ba3c-4228-8fd3-9a9ce2003c93)
---

## 🛠️ Setup & Usage

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/your-username/bitcoin-price-prediction.git
cd bitcoin-price-prediction
```

### 2️⃣ **Install Dependencies**
Install the required Python libraries:
```bash
pip install yfinance pandas numpy matplotlib tensorflow
```

### 3️⃣ **Launch Jupyter Notebook**
Ensure Jupyter Notebook is installed, then launch it:
```bash
pip install notebook
jupyter notebook
```
- Open `Finalccbtproject.ipynb` in your browser.

### 4️⃣ **Run the Notebook**
The notebook will:
- 📥 Fetch BTC-USD data (2005–2025)
- 🔁 Preprocess and train the model
- 🔮 Predict closing prices for the next 10 days
- 📊 Plot predictions with annotated values
- 💾 Save the trained model as `model.keras`

---
![image](https://github.com/user-attachments/assets/74bad53d-7c89-4b11-bddd-aa60eddbfa06)
---

## 📁 Project Structure
```plaintext
bitcoin-price-prediction/
│
├── Finalccbtproject.ipynb   # 📜 Main Jupyter Notebook (logic)
├── model.keras              # 💾 Trained model file
└── README.md                # 📖 Project documentation
```

---

## 📊 Visualization
The notebook generates a **line chart** of predicted Bitcoin prices:
- **X-axis**: Days ahead (1 to 10)
- **Y-axis**: Predicted closing prices
- **🏷️ Annotations**: Each point is labeled with the predicted price

![image](https://github.com/user-attachments/assets/f0f6edd6-58b8-4cf0-89e5-4995de4e816d)
---
### Example Prediction Output:
| Day   | Predicted Price  |
|-------|------------------|
| Day 1 | $67,892.21       |
| Day 2 | $68,234.42       |
| ...   | ...              |

> 💡 **Note**: The actual plot will be displayed when running the notebook. To embed a sample plot image, save the plot as `prediction_plot.png` and add `![Prediction Plot](prediction_plot.png)` here.

---

## 📁 Data Details
- **Source**: Yahoo Finance (`BTC-USD` ticker)
- **Time Range**: 2005 to June 2025
- **Features**:
  - Open
  - High
  - Low
  - Close
  - Volume

---

## 🔮 Future Improvements
- 📐 Add model architecture and training details (e.g., LSTM, Dense layers).
- 📏 Include error metrics (RMSE, MAE, etc.) to evaluate predictions.
- 📆 Extend the forecast horizon beyond 10 days.
- 🪙 Add support for other cryptocurrencies or financial assets (e.g., ETH-USD, stocks).

---

## 🪪 License
This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

---

## 👤 Author
- **Sreekar SBS**  


---

## 🙏 Acknowledgments
- **Thanks to `yfinance`** for providing easy access to financial data via their API.
- **Inspired by** various financial machine learning tutorials and resources.

---

### 💻 Technologies Used
| Tool/Library    | Purpose                  |
|-----------------|--------------------------|
| 🐍 Python       | Core programming language|
| 📈 yfinance     | Fetch financial data     |
| 🗃️ pandas       | Data manipulation        |
| 🔢 numpy        | Numerical computations   |
| 📊 matplotlib   | Data visualization       |
| 🧠 tensorflow   | Machine learning model   |

---

### 📢 Get Involved!
- ⭐ Star this repository if you find it useful!
- 🐛 Report bugs or suggest improvements by opening an issue.
- 📜 Contribute by submitting a pull request.
