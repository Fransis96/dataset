# Dataset

### RAW Data
* laporan_iklim_harian_jayapura(2023-2025).csv
  ```
  https://raw.githubusercontent.com/Fransis96/dataset/main/laporan_iklim_harian_jayapura(2023-2026).csv
  ```

### Muat dataset dan menampilkan 5 baris pertama
> Contoh data `laporan_iklim_harian_jayapura(2023-2025).csv`  
```python
import pandas as pd

df = pd.read_csv('https://raw.githubusercontent.com/Fransis96/dataset/main/laporan_iklim_harian_jayapura(2023-2026).csv')
df.head()
```

### Unduh dataset menggunakan `code cell` di [**google colab**](https://colab.google/)  
> Contoh data `laporan_iklim_harian_jayapura(2023-2025).csv`  
```python
!wget 'https://raw.githubusercontent.com/Fransis96/dataset/main/laporan_iklim_harian_jayapura(2023-2026).csv'
```
