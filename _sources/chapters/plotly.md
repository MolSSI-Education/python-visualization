Interactive Plots using Plotly
==============================

You have seen in the previous lessons that we can make `matplotlib` plots somewhat interactive in the jupyter notebook by using the `%matplotlib notebook` magic command. Matplotlib has other, more complex ways to make figures interactive that you can read about [here](https://matplotlib.org/stable/users/interactive.html). 

However, there are other python libraries which are designed specifically to create interactive figures. This section covers creating interactive plots using the plotting library [plotly](https://plotly.com/python/). Plotly has a python API, but is also available in several other languages. There are two ways you can use plotly - through `plotly express` or through `plotly graph objects`. `Plotly Express` is the newer, more-user-friendly interface which has been made to simply commonly made plots. The second option - using `plotly graph objects` allows for much more control over your figures (and more types of figures). We will start this section by using `plotly express` to make some figures. Then, we will discuss `plotly graph objects`.

Before getting started, make sure you have plotly installed

```
pip install plotly
```