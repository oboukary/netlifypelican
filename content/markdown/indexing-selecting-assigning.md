title: Analyse de donnée dans python avec pandas
date: 2020-02-29 12:00
category: Manipulation de donnée
tags: pandas, python, data science
slug: pandas-data-science
authors: Boukary Ouedraogo
summary: Pandas la librairie python pour la manipulation de donnée

## La bibliothèque pandas 


```python
import pandas as pd
import random
data = pd.read_csv('employees.csv')
```


```python
data.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>First Name</th>
      <th>Gender</th>
      <th>Start Date</th>
      <th>Last Login Time</th>
      <th>Salary</th>
      <th>Bonus %</th>
      <th>Senior Management</th>
      <th>Team</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Douglas</td>
      <td>Male</td>
      <td>8/6/1993</td>
      <td>12:42 PM</td>
      <td>97308</td>
      <td>6.945</td>
      <td>True</td>
      <td>Marketing</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Thomas</td>
      <td>Male</td>
      <td>3/31/1996</td>
      <td>6:53 AM</td>
      <td>61933</td>
      <td>4.170</td>
      <td>True</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Maria</td>
      <td>Female</td>
      <td>4/23/1993</td>
      <td>11:17 AM</td>
      <td>130590</td>
      <td>11.858</td>
      <td>False</td>
      <td>Finance</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Jerry</td>
      <td>Male</td>
      <td>3/4/2005</td>
      <td>1:00 PM</td>
      <td>138705</td>
      <td>9.340</td>
      <td>True</td>
      <td>Finance</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Larry</td>
      <td>Male</td>
      <td>1/24/1998</td>
      <td>4:47 PM</td>
      <td>101004</td>
      <td>1.389</td>
      <td>True</td>
      <td>Client Services</td>
    </tr>
  </tbody>
</table>
</div>




```python
test=data.columns
```


```python
test
```




    Index(['First Name', 'Gender', 'Start Date', 'Last Login Time', 'Salary',
           'Bonus %', 'Senior Management', 'Team'],
          dtype='object')




```python

```
