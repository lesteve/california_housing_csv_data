### Temporary work-around repo

Until https://github.com/scikit-learn/scikit-learn/issues/32961 is fixed and
`sklearn.datasets.fetch_california_housing` works again, you can download the
California Housing data like this:
```py
import pandas as pd

data = pd.read_csv('https://github.com/lesteve/california_housing_csv_data/raw/refs/heads/main/california_housing_data.csv')
target = pd.read_csv('https://github.com/lesteve/california_housing_csv_data/raw/refs/heads/main/california_housing_target.csv')
```
