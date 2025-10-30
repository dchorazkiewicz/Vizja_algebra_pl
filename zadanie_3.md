### Krok po kroku: rozwiązanie zadania

Mamy daną macierz:

$$
C = \begin{pmatrix}
1 & 0 & 2 \\
-1 & 3 & 1 \\
0 & 2 & -1
\end{pmatrix}
$$

#### **Krok 1: Zamiana 1. i 3. wiersza**

- Pierwotny 1. wiersz: $[1,\ 0,\ 2]$  
- Pierwotny 3. wiersz: $[0,\ 2,\ -1]$  

Zamieniamy je miejscami.

Po zamianie wierszy macierz wygląda tak:

$$
C_1 = \begin{pmatrix}
\color{blue}{0} & \color{blue}{2} & \color{blue}{-1} \\
-1 & 3 & 1 \\
\color{blue}{1} & \color{blue}{0} & \color{blue}{2}
\end{pmatrix}
$$

**Wyjaśnienie operacji:**  
- Nowy 1. wiersz = dawny 3. wiersz  
- Nowy 3. wiersz = dawny 1. wiersz  
- 2. wiersz bez zmian

---

#### **Krok 2: Dodanie do 2. wiersza dwukrotności nowego 1. wiersza**

Nowy 1. wiersz (po zamianie): $[0,\ 2,\ -1]$  
Dwukrotność tego wiersza: $2 \times [0,\ 2,\ -1] = [0,\ 4,\ -2]$

Teraz dodajemy ten wektor do **2. wiersza** macierzy $C_1$:

$$
\text{nowy 2. wiersz} = [-1,\ 3,\ 1] + [0,\ 4,\ -2] = [-1+0,\ 3+4,\ 1-2] = [-1,\ 7,\ -1]
$$

Pozostałe wiersze bez zmian.

Po tej operacji macierz końcowa:

$$
C_2 = \begin{pmatrix}
0 & 2 & -1 \\
\color{red}{-1} & \color{red}{7} & \color{red}{-1} \\
1 & 0 & 2
\end{pmatrix}
$$

---

### **Macierz końcowa:**

$$
\boxed{
\begin{pmatrix}
0 & 2 & -1 \\
-1 & 7 & -1 \\
1 & 0 & 2
\end{pmatrix}
}
$$

Gotowe! Wszystkie kroki są zapisane szczegółowo.