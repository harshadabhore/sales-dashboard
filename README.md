# sales-dashboard

1.First import the data

import pandas as pd

Load Excel file

df = pd.read_excel("Products_Sales_Data.xlsx")  # replace with your file name

2.Remove duplicate rows

df_clean = df.drop_duplicates()

print(df_clean)

3. Convert date formats to a consistent type (e.g., dd-mm-yyyy).

4. df['Date'] = df['Date'].dt.strftime('%d-%m-%Y')
