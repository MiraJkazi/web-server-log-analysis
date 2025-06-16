# 📊 Web Server Log Analysis - Python Project

This project is a Python-based exploratory data analysis of real-world HTTP web server logs from the University of Calgary's Computer Science server. The dataset includes roughly a year’s worth of server access logs, parsed and analyzed to extract meaningful insights about user behavior, server usage trends, and common HTTP status patterns.

---

## 🚀 Project Objectives

- ✅ Parse and clean raw Apache HTTP log data
- 📅 Convert timestamp strings to datetime objects
- 🗂️ Extract file types and handle malformed requests
- 📈 Analyze traffic patterns, common requests, and error codes

---

## 📂 Files in this Repository

| File | Description |
|------|-------------|
| `analysis.ipynb` | Main Jupyter notebook with full code and analysis |
| `README.md` | Project overview, instructions, and results |
| `calgary_access_log.txt` | Python libraries required for the project |

---

## 🛠️ Technologies Used

- **Python** (pandas, datetime, os)
- **Jupyter Notebook**
- **apache-log-parser**


---

## 📉 Sample Insights

- ⏰ Peak access times and daily traffic trends
- ❌ Breakdown of HTTP errors (e.g., 404, 500)
- 📁 Most frequently accessed file types
- 🧠 Patterns in user-agent requests and URLs

---

## 📦 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/web-server-log-analysis.git
   cd web-server-log-analysis
