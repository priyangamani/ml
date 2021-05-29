# ml

Segmented univariate analysis

https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity

import pandas as pd
marks = pd.read_csv('https://query.data.world/s/HqjNNadqEnwSq1qnoV_JqyRJkc7o6O')

details = pd.DataFrame(marks)
print(details.isnull().sum())

import pandas as pd
customer = pd.read_csv('https://query.data.world/s/y9rxL9mGdP6AXPiDaIL4yYm6DsfTV2')


Removing extra characters from a column


customer['Cust_id'] = customer['Cust_id'].str.replace('Cust_', '')
print(customer.head(10))

Remove duplicates

import pandas as pd
rating = pd.read_csv('https://query.data.world/s/EX0EpmqwfA2UYGz1Xtd_zi4R0dQpog')

rating_update = rating.drop_duplicates()

print(rating.shape)
print(rating_update.shape)

https://data.gov.in/
