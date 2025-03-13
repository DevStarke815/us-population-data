# **US Population Data Web Page**

## **Introduction**
This project retrieves and displays US Population data using an API from Data USA.

---

## **What It Does**
- Fetches US population data from `https://datausa.io/api/data?drilldowns=Nation&measures=Population`
- Parses and sorts the data in descending order by year
- Displays the data in a clean, responsive HTML table

---

## **Example Output**
Upon loading the page, a table will display the population data:

| Year | Population |
|------|------------|
| 2022 | 333,287,557 |
| 2021 | 331,893,745 |
| 2020 | 331,002,651 |
| ...  | ... |

---

## **How It Works**
1. The HTML page (`index.html`) loads and runs a JavaScript script.
2. The script makes an API request to Data USA.
3. The response is parsed, sorted, and dynamically inserted into an HTML table.
4. The data updates in real time whenever the page loads.

---

## **How to Run**
1. Open `index.html` in a browser.
2. If using VS Code, install **Live Server** and click "Go Live" for automatic updates.
