# Machine Learning Cheat-Sheet

## `scikit-learn` Navigator

```python
# Transformer/Funktionen zur Vorverarbeitung
from sklearn.impute import SimpleImputer
from sklearn.preprocessing import LabelEncoder
from sklearn.model_selection import train_test_split

# Estimators für das Clustering
from sklearn.cluster import AgglomerativeClustering
from sklearn.cluster import KMeans

# Estimators für die Klassifikation
from sklearn.tree import DecisionTreeClassifier, plot_tree
from sklearn.neighbors import KNeighborsClassifier

# Klassifikationsmetriken
from sklearn.metrics import f1_score
from sklearn.metrics import confusion_matrix
from sklearn.metrics import accuracy_score
from sklearn.metrics import recall_score
from sklearn.metrics import precision_score
from sklearn.metrics import classification_report

# Estimators für die Regression
from sklearn.tree import DecisionTreeRegressor
from sklearn.linear_model import LinearRegression

# Metriken für die Regression
from sklearn.metrics import r2_score
from sklearn.metrics import mean_squared_error
from sklearn.metrics import mean_absolute_error
from sklearn.metrics import root_mean_squared_error
```

## `scipy` Navigator

```python
from scipy.cluster import hierarchy
```