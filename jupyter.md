## Graph of \( T(t) = \sin(t) \)

We define the function:

$$
T(t) = \sin(t)
$$

### Python code to plot the function
```python
import numpy as np
import matplotlib.pyplot as plt

t = np.linspace(-2*np.pi, 2*np.pi, 400)
T = np.sin(t)

plt.plot(t, T)
plt.xlabel("t")
plt.ylabel("T(t)")
plt.title("Graph of T(t) = sin(t)")
plt.grid(True)
plt.show()
