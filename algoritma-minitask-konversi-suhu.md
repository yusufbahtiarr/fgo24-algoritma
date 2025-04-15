# Mini Task - Konversi Suhu

1. Mulai
2. Input nilai suhu Celcius sebagai 'C'
3. Pilih Konversi Suhu
4. Konversi Suhu ke Farenheit dengan rumus (9/5 x C) + 32.
5. Konversi Suhu ke Reamur dengan rumus 4/5 x C 
6. Konversi Suhu ke Kelvin dengan rumus C + 273
7. Tampilkan Hasil Konversi Suhu
8. Selesai

```mermaid
flowchart LR
a@{shape: circle, label: "Mulai"}
b@{shape: lean-r, label: "C"}
c@{shape: diamond, label: "Konversi Suhu?"}
cf@{shape: rect, label: "Farenheit = (9/5 x C) + 32"}
cr@{shape: rect, label: "Reamur = (4/5 x C"}
ck@{shape: rect, label: "Kelvin = C + 273"}
d@{shape: lean-r, label: '"Konversi Suhu Farenheit/Reamur/Kelvin"'}
x@{shape: dbl-circ, label: "Stop"}

a --> b
b --> c
c --> cf
c --> cr
c --> ck
cf --> d
cr --> d
ck --> d
d --> x

```



