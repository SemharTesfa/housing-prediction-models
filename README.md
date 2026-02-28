# 🏠 Housing Price Prediction (Time Series Analysis)

This project explores forecasting housing price trends using machine learning models trained on historical data. Initially tested with monthly data (~350 rows), the final models were trained using **weekly data** (~1500 rows) to improve accuracy and resolution.

## 📈 Key Highlights

- Compared **monthly vs. weekly** time-series datasets  
- Performed **data cleaning**, **resampling**, and **forward-filling** for consistency  
- Trained ML models to detect trends and predict future housing prices  
- Evaluated model performance using visualizations and error metrics

## 📂 Project Structure

- `notebooks/` – Jupyter notebooks for data exploration and modeling  
- `data/` – CSV files with raw and processed housing datasets  
- `models/` – Saved model files
- `results/` – Plots and evaluation results

## 🛠️ Tools Used

- Python 3  
- Jupyter Notebook  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn

## 📊 Findings

- **Monthly data** was clean but limited in training samples, leading to underfitting.  
- **Weekly data** provided better granularity and more records for learning, improving model performance.

## 📄 License

MIT License

---

> Developed by [Semhar Tesfa](https://github.com/SemharTesfa) for educational and research purposes.
