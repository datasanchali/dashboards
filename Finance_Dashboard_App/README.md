# 📊 Finance Dashboard App

An interactive sales dashboard built with **Streamlit**, **Plotly**, **DuckDB**, and **Pandas**, enabling users to explore and analyze yearly financial performance from Excel data.

✨ Features

- Interactive multi-chart layout
- Real-time visual KPIs and gauges
- Easy file upload with Excel support


<img width="1675" height="968" alt="Sales dashboard " src="https://github.com/user-attachments/assets/056cac3e-2b8a-4699-824f-9a0c37a82a4b" />


## 🚀 Try the App Live

Click the link below to launch the app on **Streamlit Cloud**:  
👉 [Launch Dashboard](https://dashboards-ss-finance-app.streamlit.app)

> ⚠️ You’ll need to upload the Excel file `finance_data.xlsx` (available in this repo) to begin.


---

## 📁 Project Structure

```
├── finance_dashboard_app.py   # Main Streamlit app
├── finance_data.xlsx           # Sample dataset to upload
├── requirements.txt           # Python dependencies
└── README.md                  # You're here!
```

---

## 📥 How to Use


1. **Visit the App**  
   Open the [Streamlit app](https://dashboards-ss-finance-app.streamlit.app) in your browser.

2. **Upload the Data**  
   - Download [`finance_data.xlsx`](finance_data.xlsx) from this repo.
   - Use the **sidebar file uploader** in the app to upload it.

3. **Explore the Dashboard**  
   - View key financial metrics (e.g. receivables, payables, ratios).
   - Use interactive Plotly charts to compare Budget vs Forecast.
   - Drill into different business units and accounts.

---

## 🛠️ Run Locally (Optional)

Clone the repo and run the app using:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
pip install -r requirements.txt
streamlit run finance_dashboard_app.py
```

---
## 📦 Requirements

- streamlit  
- pandas  
- plotly  
- duckdb  
- openpyxl

- > These are listed in `requirements.txt` and automatically handled by Streamlit Cloud.

---

## 👤 Author

**Sanchali Singhal**  
_Developed as a demonstration of modern data app capabilities._

---

## 📝 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.


