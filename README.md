# Trader Behavior and Market Sentiment Analysis

### Project Overview

This project performs a comprehensive analysis of trader behavior on the Hyperliquid platform by correlating it with the Bitcoin Fear & Greed Index. The primary goal is to uncover actionable insights by examining how specific metrics change during different market sentiment periods (Fear vs. Greed).

The key areas of analysis include:
* **Trading Volume:** Comparing the total USD volume during fear vs. greed.
* **Profit & Loss (PnL):** Analyzing the average profitability of trades in different sentiments.
* **Trade Frequency & Size:** Investigating the total number of trades and their average dollar value.
* **BUY vs. SELL Behavior:** Examining how buying and selling pressure shifts with market mood.
* **Top Trader Analysis:** A deep dive into the strategies of the platform's top-performing traders to find patterns that set them apart from the average user.

---

### Project Structure

The repository follows the required submission format:

-   `ds_<candidate_name>/`
    -   `notebook_1.ipynb`: A Google Colab notebook containing all Python code for data cleaning, analysis, and visualization.
    -   `/csv_files/`: Contains all intermediate or processed CSV data files.
    -   `/outputs/`: Contains all visual outputs, such as charts and graphs.
    -   `ds_report.pdf`: A PDF report summarizing the key insights and findings from the analysis.
    -   `README.md`: This file, containing setup and project information.

---

### How to Run the Analysis

1.  **Open Notebook**: Open `notebook_1.ipynb` in Google Colab.
2.  **Upload Data**: Upload the two initial datasets (`historical_data.csv` and `fear_greed_index.csv`) to the Colab environment.
3.  **Execute Code**: Run all the cells in the notebook from top to bottom.
4.  **Check Outputs**: The script will automatically generate the processed CSV file in the `csv_files/` directory and all chart images in the `outputs/` directory.
