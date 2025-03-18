# iris-classification-hyperparameter-tuning

IN CASE YOU WANT TO IMPORT IN PYTHON DIRECTLY
pip install ucimlrepo

Import the dataset into your code 
from ucimlrepo import fetch_ucirepo 
  
#fetch dataset 
iris = fetch_ucirepo(id=53) 
  
#data (as pandas dataframes) 
X = iris.data.features 
y = iris.data.targets 
  
#metadata 
print(iris.metadata) 
  
#variable information 
print(iris.variables) 
