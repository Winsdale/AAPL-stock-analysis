README template 
 # AAPL-stock-analysis

 
This project performs a basic financial data analysis on Apple Inc.
 
 
 
1. Problem & User
 
The core problem is to explore the price behaviour, trading volume patterns, and daily returns of AAPL using real-world market data. The intended audience includes my course instructor and peers, who will assess my practical skills in Python-based data analysis.
 
 
 
2. Data
 
- Source: Historical daily trading data for AAPL, downloaded from a reputable public financial website in CSV format.
- Access date: 21 April 2026
- Key fields:  Date ,  Open ,  High ,  Low ,  Close/Last ,  Volume 
- The dataset covers approximately one year of trading records.
 
 
  
3. Methods (Main Python Workflow)
 
The analysis is performed in a Jupyter Notebook ( ACC102_AAPL_Analysis.ipynb ), following these key steps:
 
1. Setup & Import: Load required libraries ( pandas ,  matplotlib ).
2. Data Loading & Inspection: Read the CSV file and explore its structure.
3. Data Cleaning:- Convert the  Date  column to  datetime  format.
- Remove dollar signs from price columns ( Close/Last ,  Open ,  High ,  Low ) and convert them to floats.
- Sort the data by date.
4. Calculations: Compute daily returns using the percentage change in closing prices.
5. Visualization: Generate two plots:- A line chart showing the closing price trend.
- A bar chart showing daily trading volume.
6. Descriptive Statistics: Calculate and display key metrics (mean, standard deviation, max/min values).
 
 
 
4. Key Findings
 
- AAPL’s closing price showed an overall upward trend over the year, with periodic fluctuations.
- Trading volume varied significantly, with notable spikes around major events.
- The average daily return was positive, reflecting overall growth.
- The standard deviation of returns indicated moderate price risk.
 
 
5. How to Run
 
1. Environment Setup: Ensure you have Python and Jupyter installed. Install required packages:bash
  
pip install pandas matplotlib
 
2. Open the Notebook: Launch Jupyter Notebook and open  ACC102_AAPL_Analysis.ipynb .
3. Prepare Data: Place the  HistoricalData_1776773023853.csv  file in the same directory as the notebook.
4. Run All Cells: Execute the notebook cells sequentially to see the results.
 
 
 
6. Product Link / Demo
 
- Demo Video:https://video.xjtlu.edu.cn/Mediasite/Play/f7304479198e4573848f2bec8c2095ff1d
 
 
7. Limitations & Next Steps
 
Limitations
 
- Only one year of data is analysed, which may not capture long-term trends.
- Visualizations are basic and do not include advanced technical indicators.
- No comparative analysis with market indices or peer stocks is included.
 
Next Steps
 
- Extend the dataset to cover multiple years.
- Add moving averages, volatility measures, and risk metrics.
- Compare AAPL’s performance with the S&P 500 index.
- Enhance visualizations with annotations and interactive elements.
