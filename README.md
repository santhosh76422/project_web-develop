# 🔭 Pulsar Search Project

The **Pulsar Search System** is a web-based platform designed to store, search, and retrieve pulsar observation files with high efficiency. It provides an intuitive interface to filter and locate required pulsar data from large datasets.

---

## ✅ Features

* Search pulsar files easily through web interface
* Auto-ingest **daily CSV datasets** into the database
* Supports **range-based search and float filtering**
* **Autocomplete suggestions** for Source Name
* Select multiple rows using **checkboxes**
* **Download selected rows as CSV**
* Displays complete record details in table format

---

## 🏗️ System Architecture

| Layer                    | Technology                                               |
| ------------------------ | -------------------------------------------------------- |
| Frontend                 | HTML, CSS, JavaScript                                    |
| Backend                  | Python (Flask Framework)                                 |
| Database                 | SQLite                                                   |
| Data Source              | Daily CSV auto-ingest                                    |
| Filtering / Search Logic | SQL Range Filters (LIKE, ≥, ≤), Epoch float filtering    |
| Deployment (Local)       | Flask Dev Server                                         |
| Misc Features            | CSV Download, Autocomplete, Checkboxes for row selection |

---

## 🔍 Search Filters Supported

| Filter           | Type                |
| ---------------- | ------------------- |
| Source Name      | Text + Autocomplete |
| File Name        | Text                |
| GMRT Start Time  | Range               |
| GMRT End Time    | Range               |
| Epoch (MJD)      | Float Range         |
| Dimension Radius | Float Range         |

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Run Flask app

   ```bash
   python app.py
   ```
4. Open browser and go to:

   ```
   http://127.0.0.1:5000/
   ```

---

## 📂 Folder Structure (Example)

```
/pulsar-search-project
│── app.py
│── templates/
│── static/
│── data/
│── daily_updates/
│── database.sqlite
│── README.md
```

---

## 📝 Future Enhancements 

* Export results as **PDF**
* User login accessibility
* Advanced analytics & visualization dashboard

---

## 👨‍💻 Author

**Santhosh**
Pulsar Search Project • 2025

---
