# Enterprise Data Reconciliation & Analysis 📊

## 👋 About This Project

Hi! Welcome to my project.

The main purpose of this project is to compare and match data from different sources to make sure the information is accurate and consistent.

In many businesses, information is stored in different places. Sometimes records don't match, some details are missing, or there may be incorrect entries. This project focuses on solving these problems by bringing the data together, checking it, and preparing it for analysis.

I worked on this project to understand how data from different sources can be combined and checked to get more reliable results.

## 🎯 What Does This Project Do?

In simple words, this project:

- Checks customer information and identifies active customers.
- Reads transaction details from server logs.
- Removes records that contain errors.
- Handles missing currency exchange rates.
- Compares and matches information from different sources.
- Calculates the final revenue in USD.
- Finds monthly revenue and the top 5 customers.

## 🛠️ Tools I Used

- **Python:** To work with and process the data.
- **SQL:** To find and check customer information.
- **Pandas:** To clean and combine different datasets.
- **Regular Expressions:** To find transaction details in server logs.
- **Matplotlib:** To create simple charts.
- **Jupyter Notebook:** To write my code and explain each step.

## 🔄 How I Worked on the Project

I divided the work into simple steps:

1. **Checking customer data:** I checked customer records and selected customers with the latest Active status.
2. **Reading transaction data:** I collected useful transaction details and removed error records.
3. **Handling missing information:** I filled missing exchange rates using the previous available rate.
4. **Matching the data:** I connected customer, transaction, and exchange-rate information.
5. **Checking the results:** I calculated revenue in USD and prepared the final results.
6. **Understanding the data:** I looked at monthly revenue and identified the top five customers.

All the steps are explained clearly in the Jupyter Notebook, including the code and results.

## 📈 Key Results

Here are some important results from my project:

| Details | Results |
|---|---:|
| Total server log records | 100,000 |
| Valid transactions found | 94,902 |
| Active customers identified | 14,183 |
| Missing exchange rates handled | 104 |
| Final matched transactions | 53,899 |
| Total calculated revenue | $148,274,622.91 |

## 📁 Project Structure

```text
enterprise-data-reconciliation/
│
├── README.md
│
├── Enterprise_Data_Reconciliation.ipynb
│
├── final_reconciled_transactions.xls
│
├── monthly_usd_revenue.xls
│
└── top_5_customers.xls
```

## ▶️ How to View This Project

1. Download or clone this repository.
2. Open the Jupyter Notebook file.
3. Read the questions and explanations.
4. Run the code cells in order if you have the original input datasets.
5. Open the Excel files to see the final results.

**Note:** The original server logs, customer database, and exchange-rate file are not included in this repository. They are needed to run the complete project again. The uploaded files contain the notebook and final results.

## 💡 What I Learned

While working on this project, I learned how important it is to check data before using it.

I got practical experience in cleaning information, finding missing values, comparing records from different sources, and making sure the final data is consistent.

My goal was to create a simple solution that makes data easier to understand, compare, and trust.

## 🙌 Final Words

This project was a great learning experience for me. It helped me understand how data from different sources can be brought together to solve a real-world problem.

I'm still learning and improving my skills, and I look forward to working on more projects like this.

Thanks for visiting my project! 😊
