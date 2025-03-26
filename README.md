# UMINT-UNS_data
## Umelá inteligencia 2025 

- databody.mat / databody.csv
- CTGdata.mat / CTGdata.csv
- datafun.mat / datafun.csv + datafunindx.csv
- datapiscisla_all.mat 

Zadanie projektu – Umelé neurónové siete Blok 2:
- 5:
  - A) Klasifikácia do skupín pomocou viacvrstvovej perceptronovej (MLP) siete.  (databody) 
  - B) Aproximácia nelineárnej funkcie pomocou MLP siete. (datafun.csv + datafunindx.csv )
    - Label:
      * 1: **train** indexes
      * 2: **test** indexes 
- 6: Klasifikácia na medicínskych dátach pomocou MLP siete.  (CTGdata.csv/CTGdata.mat)
- 7: Rozpoznávanie rukou písaných číslic pomocou MLP siete.  () 
- 8: Rozpoznávanie rukou písaných číslic pomocou konvolučnej neurónovej siete.  ()


```python
import pandas as pd
 
# Načítanie datasetu z online GitHub raw URL
url = "https://raw.githubusercontent.com/xHalaso/UMINT-UNS_data/main/Python_(CSV)/databody.csv"
df = pd.read_csv(url)
 
# Voliteľne vypísať prvých pár riadkov
print(df.head())
```
