# assignment-2-march
Q1: What is Matplotlib? Why is it used? Name five plots that can be plotted using the Pyplot module of
Matplotlib.
Q2: What is a scatter plot? Use the following code to generate data for x and y. Using this generated data
plot a scatter plot.
import numpy as np
np.random.seed(3)
x = 3 + np.random.normal(0, 2, 50)
y = 3 + np.random.normal(0, 2, len(x))
Note: Also add title, xlabel, and ylabel to the plot.
Q3: Why is the subplot() function used? Draw four line plots using the subplot() function.
Use the following data:
import numpy as np
For line 1: x = np.array([0, 1, 2, 3, 4, 5]) and y = np.array([0, 100, 200, 300, 400, 500])
For line 2: x = np.array([0, 1, 2, 3, 4, 5]) and y = np.array([50, 20, 40, 20, 60, 70])
For line 3: x = np.array([0, 1, 2, 3, 4, 5]) and y = np.array([10, 20, 30, 40, 50, 60])
For line 4: x = np.array([0, 1, 2, 3, 4, 5]) and y = np.array([200, 350, 250, 550, 450, 150])
Q4: What is a bar plot? Why is it used? Using the following data plot a bar plot and a horizontal bar plot.
import numpy as np
company = np.array(["Apple", "Microsoft", "Google", "AMD"])
profit = np.array([3000, 8000, 1000, 10000])
Q5: What is a box plot? Why is it used? Using the following data plot a box plot.
box1 = np.random.normal(100, 10, 200)
box2 = np.random.normal(90, 20, 200)
