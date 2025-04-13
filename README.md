# 🚀 Startup_Analysis Dashboard

This project provides an interactive **Streamlit web application** to analyze Indian startup funding data. It includes insights for **overall funding trends**, **startup-specific details**, and **investor-wise analysis**.

## 📊 Features

- 📌 Overall metrics like Total Funding, Average Ticket Size, and Funded Startups count.
- 📈 Month-over-Month (MoM) trend visualization.
- 👤 Investor-specific details including:
  - Most recent investments
  - Sector-wise distribution
  - Year-on-Year investment trends
- 🏢 Startup selection panel (under development)

---

## 🧠 Tech Stack

- **Python**
- **Streamlit** for UI
- **Pandas** for data manipulation
- **Matplotlib** for visualization

---

## 📁 Project Structure

```
📦startup-funding-analysis/
├── startup_cleaned.csv       # Dataset used for analysis
├── app.py                    # Main Streamlit application (your code)
├── README.md                 # Project documentation
```

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Nik11sam/Startup_Analysis.git
   cd Startup_Analysis
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

   > If `requirements.txt` is not available, install manually:
   ```bash
   pip install streamlit pandas matplotlib
   ```

3. **Make sure `startup_cleaned.csv` is in the same directory.**

4. **Run the Streamlit app**
   ```bash
   streamlit run app.py
   ```

---

## 📊 Dataset

Make sure your `startup_cleaned.csv` file contains the following important columns:

- `date` (e.g., 2020-03-14)
- `startup`
- `vertical`
- `city`
- `round`
- `amount`
- `investors`

---

## 🛠 Future Enhancements

- ✅ Add detailed startup-wise analysis.
- ✅ Add filters by city, round, sector.
- ✅ Optimize loading speed for large datasets.

