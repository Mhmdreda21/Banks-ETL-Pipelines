# ETL Project – Largest Banks Analysis

## 📌 Project Overview
This project demonstrates a simple **ETL (Extract, Transform, Load)** pipeline in Python.  
The pipeline extracts data about the world’s largest banks by market capitalization from **Wikipedia**, transforms the data into multiple currencies using exchange rates, and loads the results into both a **CSV file** and a **SQLite database**.  

Each stage of the pipeline is logged with timestamps for tracking progress.

---

## ⚙️ Technologies Used
- **Python 3.11**
- **Pandas** – Data extraction and manipulation  
- **NumPy** – Mathematical transformations  
- **SQLite3** – Database storage  
- **Requests & BeautifulSoup** – Web scraping  
- **Logging** – Progress tracking  

---

## 🚀 Workflow
1. **Extract**  
   - Scrapes the table of banks by market capitalization from Wikipedia.  
   - Cleans the data and loads it into a Pandas DataFrame.  

2. **Transform**  
   - Reads exchange rates from a CSV file.  
   - Converts the market capitalization into multiple currencies:  
     - USD → GBP, EUR, INR  
   - Rounds values to 2 decimals.  

3. **Load**  
   - Saves the transformed DataFrame to a CSV file.  
   - Loads the data into a SQLite database for queries.  

4. **Logging**  
   - Every function execution is logged in `code_log.txt` with a timestamp.  

---

## 🛠️ Installation & Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/etl-banks-project.git
   cd etl-banks-project
ow.
