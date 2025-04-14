# 📈 Stock Trading Strategy Analysis
## 📌 Project Overview
This project analyzes the performance of stock trading strategies across different countries and position types (long/short). Key metrics such as Hit Ratio, Expectancy, and Average Win/Loss Ratio are used to evaluate the effectiveness of each strategy.
## 📊 Data Description

The dataset includes information on trading positions (long and short), performance outcomes across various countries, and key evaluation metrics such as:

- **Average Win Ratio**: Average return when a trade is successful  
- **Average Loss Ratio**: Average loss when a trade fails  
- **Hit Ratio**: Success rate of trades  
- **Expectancy**: Expected return based on win/loss and probability
## ✅ Key Findings & Insights

- Over 65% of all trading positions are **long**, but the **Hit Ratio is relatively low at 47%**, indicating a need for strategy optimization.
- **Canada** shows the highest stability in performance with a **70% Hit Ratio** and high Expectancy, making it a promising market.
- **Correlation Analysis**:
  - 📈 **Average Win Ratio** has a **positive correlation** with Expectancy
  - 📉 **Average Loss Ratio** has a **negative correlation** with Expectancy
  - 🔁 **Hit Ratio** shows a **weak positive correlation** with Expectancy (around 0.3)
## 🧰 Technologies Used
- **Microsoft Excel**: For initial data cleaning, filtering, and table summarization
- **Python**: Data manipulation and analysis with pandas and numpy  
- **Visualization**: seaborn, matplotlib  
## 📌 Conclusion

- The high proportion of long positions combined with a low Hit Ratio suggests the need for strategy refinement.
- The Canadian market stands out with strong performance stability and high Expectancy.
- Improving Expectancy should focus on increasing the Average Win Ratio and minimizing the Average Loss Ratio.
