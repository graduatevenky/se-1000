import matplotlib.pyplot as plt
import numpy as np

# Get user input for the coefficients
pressure = int(input("Enter the value of pressure: "))
windspeed = int(input("Enter the value of windspeed: "))
humidity = int(input("Enter the value of humidity: "))

# Generate x values
x = np.linspace(-10, 10, 400)

# Calculate y values for the first function
y1 = pressure*x**2 + windspeed*x + humidity

# Plot the first function
plt.plot(x, y1, label=f'UserInput:4{pressure}x^2 + {windspeed}x + {humidity}')

# Hard-coded coefficients for the second function
pressure = 1
windspeed = -3
humidity = 2

# Calculate y values for the second function
y2 = pressure*x**2 + windspeed*x + humidity

# Plot the second function
plt.plot(x, y2, label=f'HardCoded:{pressure}x^2 + {windspeed}x + {humidity}')

# Add title, labels, legend, and grid
plt.title('Plot of the quadratic functions')
plt.xlabel('x')
plt.ylabel('y')
plt.legend()
plt.grid(True)

# Display the plot
plt.show()
