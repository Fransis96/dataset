# Dataset

### RAW Data

<details>
  <summary>Laporan iklim harian jayapura</summary><br>
  
  - 2023-2026
    > **Nama Stasiun**: Stasiun Meteorologi Dok II Jayapura  
    > **Sumber**: https://dataonline.bmkg.go.id/data-harian  
    ```
    https://raw.githubusercontent.com/Fransis96/dataset/main/laporan_iklim_harian_jayapura(2023-2026).csv
    ```
     
</details>
<details>
  <summary>Data gempa bumi</summary><br>
  
  > Sumber: https://dataonline.bmkg.go.id/data-gempabumi  
  > ...

</details>

---

### Muat dataset dan menampilkan 5 baris pertama
> Contoh data `laporan_iklim_harian_jayapura(2023-2025).csv`  
```python
import pandas as pd

df = pd.read_csv('https://raw.githubusercontent.com/Fransis96/dataset/main/laporan_iklim_harian_jayapura(2023-2026).csv')
df.head()
```

---

### Unduh dataset menggunakan `code cell` di [**google colab**](https://colab.google/)  
> Contoh data `laporan_iklim_harian_jayapura(2023-2025).csv`  
```python
!wget 'https://raw.githubusercontent.com/Fransis96/dataset/main/laporan_iklim_harian_jayapura(2023-2026).csv'
```
