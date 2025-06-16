# 📊 Superstore EDA Dashboard using Streamlit & Plotly

This project is an interactive data visualization dashboard for **Sample Superstore** data built using **Streamlit**, **Pandas**, and **Plotly**. It allows users to perform exploratory data analysis (EDA) with filters and visual insights based on sales, profits, and other metrics.

---

## 🔧 Features

- 📁 File uploader for `.csv`, `.txt`, `.xlsx`, `.xls` formats
- 📆 Date range filtering
- 🌍 Region, State, and City-based filtering
- 📊 Bar chart, Pie chart, Tree map, Line chart, Scatter plot visualizations
- 📈 Time-series and hierarchical analysis
- 📥 CSV download buttons for filtered data and visual outputs
- 🗂 Expandable sections for better UI/UX

---

## 🚀 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/superstore-dashboard.git
cd superstore-dashboard

2. Create a Virtual Environment (Optional but Recommended)
python -m venv dashboard
source dashboard/bin/activate        # For Linux/Mac
dashboard\Scripts\activate.bat       # For Windows

3. Install Required Libraries

pip install -r requirements.txt
Create a requirements.txt file with:
streamlit
pandas
plotly
openpyxl
xlrd

4. Run the Dashboard

streamlit rundashboard.py


📂 Folder Structure

superstore-dashboard/
├── superstore_dashboard.py      # Streamlit app
├── Superstore.xls               # Sample data (optional)
├── README.md                    # Project documentation
├── requirements.txt             # Dependencies



📌 Notes
If no file is uploaded, the app uses Superstore.xls from your local path (C:\Users\ACER\Desktop\dashboard). You can change this behavior to use a bundled sample file or give an error message.

You can deploy this app online using Streamlit Cloud or services like Heroku.

🧠 Inspiration
This project was built as a hands-on visualization dashboard to explore EDA capabilities using Python and modern plotting libraries.

📄 License
This project is open-source and available under the MIT License.
