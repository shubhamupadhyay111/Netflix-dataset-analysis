# Netflix Stock Dataset Analysis

## Objective  
This project analyzes Netflix stock data to explore:  

1. Volume of stock traded  
2. Netflix stock price trends (High, Open, and Close prices)  
3. Netflix stock price patterns by day, month, and year  
4. Top 5 dates with the highest stock price  
5. Top 5 dates with the lowest stock price  

## Getting Started  
To run this analysis, ensure you have the necessary Python libraries installed:  

```bash
pip install pandas matplotlib seaborn
```

## Dataset  
The analysis is based on Netflix's historical stock data. The dataset is loaded as follows:  

```python
import pandas as pd
df = pd.read_csv("Netflix stock dataset.csv")
df.head()
```

## Key Steps in Analysis  
- Data preprocessing and conversion of dates  
- Visualizing stock price trends  
- Identifying patterns in trading volume  
- Extracting highest and lowest stock price dates  

## Sample Code  
```python
import seaborn as sns
sns.set(rc={'figure.figsize': (10,5)})
df['Date'] = pd.to_datetime(df['Date'])
```

## Results  
The analysis provides insights into stock trends, trading volumes, and significant price movements.  

---
Would you like to include more details, such as visualizations or findings?

