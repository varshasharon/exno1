# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output
```
import pandas as pd
df=pd.read_csv("/content/SAMPLEIDS.csv")
df
```
![image](https://github.com/varshasharon/exno1/assets/98278161/792962ae-74e2-467f-b239-66d6a3b1fad6)

```
df.head(10)
```
![image](https://github.com/varshasharon/exno1/assets/98278161/459e1284-94c5-427b-aa17-10f452c34bd9)

```
df.tail(10)
```
![image](https://github.com/varshasharon/exno1/assets/98278161/f1921df1-c8a4-4aca-b547-dd0c8aae9ab6)



# Result
          <<include your Result here>>
