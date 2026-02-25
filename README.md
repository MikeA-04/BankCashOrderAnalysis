# Bank Cash Order Analysis: $100 Bill Trends (2023–2026)
The bank wants to understand demand for $100 bills over the past three years to optimize cash supply, reduce unnecessary storage, and improve branch-level forecasting. This analysis identifies patterns in cash orders across seasonal trends and anomalies in demand.

## Data Pipeline
1. Raw cash order data uploaded to Azure Blob Storage
2. Stored in Azure SQL Database for structured querying
3. Analyzed using Python (pandas) for data cleaning and aggregations
4. Visualized in Power BI for executive dashboards and insights

## Dataset Description
Data source: Internal bank cash order logs
Time range: 2023-2026
Columns:
- Date of order
- Cash a the beginning of the day
- Total cash that went out
- Total cash that went in
- Cash at the end of the day
- Amount of $100s that went into the vault
- Amount of $100s that went out of the vault
- Cash went out of ATM (denomination: $20)

Dataset contains ~750 rows

## SQL Analysis Examples

## Data Cleaning (Python)

## Key Insights

## Dashboard

## Business Recommendations

## Future Improvements

## Tools and Technologies
| Category        | Tool                                 |
| --------------- | ------------------------------------ |
| Cloud Storage   | Azure Blob Storage                   |
| Database        | Azure SQL Database                   |
| Data Analysis   | Python (pandas, matplotlib, seaborn) |
| Visualization   | Power BI                             |
| IDE             | VS Code                              |
| Version Control | Git + GitHub                         |

## Folder Structure
```
bank-100-bill-analysis/  
│  
├── data/  
│   ├── raw/          # raw dataset (sample)  
│   └── processed/    # cleaned and aggregated data  
├── notebooks/        # Jupyter notebooks  
├── sql/              # SQL scripts  
├── dashboard/        # Screenshots  
├── images/           # Architecture diagram, charts  
├── .gitignore  
├── LICENSE  
└── README.md
```
