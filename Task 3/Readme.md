### Task 3: Exploratory Data Analysis - Retail

By: Amitkumar Rautray


### Exploratory Data Analysis
<ol> <li>Exploratory Data Analysis – EDA – plays a critical role in understanding the what, why, and how of the problem statement.</li>
<li>It’s first in the order of operations that a data analyst will perform when handed a new data source and problem statement.</li> 
</ol>

![EDA.png](https://blog.camelot-group.com/wp-content/uploads/2019/03/Picture2.png)


### Autoplotter- Open Source Python Library For GUI Based EDA

<ol> 
<li>Autoplotter is just like a dashboard in which you can load any dataset and start Exploratory Data Analysis</li>
<li>It supports different types of visualizations, statistical analysis of data, plotting according to your selected features, and creates all the major plots.</li>
</ol> 


![Autoplotter.png](https://i.ytimg.com/vi/r5uGJcp6ru0/maxresdefault.jpg)

### Implementation
Like any other python library, we will install Autoplotter using pip install autoplotter.

<ol> <li>Importing Autoplotter


```
from autoplotter import run_app 
import pandas as pd
```
</li> 

<li>Loading the Dataset


```
df = pd.read_csv(‘sample.csv’)
```
</li> 


<li>Loading the Autoplotter


```
run_app(df)
```
</li> 

</ol>
