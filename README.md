# simplecsv

Easily manipulate csv files using python

```python
from simplecsv import simplecsv

sc=simplecsv("file.csv")
sc.writerow(["ID","NAME","INFO"])
sc.writerows(data)
sc.close()
```
