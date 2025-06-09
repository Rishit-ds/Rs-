
import numpy as np
import matplotlib.pyplot as plt

# Heart shape using parametric equations
t = np.linspace(0, 2 * np.pi, 1000)
x = 16 * np.sin(t) ** 3
y = 13 * np.cos(t) - 5 * np.cos(2*t) - 2 * np.cos(3*t) - np.cos(4*t)

plt.figure(figsize=(8, 6))
plt.plot(x, y, color='red')
plt.fill(x, y, color='red', alpha=0.5)
plt.text(0, -1, 'I Love You ❤️', fontsize=20, ha='center', color='white', weight='bold')
plt.axis('off')
plt.title('Love in Python', fontsize=16)
plt.show()

