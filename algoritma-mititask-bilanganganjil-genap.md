## MiniTask Algoritma Menentukan Bilangan Ganjil dan Genap

1. Mulai
2. Input angka 'X'
3. Jika angka 'X' dibagi 2 hasil sisa baginya 0, Maka angka 'X' tersebut bilangan genap.
4. Jika tidak, maka angka 'X' tersebut bilangan ganjil
5. Selesai

## Flowchart 1
```mermaid
flowchart LR

a@{shape: circle, label: "start"}
b@{shape: lean-r, label: "X"}
c@{shape: diamond, label: "X % 2 == 0"}
d@{shape: lean-r, label: '"Bilangan Genap"'}
e@{shape: lean-r, label: '"Bilangan Ganjil"'}
x@{shape: dbl-circ, label: "stop"}

a --> b
b --> c
c --TRUE--> d
c --FALSE--> e
d --> x
e --> x
```
## Psuedocode 1
```pseudocode
DECLARE X: INTEGER

INPUT X

IF X MOD 2 == 0 THEN
    OUTPUT "Bilangan Genap"
ELSE
    OUTPUT "Bilangan Ganjil"
ENDIF

```
## Flowchart 2
```mermaid
flowchart LR

a@{shape: circle, label: "start"}
dk@{shape: rect, label: "X, RESULT"}
b@{shape: lean-r, label: "X"}
c@{shape: diamond, label: "X % 2 == 0"}
d@{shape: rect, label: RESULT = "Bilangan Genap"}
e@{shape: rect, label: RESULT = "Bilangan Ganjil"}
f@{shape: lean-r, label: '"RESULT"'}
x@{shape: dbl-circ, label: "stop"}

a --> dk
dk --> b
b --> c
c --TRUE--> d
c --FALSE--> e
d --> f
e --> f
f --> x
```
## Psuedocode 2
```pseudocode
DECLARE X: INTEGER
DECLARE RESULT: STRING

INPUT X

IF X MOD 2 == 0 THEN
    RESULT <- "Bilangan Genap"
ELSE
    RESULT <- "Bilangan Ganjil"
ENDIF

OUTPUT RESULT

```


