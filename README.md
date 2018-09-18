# simplecsv

Easily manipulate csv files using python

```python
from simplecsv import simplecsv

sc=simplecsv("file.csv")
sc.writerow(["ID","NAME","INFO"])
sc.writerows(data)
sc.close()
```

You can change how simplecsv uses files using `simplecsv(mode="")`

default mode is `"a+"` but any mode is acceptable eg `"w+"` or `"r"`
