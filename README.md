# UMINT-UNS_data
## Umelá inteligencia 2025 

Zadanie projektu – Umelé neurónové siete, Blok 2:
### Úloha 5:
  - A) Klasifikácia do skupín pomocou viacvrstvovej perceptronovej (MLP) siete.  ( *databody.mat / databody.csv* ) 
  - B) Aproximácia nelineárnej funkcie pomocou MLP siete. ( *datafun.mat / datafun.csv + datafunindx.csv* )
    - Označenie (Label):
      * **1**: indexy určené pre **trénovanie**
      * **2**:  indexy určené pre **testovanie**
    ```python
    380,1   # train indx
    389,2   # test  indx
    ```
### Úloha 6: 
Klasifikácia na medicínskych dátach pomocou MLP siete.  ( *CTGdata.csv/CTGdata.mat* )
### Úloha7: 
Rozpoznávanie rukou písaných číslic pomocou MLP siete. ( <a href="https://pytorch.org/vision/main/generated/torchvision.datasets.MNIST.html" target="_blank"> 
 *MNIST Dataset* </a> )
### Úloha 8:
Rozpoznávanie rukou písaných číslic pomocou konvolučnej neurónovej siete. ( <a href="https://pytorch.org/vision/main/generated/torchvision.datasets.MNIST.html" target="_blank"> *MNIST Dataset* </a>  )

## GitHub (.csv) ==> Python
```python
import pandas as pd
 
# Načítanie datasetu z online GitHub raw URL
url = "https://raw.githubusercontent.com/xHalaso/UMINT-UNS_data/main/Python_(CSV)/databody.csv"
df = pd.read_csv(url)
 
# Voliteľne vypísať prvých pár riadkov
print(df.head())
```
<a href="https://pytorch.org/vision/main/datasets.html" target="_blank"> **List of PyTorch Datasets**  </a>
