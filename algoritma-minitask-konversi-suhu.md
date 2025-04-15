1. Mulai
2. Input nilai suhu Celcius sebagai 'C'
4. Konversi Suhu Celcius ke Farenheit dengan rumus (9/5 x C) + 32.
5. Konversi Suhu Celcius ke Reamur dengan rumus 4/5 x C 
6. Konversi Suhu Celcius ke Kelvin dengan rumus C + 273
7. Tampilkan Hasil Konversi Suhu
8. Selesai

```mermaid
flowchart LR
a@{shape: circle, label: "Mulai"}
b@{shape: lean-r, label: "C"}
c@{shape: rect, label: "Farenheit = (9/5 x C) + 32"}
d@{shape: rect, label: "Reamur = 4/5 x C"}
e@{shape: rect, label: "Kelvin = C + 273"}
f@{shape: lean-r, label: '"Konversi Suhu Farenheit, Reamur, Kelvin"'}
x@{shape: dbl-circ, label: "Stop"}

a --> b
b --> c
c --> d
d --> e
e --> f
f --> x

```
