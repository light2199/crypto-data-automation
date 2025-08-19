# crypto-data-automation

This project demonstrates how to automate cryptocurrency data extraction from the CoinMarketCap API 💰📊 and structure it for easy analysis. The program connects to the API, retrieves live cryptocurrency data, and converts the raw JSON response into a clean Pandas DataFrame 🐼.

⚙️ How to Use

1️⃣ Update the API URL 🌐 – Replace the sample endpoint with the one you want to use.
2️⃣ Insert your own API Key 🔑 – Change the placeholder key with the API key generated from your CoinMarketCap account.

✨ Key Features & Modifications

✅ Adjusted the row limit from 5000 ➝ 15 for easier handling.
✅ Renamed values & columns 📝 to make the dataset more understandable.
✅ Applied filtering 🔍 to remove unnecessary data fields.
✅ Added a new column called Timestamp ⏱️ to track when the data was pulled.
✅ Automated the extraction process so new data can be appended at regular intervals 🔄.
✅ Option to save results into a CSV file 📂 for historical analysis.

🚀 Why this Project?

This project can serve as a starting point for anyone who wants to build:
📊 Cryptocurrency dashboards
📈 Trend analysis models
⏱️ Real-time market monitoring tools
