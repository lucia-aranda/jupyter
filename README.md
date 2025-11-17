<div align="center">
  <br>
  <img alt="jn" src="img/jupyter_notebook.png" width="150px">
  <h1>💻 Data Analysis 💻</h1>
  <strong>School project about csv <a href="https://github.com/lucia-aranda/jupyter/tree/main/ipynb">data analysis</a> using pandas, matplotlib, numpy, seaborn, scipy and piplite libraries.</strong>
</div>

## Summary

| #   | Section                                                                                                                              |
| --- | ---------------------------------------------------------------------------------------------------------------|
| 🚗   | [Car notebook](https://github.com/lucia-aranda/jupyter/blob/main/ipynb/CAR_ANALYSIS.ipynb) + [CSV data file](https://github.com/lucia-aranda/jupyter/blob/main/csv/auto.csv)  |
| 🏀   | [NBA notebook no.1](https://github.com/lucia-aranda/jupyter/blob/main/ipynb/NBA_P1_ANALYSIS.ipynb) + [NBA notebook no.2](https://github.com/lucia-aranda/jupyter/blob/main/ipynb/NBA_P2_ANALYSIS.ipynb) + [CSV data file](https://lucia-aranda.github.io/javascript/)  |
| 📋   | [Reports](https://github.com/lucia-aranda/jupyter/tree/main/pdf)  |

## Prerequisites

To run the project locally, you need a development environment installed on your machine:

- `Python 3.12.x or upper`

- `Jupyter Notebook`

And internet conection 🌐 to propertly load libraries.

## Installation

To run Jupyter Notebook in your personal computer, download <a src="https://www.python.org/">python</a> and run the installer:

- `Add Python to PATH [!important]`

Next, open the command prompt (Windows + R, then type 'cmd') and copy paste:

```
python --version
```

Once you confirm the required version is installed in your computer, install jupyter with:

```
pip install notebook
```

Finally, open the application with the sentence:

```
jupyter notebook
```

Create a new folder, add the files (csv and ipynb) in the same folder and you can now run each line of code from the top to the bottom.

## Concept

This is a responsive javascript portfolio using mathematical exercises with recursivity, arrays, selection, including while, do while, and for loops. Showcases fundamental programming logic and control flow structures with practical, executable examples. 🧮

It combines JavaScript animations, CSS styling, Bootstrap and modern front-end techniques to create an engaging user experience. The project features interactive hover effects, and minimalist design that enhance visual simplicity. With clean code structure, the project demonstrates both technical skills like JavaScript DOM manipulation, alongside strong design sensibility through responsive layouts and user-friendly navigation. 👩‍💻

Whether you're a developer interested in seeing clean implementations of fundamental programming patterns, or someone curious about how code can tackle mathematical puzzles, this portfolio offers hands-on examples that are both educational and engaging. Each exercise is designed to make complex computational logic accessible and visual. 📔 problem solved,  how can i use it, how can i apply it, why it exists

## Use case

This small code example from Car Notebook, creates a box graph (boxplot) showing quantitative data according to categories, taking by reference body-style in 'x' and price in 'y'. 
In other words, the relation between cars' body-type and their price.

```
sns.boxplot(x='body-style', y='price', data=df)
```

<img src="img/car_graph.png" width="300px">
<br>

This other code example from NBA Notebook, creates a line graph with data obtained from df_line_final, set the title and assign 'y' and 'x' axis label.
The graph basically show NBA strikes per year.

```
df_line_final.plot(kind='line')
plt.title('Evolución de tiros de NBA')
plt.ylabel('Número de tiros')
plt.xlabel('Year')
plt.show()
```

<img src="img/nba_graph.png" width="300px">

## Contributing

Feel free to DM me 💬 if you have any question(s)/need help/concern(s) about :)
