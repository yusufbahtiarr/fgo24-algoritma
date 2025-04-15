# Algoritma MiniTask - Membuat Algoritma Menghitung Luas dan Keliling Lingkaran

1. Mulai
2. Masukkan jari-jari sebagai 'r'
3. Jika 'r'' habis dibagi 7, maka gunakan 'phi' sebagai 22/7
4. Jika tidak gunakan 'phi sebagai 3.14
5. Hitung luas dengan 'phi' dikali r kuadrat
6. Hitung keliling dengan '2 dikali phi' dikali r
7. Tampilkan luas dan keliling lingkaran
8. Selesai

## FLowchart
```mermaid
    flowchart LR
    a@{shape: circle, label: "Mulai"}
    b@{shape: lean-r, label: "r"}
    c@{shape: diamond, label: "r % 7 == 0"}
    d@{shape: lean-r, label: "phi = 22/7"}
    e@{shape: lean-r, label: "phi = 3.14"}
    f@{shape: rect, label: "luas = phi x r x r"}
    g@{shape: rect, label: "keliling = 2 x phi x r"}
    h@{shape: lean-r, label: '"Luas dan keliling Lingkaran"'}
    x@{shape: dbl-circ, label: "Stop"}

    a --> b
    b --> c
    c --TRUE--> d
    c --FALSE--> e
    d --> f
    e --> f
    f --> g
    g --> h
    h --> x 


```
