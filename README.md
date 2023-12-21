# Spark ETL Project
1. The project is done on Adult income dataset from UC Irvine Machine Learning Repository. The data is kind of "Census Income dataset" (Predict whether income exceeds $50K/yr).
2. I tried here to extract data and perform data cleaning (for categorical variables I tried to understand whether a complete row is missing on a variable has an effect on any other variable. For example one of the field known as "workclass" has some weird string "?" for which "occupation" had also had werid string "?". So we can make out that occupation and workclass were linked with eachother).
3. After  data cleaning I created fact table (transactional kind) and dimension table.
4. Loaded the data into postgres-SQL.