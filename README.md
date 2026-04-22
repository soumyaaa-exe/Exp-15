AIM: To study different data normalization techniques and encoding methods in Pandas and Scikit-learn for converting categorical data into numerical form.
THEORY :
pd.DataFrame(): Creates a structured tabular dataset from dictionary data.

print(): Displays output on the console.

df['col'].min(): Returns the minimum value in a column.

df['col'].max(): Returns the maximum value in a column.

Min-Max Normalization: Scales values between 0 and 1 using (x - min)/(max - min).

df[cols]: Selects multiple columns from a DataFrame.

df.mean(): Calculates average value of a column.

df.std(): Calculates standard deviation of a column.

Z-Score Normalization: Standardizes data using (x - mean)/standard deviation.

Decimal Scaling: Normalizes data by dividing values with a power of 10.

display(): Shows DataFrame in tabular format in Jupyter/Colab.

pd.read_csv(): Loads dataset from a CSV file into a DataFrame.

LabelEncoder(): Converts categorical labels into numeric form.

fit_transform(): Fits encoder and transforms categorical values into numbers.

pd.get_dummies(): Converts categorical variables into one-hot encoded columns.

get_dummies(columns=): Applies encoding to specific columns.

drop_first=True: Drops one dummy column to avoid multicollinearity.

Multiple column encoding: Allows encoding of several categorical columns simultaneously.

Normalization on multiple columns: Applies scaling operations on selected columns together.

Categorical to numerical conversion: Required for machine learning models to process non-numeric data.
CONCLUSION : In this experiment, we studied different normalization techniques such as Min-Max, Z-score, and Decimal Scaling to scale numerical data. We also learned how to convert categorical data into numerical form using Label Encoding and One-Hot Encoding. These techniques help improve model performance and data consistency. Overall, normalization and encoding are essential steps in data preprocessing.
