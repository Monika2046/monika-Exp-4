# monika-Exp-4
from pandas import read_csv
from matplotlib import pyplot
series=read_csv(r'C:\monika\monthly-car-sales.csv')
print(series.head())
series.plot()
pyplot.show()
![1](https://github.com/user-attachments/assets/f59cc662-be42-4d3d-a1f3-ccab341b3fd0)
series.plot(style='-.')
pyplot.show()
![2](https://github.com/user-attachments/assets/48aa8a55-f0fd-4f67-b727-ace502b87e78)
series.plot(kind='kde')
pyplot.show()
![3](https://github.com/user-attachments/assets/d27fb93c-e487-4182-ac40-80aea9172c9c)
series.hist()
pyplot.show()
![4](https://github.com/user-attachments/assets/e680de9e-fd1e-411b-b1aa-858a458c09ae)
