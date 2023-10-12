# quiz2_answer_key
# Quiz2
Name:
</br>
Uni:
</br>
Date:
</br>

1. Select the response that most closely explains what this command accomplishes: 
</br>

```python
import pandas as pd
```
</br>

1. Importing the pandas software and storing it in the variable pd
2. **Importing the pandas library and giving it the alias pd**
3. Importing the pandas variable and giving it the alias pd
4. Importing the pandas software and storing it in the alias pd

</br>

2. Select the response that most closely explains what this command accomplishes: 
</br>

```python
refugee_df = pd.read_csv('refugee-arrivals-by-destination.csv', delimiter=",", encoding='utf-8')
```
</br>

1. Using the read_csv variable to bring in the dataset, specifiying the delimiter and encoding, and storing the spreadsheet in the refugee_df function
2. Using the read_csv method to bring in the dataset, specifiying the delimiter and encoding, and storing the spreadsheet in the refugee_df variable
3. **Using the read_csv method to bring in the dataset, specifiying the delimiter and encoding, and storing the dataframe in the refugee_df variable**
4. Using the read_csv variable to bring in the dataset, specifiying the delimiter and encoding, and storing the dataframe in the refugee_df variable
</br>

3. Which of the following commands would return the top three rows in a dataframe? Select all that apply
</br>

1. **`refugee_df[0:3]`**
2. `refugee_df[0:4]`
3. `refugee_df[0:2]`
4. **`refugee_df.head(3)`**
</br>

4. For each of the following values, provide the standard Python datatype (if applicable) and the pandas datatype (int64, float64, object, datetime64)
</br>

1. `1`: integer, int64
2. `1.0`: float, float 64
3. `"1"`: string, object
4. `2023/10/5`: none, datatime64
</br>

5. True or False: If you want to select one column from a dataframe you need to use double brackets. But if you want to select two or more columns from a dataframe, you only need single brackets. 
</br>

1. True
2. **False**
</br>

6. True or False: The NLTK `concordance` method is case sensitive
</br>

1. True
2. **False**
</br>

7. Each of the following words denotes a step in the text data cleaning process. Add numbers 1 - 4 to mark which comes first, with 1 being the first step and four being the last:
</br>

1. lemmatize (4)
2. remove punctuation and numbers (1)
3. remove stop words (3)
4. make lower case (2)
</br>

8. Select the response that most closely explains what this command accomplishes: 
</br>

```python
len(set(text1_tokens))
```

</br>

1. the `len` function finds all of the unique values within the text1_tokens list, and the `set` function calculates and prints the number of unique values
2. ** the `set` function finds all of the unique values within the text1_tokens list, and the `len` function calculates and prints the number of unique values**
3. the `set` variable finds all of the unique values within the text1_tokens list, and the `len` variable calculates and prints the number of unique values
4. the `len` variable finds all of the unique values within the text1_tokens list, and the `set` variable calculates and prints the number of unique values
</br>

9. Explain what each line of the following code is accomplishing (4 points):
</br>

```python
text1_stops = [] #we create an empty list and store it in the variable text1_stops
for t in text1_tokens: # for every item t in text1_tokens:
    if t not in stops: # if t not in the stops variable
        text1_stops.append(t) #then add t to the text1_stops list
```

</br>
