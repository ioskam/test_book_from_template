# Begeleide oefening

::::{question} Opgave
:type: short-answer
:variant: gaps
:admonition:
:class: exercise
:nocaption:
:showanswer:

---
M[\begin{pmatrix} 4000 & 2000 \\\ 2000 & 4000 \end{pmatrix}]
^^^
? Bepaal de elementstijfheidsmatrix $\mathbf{K}^{(e)}$ voor een willekeurig element.

$\mathbf{K}^{(e)} = $ {gap}

---

::::

% solution_start

::::{admonition} Uitwerking
:class: solution, dropdown

$$\mathbf{K}^{(e)} = \begin{bmatrix} \cfrac{4EI}{l} & \cfrac{2EI}{l} \\ \cfrac{2EI}{l} & \cfrac{4EI}{l} \end{bmatrix} = \begin{bmatrix} 4000 & 2000 \\ 2000 & 4000 \end{bmatrix}$$

::::

% solution_end

::::{question} Opgave
:type: short-answer
:variant: gaps
:admonition:
:class: exercise
:nocaption:
:showanswer:

---
M[\begin{pmatrix} 4000 & 2000 & 0 & 0 & 0 \\\ 2000 & 12000 & 2000 & 2000 & 0 \\\ 0 & 2000 & 8000 & 0 & 2000 \\\ 0 & 2000 & 0 & 4000 & 0 \\\ 0 & 0 & 2000 & 0 & 4000 \end{pmatrix}]
^^^
? Bepaal de globale stijfheidsmatrix $\mathbf{K}$.

$\mathbf{K} = $ {gap}

---

::::

% solution_start

::::{admonition} Uitwerking
:class: solution, dropdown

De globale stijfheidsmatrix kan uit de elementstijfheidsmatrices worden bepaald door de elementen te plaatsen in de rijen en kolommen behorend bij de knopen en op te tellen.

$$\mathbf{K} =
\begin{bmatrix} 
4000 & 2000 & 0 & 0 & 0 \\ 
2000 & 4000+4000+4000 & 2000 & 2000 & 0 \\ 
0 & 2000 & 4000+4000 & 0 & 2000 \\ 
0 & 2000 & 0 & 4000 & 0 \\ 
0 & 0 & 2000 & 0 & 4000 
\end{bmatrix}
=
\begin{bmatrix} 
4000 & 2000 & 0 & 0 & 0 \\ 
2000 & 12000 & 2000 & 2000 & 0 \\ 
0 & 2000 & 8000 & 0 & 2000 \\ 
0 & 2000 & 0 & 4000 & 0 \\ 
0 & 0 & 2000 & 0 & 4000 
\end{bmatrix}$$

::::

% solution_end
