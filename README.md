# Trade Analysis and Account Ranking

## Overview
This Jupyter Notebook analyzes trading data and ranks trading accounts based on key performance metrics. The output includes ranked accounts saved as a CSV file and visualized using bar charts.

---

## Features
- **Performance Metrics**:
  - Profit and Loss (PnL)
  - Return on Investment (ROI)
  - Sharpe Ratio
  - Maximum Drawdown (MDD)
  - Win Rate and Total Positions
  
- **Account Ranking**:
  - Weighted scoring system for ranking accounts using calculated metrics.
  
- **Visualization**:
  - Bar chart for top 20 performing accounts.

---

## Requirements
- Python 3.x
- Libraries:
  - pandas
  - numpy
  - ast
  - matplotlib
  - seaborn
- Jupyter Notebook

---

## How to Use
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/trade-analysis.git
   cd trade-analysis
   ```

2. **Install Dependencies**:
   Use the following command to install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. **Open the Notebook**:
   Launch the notebook in Jupyter:
   ```bash
   jupyter notebook trade-analysis-and-account-ranking.ipynb
   ```

4. **Run the Notebook**:
   - Update the file path for the trading data CSV file in the notebook.
   - Execute the cells sequentially.

5. **View Output**:
   - Ranked accounts are saved in `final_account_ranking.csv`.
   - Visualizations of top accounts are displayed in the notebook.

---

## File Structure
- `trade-analysis-and-account-ranking.ipynb`: Main notebook for analysis and visualization.
- `final_account_ranking.csv`: Output file with ranked accounts.
- `README.md`: Documentation.

---

## Example Outputs
1. **CSV File**:
   - Contains ranking metrics like ROI, Sharpe Ratio, Win Rate, and Drawdown for all accounts.
   
2. **Visualizations**:
   - Bar chart for the top 20 accounts ranked by performance.

---

## Kaggle Notebook
This analysis is also available on Kaggle:  
[Trade Analysis and Account Ranking](https://www.kaggle.com/code/drakshithkodithyala/trade-analysis-and-account-ranking)

---

## Contributing
Contributions are welcome! Fork this repository, make your changes, and submit a pull request.

---

## License
This project is licensed under the MIT License. See `LICENSE` for details.
