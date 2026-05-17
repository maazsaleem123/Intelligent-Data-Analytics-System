# 🔬 Intelligent Data Analytics System

<div align="center">

**Upload your dataset — get instant cleaning, deep analysis, beautiful visualizations, and exportable reports.**

[![Live App](https://img.shields.io/badge/🚀%20Live%20App-Click%20to%20Open-636EFA?style=for-the-badge)](https://intelligent-data-analytics.streamlit.app/)
[![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)](https://python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-Framework-FF4B4B?style=for-the-badge&logo=streamlit)](https://streamlit.io)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</div>

---

## 🚀 Live Demo

👉 **[https://intelligent-data-analytics.streamlit.app/](https://intelligent-data-analytics.streamlit.app/)**

Open the app, upload any CSV or Excel file, and instantly explore your data — no setup needed.

---

## 📸 App Screenshots

### 🏠 Home — Upload Your Dataset
> Clean dark-themed landing page with drag & drop file upload. Supports CSV and Excel (.xlsx) files up to 200MB.

![Home](https://raw.githubusercontent.com/maazsaleem123/Intelligent-Data-Analytics-System/main/screenshots/01_home.png)

---

### 📄 Step 1 — Dataset Preview
> Instantly see your full dataset in a scrollable table. Shows total rows, total columns, and load status. Your original file is always kept safe and unchanged.

![Dataset Preview](https://raw.githubusercontent.com/maazsaleem123/Intelligent-Data-Analytics-System/main/screenshots/02_dataset_preview.png)

---

### 🧹 Step 2 — Data Cleaning
> Detects missing values column-by-column and duplicate rows. One-click removal buttons keep your original data safe — all cleaning happens on a working copy.

![Data Cleaning](https://raw.githubusercontent.com/maazsaleem123/Intelligent-Data-Analytics-System/main/screenshots/03_data_cleaning.png)

![After Cleaning](https://raw.githubusercontent.com/maazsaleem123/Intelligent-Data-Analytics-System/main/screenshots/05_after_cleaning.png)

---

### 💚 Step 3 — Data Health Score
> Visual progress bar showing your data quality as a percentage. Color-coded status: 🟢 Excellent (100%) · 🟡 Good (80%+) · 🔴 Needs Cleaning.

![Health Score 85%](https://raw.githubusercontent.com/maazsaleem123/Intelligent-Data-Analytics-System/main/screenshots/04_health_score_85.png)

![Health Score 100%](https://raw.githubusercontent.com/maazsaleem123/Intelligent-Data-Analytics-System/main/screenshots/06_health_score_100.png)

---

### 📊 Step 4 — Data Analysis
> Full statistical summary (count, mean, std, min, max, quartiles) for all numeric columns. Select any column to view its value counts instantly.

![Data Analysis](https://raw.githubusercontent.com/maazsaleem123/Intelligent-Data-Analytics-System/main/screenshots/07_data_analysis.png)

---

### 📈 Step 5 — Interactive Visualization
> Choose any column and chart type — Bar, Pie, Line, Area, or Histogram. All charts are fully interactive (zoom, hover, pan). A precise Graph Data Table is shown below the chart.

![Visualization](https://raw.githubusercontent.com/maazsaleem123/Intelligent-Data-Analytics-System/main/screenshots/08_visualization.png)

![Graph Data Table](https://raw.githubusercontent.com/maazsaleem123/Intelligent-Data-Analytics-System/main/screenshots/09_graph_data_table.png)

---

### 💡 Step 6 — Advanced Recommendations
> Highlights the highest and lowest performing values. Displays Top 3 and Bottom 3 values, percentage contribution of each category, and a context-aware Smart Suggestion tailored to your column type.

![Advanced Recommendations](https://raw.githubusercontent.com/maazsaleem123/Intelligent-Data-Analytics-System/main/screenshots/10_recommendations.png)

---

### 🧠 Step 7 — Auto Insight Summary
> Auto-generated text insights based on your actual data. Includes a detailed Insight paragraph and Key Observations — no manual analysis needed.

![Auto Insight](https://raw.githubusercontent.com/maazsaleem123/Intelligent-Data-Analytics-System/main/screenshots/11_auto_insight.png)

---

### 📥 Step 8 — Download Report
> Click "Preview & Download Report" to see a complete preview of all 8 steps, then download as a professional Word (.docx) or PDF report — with charts, tables, insights, and recommendations all included.

![Download Button](https://raw.githubusercontent.com/maazsaleem123/Intelligent-Data-Analytics-System/main/screenshots/12_download_button.png)

![Report Preview](https://raw.githubusercontent.com/maazsaleem123/Intelligent-Data-Analytics-System/main/screenshots/13_report_preview.png)

![Download Word and PDF](https://raw.githubusercontent.com/maazsaleem123/Intelligent-Data-Analytics-System/main/screenshots/20_download_word_pdf.png)

---

## ✨ Features at a Glance

| Step | Feature | Description |
|------|---------|-------------|
| 1 | 📄 Dataset Preview | View full data table with row & column count |
| 2 | 🧹 Data Cleaning | Detect & remove missing values and duplicates with one click |
| 3 | 💚 Health Score | Visual data quality percentage with color-coded status |
| 4 | 📊 Data Analysis | Statistical summary + value counts for any column |
| 5 | 📈 Visualization | 5 interactive chart types — Bar, Pie, Line, Area, Histogram |
| 6 | 💡 Recommendations | Top/bottom values, % contribution & smart suggestions |
| 7 | 🧠 Auto Insights | Auto-generated text insights from your data |
| 8 | 📥 Download Report | Export full analysis as Word (.docx) or PDF |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| [Streamlit](https://streamlit.io) | Web app framework |
| [Pandas](https://pandas.pydata.org) | Data loading & analysis |
| [Plotly](https://plotly.com/python/) | Interactive charts |
| [Matplotlib](https://matplotlib.org) | Chart image export for reports |
| [python-docx](https://python-docx.readthedocs.io) | Word (.docx) report generation |
| [ReportLab](https://www.reportlab.com) | PDF report generation |
| [OpenPyXL](https://openpyxl.readthedocs.io) | Excel file reading |

---

## 📦 Installation & Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/maazsaleem123/Intelligent-Data-Analytics-System.git
cd Intelligent-Data-Analytics-System
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the app
```bash
streamlit run app.py
```

### 4. Open in browser
```
http://localhost:8501
```

---

## 📋 Requirements

```
streamlit
pandas
matplotlib
plotly
openpyxl
python-docx
reportlab
```

All dependencies are listed in `requirements.txt`.

---

## 📁 Project Structure

```
Intelligent-Data-Analytics-System/
│
├── app.py                  # Main Streamlit application
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
└── screenshots/            # App screenshots used in README
    ├── 01_home.png
    ├── 02_dataset_preview.png
    ├── 03_data_cleaning.png
    ├── 04_health_score_85.png
    ├── 05_after_cleaning.png
    ├── 06_health_score_100.png
    ├── 07_data_analysis.png
    ├── 08_visualization.png
    ├── 09_graph_data_table.png
    ├── 10_recommendations.png
    ├── 11_auto_insight.png
    ├── 12_download_button.png
    ├── 13_report_preview.png
    └── 20_download_word_pdf.png
```

---

## 📖 How to Use

1. **Open** the [live app](https://intelligent-data-analytics.streamlit.app/) or run it locally
2. **Upload** your CSV or Excel file using the Upload button
3. **Preview** your dataset — see all rows, columns, and load status
4. **Clean** your data — detect and remove missing values & duplicates with one click
5. **Check** the Data Health Score — see your data quality as a percentage
6. **Analyze** — view statistical summary and value counts for any column
7. **Visualize** — pick a column and chart type to generate an interactive graph
8. **Read** smart recommendations and auto-generated insights for your data
9. **Download** the full report as Word or PDF — ready to share or present

---

## 💡 Supported File Types

| Format | Extension | Max Size |
|--------|-----------|----------|
| CSV | `.csv` | 200 MB |
| Excel | `.xlsx` | 200 MB |

---

## 📊 What's Inside the Downloaded Report

Every downloaded Word or PDF report contains:

- ✅ Full dataset table
- ✅ Missing values per column
- ✅ Data health score & status
- ✅ Complete statistical summary
- ✅ Value counts for selected column
- ✅ Chart image (the exact graph you selected)
- ✅ Graph data table
- ✅ Top 3 & Bottom 3 values
- ✅ Percentage contribution table
- ✅ Smart suggestion
- ✅ Auto insight summary
- ✅ Key observations

---

## 👨‍💻 Author

**Maaz Saleem**
- GitHub: [@maazsaleem123](https://github.com/maazsaleem123)

---

## ⭐ Support

If you find this project useful, please give it a **star ⭐** on GitHub — it helps others discover it!

[![GitHub stars](https://img.shields.io/github/stars/maazsaleem123/Intelligent-Data-Analytics-System?style=social)](https://github.com/maazsaleem123/Intelligent-Data-Analytics-System/stargazers)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">
  <b>Built with ❤️ using Streamlit & Python</b>
</div>
