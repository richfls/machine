from scipy.stats import binom
import matplotlib.pyplot as plt

n = 6 #number of trials
p = 0.37 #propability

values = list(range(n + 1))
print("Valuse are:", values)

dist = [binom.pmf(r, n, p) for r in values]
print("binomial distribution is:", dist)

plt.bar(values, dist)
plt.show()
