<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#introduction">Introduction</a>
    </li>
    <li><a href="#Make some Data">Make some Data</a></li>
    <li><a href="#Create the Model and Cost Function (Total Loss)">Create the Model and Cost Function (Total Loss)</a></li>
    <li><a href="#Train the Model: Batch Gradient Descent">Train the Model: Batch Gradient Descent</a></li>
    <li><a href="#Train the Model: Stochastic Gradient Descent with Dataset DataLoader">Train the Model: Stochastic Gradient Descent with Dataset DataLoader</a></li>
    <li><a href="#Train the Model: Mini Batch Gradient Decent: Batch size equals 5">Train the Model: Mini Batch Gradient Decent: Batch size equals 5</a></li>
    <li><a href="#Train the Model: Mini Batch Gradient Decent: Batch size equals 10">Train the Model: Mini Batch Gradient Decent: Batch size equals 10</a></li>
    <li><a href="#examining-results">Examining results</a></li>
    <li><a href="#summary">Summary</a></li>

  </ol>
</details>

# Training Two Parameter Mini-Batch Gradient Decent¶

### Introduction
In this study, practice training how to use Mini-Batch Descent to train models in the PyTorch framework.




### Make some Data
aaaaaa
### Create the Model and Cost Function (Total Loss)

First of all, we simulate some data using datasets from sklearn.

```python
from utils_data import *

N = 2000
noise = 0.25
# load and visualize data
X, Y = load_data(N, noise)

# visualize the data
path_to_save_plot = os.path.join("input", "viz")
plot_data(X, Y, path_to_save_plot)
```

<p align="center">
  <a href="">
    <img src="/input/viz/viz.png" width="620" alt=""/>
  </a>
</p>



### Train the Model: Batch Gradient Descent
ddddđd
First of all, we simulate some data using datasets from sklearn.

```python
from utils_data import *

N = 2000
noise = 0.25
# load and visualize data
X, Y = load_data(N, noise)

# visualize the data
path_to_save_plot = os.path.join("input", "viz")
plot_data(X, Y, path_to_save_plot)
```

<p align="center">
  <a href="">
    <img src="/input/viz/viz.png" width="620" alt=""/>
  </a>
</p>

### Train the Model: Stochastic Gradient Descent with Dataset DataLoader




rrrr
### Train the Model: Mini Batch Gradient Decent: Batch size equals 5




hhhhh
### Train the Model: Mini Batch Gradient Decent: Batch size equals 10




mmmmm
### Examining-results
mmmm







### Summary

