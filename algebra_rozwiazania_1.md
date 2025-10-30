Z przyjemnością pomogę Ci rozwiązać to zadanie krok po kroku! 😊

Dane mamy macierze:
$$
A=\begin{pmatrix}1 & 2\\ 3 & 4\end{pmatrix} \quad \text{i} \quad B=\begin{pmatrix}0 & -1\\ 2 & 1\end{pmatrix}
$$

---

## 1. Dodawanie macierzy: $A+B$

Aby dodać dwie macierze o tych samych wymiarach, dodajemy odpowiadające sobie elementy.

$$
A+B = \begin{pmatrix}1 & 2\\ 3 & 4\end{pmatrix} + \begin{pmatrix}0 & -1\\ 2 & 1\end{pmatrix} = \begin{pmatrix}1+0 & 2+(-1)\\ 3+2 & 4+1\end{pmatrix} = \begin{pmatrix}1 & 1\\ 5 & 5\end{pmatrix}
$$

**Wynik:**
$$
A+B = \begin{pmatrix}1 & 1\\ 5 & 5\end{pmatrix}
$$

---

## 2. Odejmowanie macierzy: $A-B$

Aby odjąć macierze o tych samych wymiarach, odejmujemy odpowiadające sobie elementy.

$$
A-B = \begin{pmatrix}1 & 2\\ 3 & 4\end{pmatrix} - \begin{pmatrix}0 & -1\\ 2 & 1\end{pmatrix} = \begin{pmatrix}1-0 & 2-(-1)\\ 3-2 & 4-1\end{pmatrix} = \begin{pmatrix}1 & 2+1\\ 1 & 3\end{pmatrix} = \begin{pmatrix}1 & 3\\ 1 & 3\end{pmatrix}
$$

**Wynik:**
$$
A-B = \begin{pmatrix}1 & 3\\ 1 & 3\end{pmatrix}
$$

---

## 3. Mnożenie macierzy przez skalar: $2A$

Aby pomnożyć macierz przez skalar (liczbę), mnożymy każdy element macierzy przez ten skalar.

$$
2A = 2 \cdot \begin{pmatrix}1 & 2\\ 3 & 4\end{pmatrix} = \begin{pmatrix}2\cdot 1 & 2\cdot 2\\ 2\cdot 3 & 2\cdot 4\end{pmatrix} = \begin{pmatrix}2 & 4\\ 6 & 8\end{pmatrix}
$$

**Wynik:**
$$
2A = \begin{pmatrix}2 & 4\\ 6 & 8\end{pmatrix}
$$

---

## 4. Kombinacja liniowa macierzy: $3B-2A$

Najpierw obliczamy $3B$ i $2A$, a następnie odejmujemy.

### Obliczenie $3B$:
$$
3B = 3 \cdot \begin{pmatrix}0 & -1\\ 2 & 1\end{pmatrix} = \begin{pmatrix}3\cdot 0 & 3\cdot (-1)\\ 3\cdot 2 & 3\cdot 1\end{pmatrix} = \begin{pmatrix}0 & -3\\ 6 & 3\end{pmatrix}
$$

### Obliczenie $2A$:
(Już obliczyliśmy w punkcie 3):
$$
2A = \begin{pmatrix}2 & 4\\ 6 & 8\end{pmatrix}
$$

### Obliczenie $3B-2A$:
$$
3B-2A = \begin{pmatrix}0 & -3\\ 6 & 3\end{pmatrix} - \begin{pmatrix}2 & 4\\ 6 & 8\end{pmatrix} = \begin{pmatrix}0-2 & -3-4\\ 6-6 & 3-8\end{pmatrix} = \begin{pmatrix}-2 & -7\\ 0 & -5\end{pmatrix}
$$

**Wynik:**
$$
3B-2A = \begin{pmatrix}-2 & -7\\ 0 & -5\end{pmatrix}
$$

---

## 5. Mnożenie macierzy: $A \cdot B$

