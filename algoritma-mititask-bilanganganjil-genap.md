## MiniTask Algoritma Menentukan Bilangan Ganjil dan Genap

1. Mulai
2. Input Angka 'X'
3. Apakah angka 'X' dibagi 2 hasilnya 0?, maka angka 'X' bilangan genap.
4. Jika tidak, maka angka 'X' tersebut bilangan ganjil
5. Selesai

## Flowchart
```mermaid
flowchart LR

a@{shape: circle, label: "start"}
b@{shape: lean-r, label: "X"}
c@{shape: diamond, label: "x % 2 == 0"} 
d@{shape: lean-r, label: '"Genap"'}
e@{shape: lean-r, label: '"Ganjil"'}
x@{shape: dbl-circ, label: "stop"}

a --> b
b --> c
c --TRUE--> d
c --FALSE--> e
d --> x
e --> x
```

```pseudocode
DECLARE X: INTEGER

INPUT X

IF X % == 0 THEN
    OUTPUT <- "Bilangan Genap"
ELSE
    OUTPUT <- "Bilangan Ganjil"
END IF

```
```mermaid
flowchart LR

a@{shape: circle, label: "start"}
dk@{shape: rect, label: "x, result"}
b@{shape: lean-r, label: "X"}
c@{shape: diamond, label: "x % 2 == 0"} 
d@{shape: lean-r, label: '"Genap"'}
e@{shape: lean-r, label: '"Ganjil"'}
x@{shape: dbl-circ, label: "stop"}

a --> dk
dk --> b
b --> c
c --TRUE--> d
c --FALSE--> e
d --> x
e --> x
```
```pseudocode
DECLARE X: INTEGER
DECLARE RESULT: STRING

INPUT X

IF X % == 0 THEN
    RESULT <- "Genap"
ELSE
    RESULT <- "Ganjil"
END IF

OUTPUT "Bilangan ", RESULT

```


