# CryptoCurrency_Dashboard

This project is a Power BI dashboard that visualizes cryptocurrency trends using daily market data.  
It highlights key metrics such as **Volume, High, Average, and Low**, with interactive slicers for **Symbol** and **Year**.  

## Features
- KPI cards for Volume (bn), High, Average, and Low with trend indicators (▲ ▼).
- Interactive slicers for coins and years.
- Charts showing price trends, distribution, and comparative insights.
- Custom styling with dark theme and brand colors.

## Data
Source data includes fields: **Date, Symbol, Open, High, Low, Close, Volume, Marketcap**.  
The dataset (`CryptoData_CSV`) is connected and transformed directly within Power BI.

## Usage
1. Open `Crypto_Analytics.pbix` in Power BI Desktop.  
2. Use the **Symbol** and **Year** slicers to filter results.  
3. Export reports to PDF via **File → Export → PDF**.  

## Tech Stack
- **Power BI Desktop**  
- **DAX** (measures for totals, averages, change %, arrows)  
- **CSV Data Source** (Crypto historical data)  
