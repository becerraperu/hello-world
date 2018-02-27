# hello-world

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline

df = pd.read_csv('basket.csv')
df.head()
df.info()

# This data set contains statistics for 22,083 basketball players.

plt.scatter(x=df['GP'], y=df['points'])
plt.xlabel('Games played')
plt.ylabel('points')
plt.title('Games played / points')
plt.show()

# This scatter plot show games played vs points.
