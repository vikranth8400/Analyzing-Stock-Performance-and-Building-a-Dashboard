# 📊 Tesla and GameStop Stock and Revenue Data Analysis

This project extracts stock price and revenue data for **Tesla (TSLA)** and **GameStop (GME)** using `yfinance` and web scraping with `BeautifulSoup`. It then visualizes stock trends over time.

---

## 🔧 Technologies Used
- Python 3.x
- Pandas
- yfinance
- Requests
- BeautifulSoup (bs4)
- Matplotlib
- Jupyter Notebook / Colab

---

## 📂 Project Structure
```bash
├── Tesla_GME_Analysis.ipynb       # Main Jupyter Notebook
├── README.md                      # Project overview (this file)
├── images/
│   ├── Q1.png                     # Tesla stock data (head)
│   ├── Q2.png                     # Tesla revenue data (tail)
│   ├── Q3.png                     # GameStop stock data (head)
│   ├── Q4.png                     # GameStop revenue data (tail)
│   ├── Q5.png                     # Tesla stock graph
│   ├── Q6.png                     # GameStop stock graph
```

---

## 📌 Tasks Overview

### ✅ Q1: Extract Tesla Stock Data using yfinance
- Used `yf.Ticker("TSLA")` and reset the index
- 📸 Screenshot: ![Q1](https://github.com/vikranth8400/Analyzing-Stock-Performance-and-Building-a-Dashboard/blob/c7a9a02be288b9e850fc9d377119f5ce37e99c38/Q1.png)

### ✅ Q2: Extract Tesla Revenue via Web Scraping
- Scraped "Tesla Quarterly Revenue" table from Macrotrends
- 📸 Screenshot: ![Q2](https://github.com/vikranth8400/Analyzing-Stock-Performance-and-Building-a-Dashboard/blob/38a621c124b4b3b342071b77d3f394a89d5740a9/Q2.png
)

### ✅ Q3: Extract GameStop Stock Data using yfinance
- Used `yf.Ticker("GME")` and reset the index
- 📸 Screenshot: ![Q3](https://github.com/vikranth8400/Analyzing-Stock-Performance-and-Building-a-Dashboard/blob/38a621c124b4b3b342071b77d3f394a89d5740a9/Q3.png)

### ✅ Q4: Extract GameStop Revenue via Web Scraping
- Scraped "GameStop Quarterly Revenue" table from Macrotrends
- 📸 Screenshot: ![Q4](https://github.com/vikranth8400/Analyzing-Stock-Performance-and-Building-a-Dashboard/blob/38a621c124b4b3b342071b77d3f394a89d5740a9/Q4.png)

### ✅ Q5: Visualize Tesla Stock Data
- Created line graph for Tesla stock trend
- 📸 Screenshot: ![Q5]([images/Q5.png](https://github.com/vikranth8400/Analyzing-Stock-Performance-and-Building-a-Dashboard/blob/38a621c124b4b3b342071b77d3f394a89d5740a9/Q5.png))

### ✅ Q6: Visualize GameStop Stock Data
- Created line graph for GameStop stock trend
- 📸 Screenshot: ![Q6]([images/Q6.png](https://github.com/vikranth8400/Analyzing-Stock-Performance-and-Building-a-Dashboard/blob/38a621c124b4b3b342071b77d3f394a89d5740a9/Q6.png))

---

## 🚀 How to Run
1. Clone this repo
2. Open `Tesla_GME_Analysis.ipynb` in Jupyter or Google Colab
3. Run all cells to extract data, scrape revenue, and visualize trends

---

## 📝 Notes
- Revenue data scraped from [Macrotrends](https://www.macrotrends.net)
- Stock data pulled using [yfinance](https://pypi.org/project/yfinance/)
- Graphs show price trends; revenue can be used to overlay for further analysis

---

## 📧 Contact
Feel free to reach out for questions or suggestions!

---

