# hello-world
# Step 1: Import Pandas
import pandas as pd

# Step 2: Load the dataset

url = "[https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv](https://open.data.gov.sa/ar/datasets/view/7b3282ec-d7ae-4b41-882b-ec5512ceaadd)"


df = pd.read_csv(url)

# Step 3: Display the dataset shape (rows, columns)
print("Dataset Shape (rows, columns):")
print(df.shape)

# Step 4: Preview the first few rows
print("\nFirst 5 rows of the dataset:")
print(df.head())

# Step 5: Check column names
print("\nColumn Names:")
print(df.columns)

# Step 6: Check data types and missing values
print("\nDataset Information:")
print(df.info())
