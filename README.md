
# **Ad Spend and Voter Turnout Analysis**

This project explores the relationship between election ad spending and voter turnout across various states in India. The analysis is based on three datasets: **Advertisers Dataset**, **Locations Dataset**, and **Results Dataset**.

## **Project Overview**

The goal of this project is to understand if and how ad spending influences voter turnout. The project involves the following key steps:

1. **Data Preprocessing**:
   - Cleaned and merged datasets.
   - Converted relevant columns to appropriate data types.
   - Merged the data on common fields for comprehensive analysis.

2. **Exploratory Data Analysis (EDA)**:
   - **Total Ad Spend by State**: Analyzed the total ad spend in INR across different states.
     - [Total Ad Spend by State Plot](https://github.com/aarish22/ElectionAdSpendingAnalysis/blob/main/Plots/topadSpendbyState.png)
   - **Average Voter Turnout by State**: Examined the average voter turnout percentage across states.
     - [Average Voter Turnout by State Plot](https://github.com/aarish22/ElectionAdSpendingAnalysis/blob/main/Plots/avgvoterturnputbystate.png)
   - **Top 5 Parties by Ad Spend**: Identified the top 5 political parties based on their ad spend.
     - [Top 5 Parties by Ad Spend Plot](https://github.com/aarish22/ElectionAdSpendingAnalysis/blob/main/Plots/top%205%20parties%20by%20ad%20spend.png)
   - **Distribution of Ad Spend**: Analyzed the distribution of ad spend across constituencies.
     - [Ad Spend Distribution Plot](https://github.com/aarish22/ElectionAdSpendingAnalysis/blob/main/Plots/dist%20of%20ad%20spend.png)
   - **Ad Spend and Voter Turnout by Election Phase**: Examined ad spend and voter turnout across different election phases.
     - [Ad Spend and Voter Turnout by Phase Plot](https://github.com/aarish22/ElectionAdSpendingAnalysis/blob/main/Plots/ad%20spend%20and%20voter%20trun%20out%20by%20elction%20phase.png)

3. **Key Findings**:
   - Larger states like Uttar Pradesh, Maharashtra, and Odisha have the highest ad spend.
   - Smaller states and union territories often have higher voter turnout compared to larger states.
   - The correlation between ad spend and voter turnout is weak and slightly negative.
   - Ad spending varies significantly by phase, but higher spending does not consistently correlate with higher turnout.

4. **Conclusion**:
   - Higher ad spend does not necessarily translate to higher voter turnout.
   - Other factors likely play a significant role in voter engagement.

## **Usage**

To replicate the analysis:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ad-spend-voter-turnout-analysis.git
   cd ad-spend-voter-turnout-analysis
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis notebook:
   ```bash
   jupyter notebook ElectionAdSpendandvoterTurnoutAnalysis.ipynb
   ```
