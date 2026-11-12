# TSAF-Ex-1-Plot-a-Time-Series-Data

## AIM:
To develop a Python program to plot and visualize time series data such as population,
commodity market price, or temperature.

## ALGORITHM:
1. Start the program.
2. Import Pandas and Matplotlib libraries.
3. Create the time-series data using Year or Month and its corresponding values.
4. Create a DataFrame using the time and value data.
5. Display the DataFrame.
6. Plot the time-series data using a line graph.
7. Add a suitable title and labels for the X-axis and Y-axis.
8. Display the graph.
9. Observe the graph and identify the trend as increasing, decreasing, approximately
constant, or seasonal.
10. Stop the program.

## PROGRAM:

###  Monthly Temperature — 12 Months
```
import pandas as pd
import matplotlib.pyplot as plt
month = ["Jan", "Feb", "Mar", "Apr", "May", "Jun",
"Jul", "Aug", "Sep", "Oct", "Nov", "Dec"]
temperature = [25, 27, 30, 33, 35, 34, 32, 31, 30, 29, 27, 25]
data = pd.DataFrame({
"Month": month,
"Temperature": temperature
})
print(data)
plt.plot(data["Month"], data["Temperature"])
plt.title("Monthly Temperature")
plt.xlabel("Month")
plt.ylabel("Temperature (°C)")
plt.show()

```

## OUTPUT:
<img width="678" height="717" alt="image" src="https://github.com/user-attachments/assets/47ff43a8-06ff-4605-beab-a04f7084cba4" />


## RESULT:
Thus, the given time-series data were successfully stored using Pandas and visualized using
Matplotlib. The trends in population, temperature, and commodity price were identified from
the plotted graphs
