# Test1
a try edition for using github

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

#Series
data = pd.Series(np.random.randn(1000),index=np.arange(1000))
data = data.cumsum()

data.plot()
plt.show()
