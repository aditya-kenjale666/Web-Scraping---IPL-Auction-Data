# IPL 2025 Player Retentions - Web Scraping 🏏

## 📌 Project Overview

This project uses Python and web scraping to collect TATA IPL 2025 player retention data from the official IPL website.

The scraped data is extracted from an HTML table, converted into a Pandas DataFrame, and saved as a CSV file for further analysis.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Requests
- BeautifulSoup
- Jupyter Notebook
- Web Scraping

## 🔍 Project Workflow

1. Send a request to the IPL website using `Requests`
2. Parse the webpage using `BeautifulSoup`
3. Locate the player retention table
4. Extract table headers and rows
5. Create a Pandas DataFrame
6. Save the extracted data as a CSV file

## 📊 Data

The dataset contains information about IPL franchises, including:

- Franchise
- Number of Players
- Number of Overseas Players
- Number of Uncapped Players
- RTM
- Total Money Spent
- Salary Cap Available
- Available Slots
- Overseas Slots

## 📈 Key Findings

Based on the scraped data:

- 10 IPL franchises are included in the table.
- A total of 46 players were retained.
- ₹558.5 crore was spent on player retentions.
- Rajasthan Royals had the highest total money spent at ₹79 crore.
- Punjab Kings had the lowest total money spent at ₹9.5 crore.
- 10 overseas players were retained.
- 12 uncapped players were retained.

## 📂 Files

| File | Description |
|------|-------------|
| `ipl-auction-stats.ipynb` | Jupyter Notebook containing the complete web scraping code |
| `TATA_IPL_2025_Player_Retentions.csv` | CSV file containing the scraped IPL retention data |

## 🌐 Data Source

Data was collected from the official IPL website.

## ▶️ How to Run

1. Clone or download this repository.
2. Open `ipl-auction-stats.ipynb` in Jupyter Notebook, JupyterLab, Google Colab, or VS Code.
3. Run the notebook cells.
4. The scraped data will be saved as:
   
   `TATA_IPL_2025_Player_Retentions.csv`

## 👤 Author

Aditya Suresh Kenjale
