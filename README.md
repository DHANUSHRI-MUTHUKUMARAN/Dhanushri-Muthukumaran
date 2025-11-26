# Sentiment Analysis of Bitcoin

This project explores how the Crypto Fear & Greed Index affects Bitcoin trading performance.  
By combining sentiment data with historical trading data, I calculated the average profit (PnL) and win rates for each market sentiment.

## Features
- Data cleaning and merging  
- Sentiment-wise profit comparison  
- Win rate visualization  
- Bar and pie charts for insights

## Tools Used
- Python  
- Pandas  
- Matplotlib
## Visualizations

## Average Profit by Sentiment
![Bar Chart](Images/Screenshot%202025-11-26%20at%201.29.19%20AM.png)

## Win Rate by Sentiment
![Pie Chart](Images/Screenshot%202025-11-26%20at%201.30.03%20AM.png)

## Data files are too large for GitHub.
They can be downloaded from:
- Historical Trades: <https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing>
- Fear & Greed Index: <https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing>

## Google Colab link 
<https://colab.research.google.com/drive/1NxwVMbF6duieG0T8wfSlCG7ihQgSVfG5?usp=sharing>
## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install dependencies:
   pip install pandas matplotlib
3. Run all cells.

## Conclusion:
The analysis shows that Bitcoin trades performed differently during various sentiment conditions. Extreme Greed had the highest profit potential, while Extreme Fear showed lower but more stable results. This suggests that sentiment indicators like the Fear & Greed Index can be useful in timing trades.
