# banking-dataset-analysis
Python analysis of banking term deposit marketing data
# Banking Dataset Analysis

A comprehensive Python analysis of a Portuguese banking institution's term deposit marketing campaign data.

## 📊 Project Overview

This project analyzes direct marketing campaigns (phone calls) to predict whether clients will subscribe to term deposits. The analysis covers 45,211 clients with 18 different attributes.

## 🎯 Objective

Predict if a client will subscribe to a term deposit and identify key factors that influence subscription decisions.

## 📋 Dataset Description

- **Size**: 45,211 rows × 18 columns
- **Period**: May 2008 to November 2010
- **Source**: Portuguese banking institution marketing campaigns

### Key Variables:
- **Demographics**: Age, job, marital status, education
- **Financial**: Balance, housing loan, personal loan, credit default
- **Campaign**: Contact type, duration, number of contacts
- **Target**: Term deposit subscription (yes/no)

## 🔍 Analysis Questions Answered

1. What is the distribution of age among clients?
2. How does job type vary among clients?
3. What is the marital status distribution?
4. What is the level of education among clients?
5. What proportion of clients have credit in default?
6. What is the distribution of average yearly balance?
7. How many clients have housing/personal loans?
8. What communication types were used?
9. Contact timing patterns (day, month)
10. Campaign effort analysis (contacts, duration)
11. Previous campaign outcomes
12. Term deposit subscription rates
13. Correlations between attributes and subscription likelihood

## 🛠️ Tools & Libraries Used

- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **matplotlib** - Basic plotting and visualization
- **seaborn** - Statistical data visualization
- **numpy** - Numerical computations

## 🚀 How to Run

Option 1: Local Environment
bash
# Install required libraries
pip install pandas matplotlib seaborn numpy

# Run the script
python banking_analysis.py


Option 2: Google Colab
1. Open [Google Colab](https://colab.research.google.com)
2. Upload the `banking_analysis.py` script
3. Run the script - it will prompt you to upload the CSV file
4. View results inline

📈 Key Insights

The analysis provides insights into:
- **Customer Demographics**: Age, job, and education patterns
- **Financial Behavior**: Balance distributions and loan patterns
- **Campaign Effectiveness**: Success rates by contact method and timing
- **Predictive Factors**: Variables most correlated with subscription success

📁 Project Structure


banking-dataset-analysis/
│
├── banking_analysis.py          # Main analysis script
├── Banking_data.csv            # Dataset file
└── README.md                   # Project documentation


📊 Sample Outputs

The script generates:
- **Statistical summaries** for all variables
- **Distribution plots** (histograms, bar charts, box plots)
- **Correlation heatmap** showing variable relationships
- **Success rate analysis** by different customer segments

Contributing

Feel free to fork this project and submit pull requests for improvements!

License

This project is open source and available under the MIT License.

Contact

Aarna Tejwani 
Project Link: https://github.com/yourusername/banking-dataset-analysis
