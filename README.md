# **Membuat Kode Program dari flowchart pertemuan ke 5**

## **bilanganterbesar.py**

Program pertama yang akan dibuat adalah Program untuk menampilkan bilangan terbesar dari 3 Bilangan yang di Inputkan

Berikut flowchartnya

<img src="/.images/pertama.png" width="500" alt="Flowchart">

**Program akan meminta kita untuk memasukkan 3 angka untuk dibandingkan :**

<img src="/.images/outputprogram1.png" width="500" alt="Flowchart">

**Penjelasan**

```
def mencari_bilangan_terbesar(a, b, c):
    if a > b:
        if a > c:
            return a, "A adalah terbesar"
        else:
            return c, "C adalah terbesar"
    else:
        if b > c:
            return b, "B adalah terbesar"
        else:
            return c, "C adalah terbesar"
```