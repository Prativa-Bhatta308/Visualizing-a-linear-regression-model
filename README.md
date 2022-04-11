# Visualizing-a-linear-regression-model

#Instructions

Import matplotlib.pyplot as plt.
Create a scatter plot visualizing y against X, with observations in blue.
Draw a red line plot displaying the predictions against X.
Display the plot.

# Import matplotlib.pyplot
import matplotlib.pyplot as plt

# Create scatter plot
plt.scatter(X, y, color="blue")

# Create line plot
plt.plot(X, predictions, color="red")
plt.xlabel("Radio Expenditure ($)")
plt.ylabel("Sales ($)")

# Display the plot
plt.show()

![image](https://user-images.githubusercontent.com/89304772/162654047-ac38c53f-f1f3-4cdd-bfee-4ab5e9e48073.png)
