# crypto_investment_ml
This Jupyter notebook is machine learning clustering for crypto investment data


---

## Technologies

Project uses:

[Pandas](https://pandas.pydata.org/)

[pathlib](https://docs.python.org/3/library/pathlib.html)

[hvplot](https://hvplot.holoviz.org/)

[SKLearn](https://scikit-learn.org/stable/)




---

## Installation Guide

Run this program in Jupyter notebook and have hvplot, pandas, SKlearn and path installed



---

## Usage

Utilize Jupyter Labs to interact with the software program

!["Jupyter Labs Example"](https://miro.medium.com/max/955/1*mXGu0MeYgnUkyR9ybVlQpg.png)

**Key example code for elbow curve plot**
```
# Create a dictionary with the data to plot the Elbow curve
elbow_data = {
    "k": k,
    "inertia": inertia
}
# Create a DataFrame with the data to plot the Elbow curve
df_elbow_data = pd.DataFrame(elbow_data)
# Plot a line chart with all the inertia values computed with 
# the different values of k to visually identify the optimal value for k.
original_elbow_plot = df_elbow_data.hvplot.line(
    x="k", 
    y= "inertia", 
    title="Elbow Curve", 
    xticks=k
)

original_elbow_plot
```

---

## Contributors

Hugo Kostelni

---

## License

Open Source