Aby pomnożyć macierze $A$ (wymiar $2\times 2$) i $B$ (wymiar $2\times 2$), element w $i$-tym wierszu i $j$-tej kolumnie macierzy wynikowej jest iloczynem skalarnym $i$-tego wiersza macierzy $A$ i $j$-tej kolumny macierzy $B$.

$$
A\cdot B = \begin{pmatrix}1 & 2\\ 3 & 4\end{pmatrix} \cdot \begin{pmatrix}0 & -1\\ 2 & 1\end{pmatrix} = \begin{pmatrix}c_{11} & c_{12}\\ c_{21} & c_{22}\end{pmatrix}
$$

* $c_{11} = (1)\cdot(0) + (2)\cdot(2) = 0 + 4 = **4**$ (1. wiersz $A$ $\times$ 1. kolumna $B$)
* $c_{12} = (1)\cdot(-1) + (2)\cdot(1) = -1 + 2 = **1**$ (1. wiersz $A$ $\times$ 2. kolumna $B$)
* $c_{21} = (3)\cdot(0) + (4)\cdot(2) = 0 + 8 = **8**$ (2. wiersz $A$ $\times$ 1. kolumna $B$)
* $c_{22} = (3)\cdot(-1) + (4)\cdot(1) = -3 + 4 = **1**$ (2. wiersz $A$ $\times$ 2. kolumna $B$)

**Wynik:**
$$
A\cdot B = \begin{pmatrix}4 & 1\\ 8 & 1\end{pmatrix}
$$

---

## 6. Sprawdzenie, czy $A \cdot B = B \cdot A$

Musimy obliczyć iloczyn $B \cdot A$ i porównać go z $A \cdot B$.

$$
B\cdot A = \begin{pmatrix}0 & -1\\ 2 & 1\end{pmatrix} \cdot \begin{pmatrix}1 & 2\\ 3 & 4\end{pmatrix} = \begin{pmatrix}d_{11} & d_{12}\\ d_{21} & d_{22}\end{pmatrix}
$$

* $d_{11} = (0)\cdot(1) + (-1)\cdot(3) = 0 - 3 = **-3**$ (1. wiersz $B$ $\times$ 1. kolumna $A$)
* $d_{12} = (0)\cdot(2) + (-1)\cdot(4) = 0 - 4 = **-4**$ (1. wiersz $B$ $\times$ 2. kolumna $A$)
* $d_{21} = (2)\cdot(1) + (1)\cdot(3) = 2 + 3 = **5**$ (2. wiersz $B$ $\times$ 1. kolumna $A$)
* $d_{22} = (2)\cdot(2) + (1)\cdot(4) = 4 + 4 = **8**$ (2. wiersz $B$ $\times$ 2. kolumna $A$)

**Wynik $B \cdot A$:**
$$
B\cdot A = \begin{pmatrix}-3 & -4\\ 5 & 8\end{pmatrix}
$$

**Porównanie:**

* $A\cdot B = \begin{pmatrix}4 & 1\\ 8 & 1\end{pmatrix}$
* $B\cdot A = \begin{pmatrix}-3 & -4\\ 5 & 8\end{pmatrix}$

Ponieważ odpowiadające sobie elementy macierzy $A \cdot B$ i $B \cdot A$ **nie** są równe, możemy stwierdzić:

$$
A\cdot B \neq B\cdot A
$$

Wnioskujemy, że **mnożenie macierzy nie jest przemienne** dla tych dwóch macierzy.

---



3. Obliczenie iloczynu $D \cdot C \cdot B \cdot A$Ponownie, wykorzystujemy przemienność mnożenia macierzy diagonalnych. Zbiór macierzy jest ten sam: $\{A, B, C, D\}$.$$D\cdot C\cdot B\cdot A = \begin{pmatrix}8\cdot 4\cdot 2\cdot 1 & 0\\ 0 & 16\cdot 8\cdot 4\cdot 2\end{pmatrix}$$Obliczenia dla przekątnej:Element $(1,1)$: $8 \cdot 4 \cdot 2 \cdot 1 = 32 \cdot 2 = **64**$Element $(2,2)$: $16 \cdot 8 \cdot 4 \cdot 2 = 128 \cdot 8 = **1024**$