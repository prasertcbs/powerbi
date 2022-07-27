# create `pbi` environment from `pbi.yml`

```
conda env create -f pbi.yml
conda activate pbi
```

## test python environment (copy and paste the following codes to Power BI Python script)
```
import pandas as pd

df=pd.read_csv('https://raw.githubusercontent.com/prasertcbs/basic-dataset/master/mtcars.csv')
df[:3]
```
