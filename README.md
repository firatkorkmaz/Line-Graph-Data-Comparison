# Data Comparison Graph
A simple Jupyter Notebook program to plot line graphs for data comparison. 

## Setup & Run
* Open the **Line_Graph_Data_Comparison.ipynb** file with Jupyter Notebook:
```
pip install jupyter
```
```
jupyter notebook
```
* Assign your own data to the defined list type variables SAMP1 & SAMP2 and remove or comment out the following code lines of the for loop which assigns random integers to the lists:
```
for i in range(1, 101):
    SAMP1.append(random.randint(1, 100) / (i * 10))
    SAMP2.append(abs(100 - random.randint(1, 100)) / (i * 10))
```
