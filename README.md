# Python
Python Projects
import pandas
leaves = pandas.read_csv(r'C:/Users/Generation UK&I\Documents/VIEW.csv')
print(leaves)

from matplotlib import pyplot as plt
plt.barh(leaves.Titles, leaves.avg_sickleaves)

plt.ylabel('Job Titles')
plt.xlabel('AVG Sick Leaves')
plt.title('Employees Avg Sick Leaves')

plt.show()

![Bar Graph](https://user-images.githubusercontent.com/113436622/192867218-a86fc699-00ee-4b59-8da3-8a1fa4be650f.png)
