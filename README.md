# Common Functions

### Useful `pandas` functions
`df` is the variable name for your `pandas` DataFrame. Change this to the variable name you're using if not `df`
- `df.head()`: Show the top 5 rows of your DataFrame. To display `N` rows: `df.head(N)`
- `df.info()`: See information about the data.
- `df.describe()`: See basic data statistics.
---
### Plots in `pandas`
`import pandas as pd`
- **Histogram:** `df.hist()`
- **Boxplot:** `df.boxplot`
- **Scatter Matrix:** `pd.plotting.scatter_matrix(df)`
---
### Plotting in `matplotlib`
`import matplotlib.pyplot as plt`
>Simple plot
```
plt.figure()
plt.scatter(x, y)
plt.xlabel('x-axis label')
plt.ylabel('y-axis label')
plt.title('Plot Title')
plt.show()
```

>Multiple curves in a single plot
```
plt.figure()
plt.scatter(x, y1, label='Curve 1')
plt.scatter(x, y2, label='Curve 2')
plt.xlabel('x-axis label')
plt.ylabel('y-axis label')
plt.title('Plot Title')
plt.legend()
plt.show()
```
---
### Useful Links
- Python Packages
    - [`pandas`](https://pandas.pydata.org/docs/user_guide/10min.html)
    - [`matplotlib`](https://matplotlib.org/stable/users/explain/quick_start.html#quick-start)
    - [`numpy`](https://numpy.org/devdocs/user/quickstart.html)
- Learning
    - [Intro to Programming](https://www.kaggle.com/learn/intro-to-programming)
    - [Python](https://www.kaggle.com/learn/python)
    - [Intro to SQL](https://www.kaggle.com/learn/intro-to-sql)
    - [Advanced SQL](https://www.kaggle.com/learn/advanced-sql)
    - [Python Standard Library](https://docs.python.org/3/library/index.html)
