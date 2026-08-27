````{margin}
```{attributiongrey} Bronvermelding
:class: attribution

Deze oefening is aangepast de [tweede opgave van dit tentamen](https://icozct.tudelft.nl/TUD_CT/CT2031/tentamens/files/2031-3001-2017.pdf) van {cite:ts}`Exam_30_01_2017`.

```
````

# COZ opgave 2.9

::::::{note}
Deze opgave kan in ANS gemaakt worden.
:::{todo}
[Toevoegen link naar ANS toets.](https://github.com/TUDelft-books/CTB2210/issues/90)
:::
::::::

% https://ans.app/repo_questions/...

Gegeven is de volgende constructie:

```{figure-start} ./COZ_data/constructie2.svg
---
align: center
number:
figclass: sticky-margin
source: https://github.com/Structural-Mechanics-CEG/mechanics-figures-source/tree/main/verplaatsingenmethode_vrijheidsgraden_2
---

```

$EI \gg EA$

```{figure-end}
```

Deze constructie kan ook gezien worden als

```{figure} ./COZ_data/constructie_veren.svg
---
align: center
number:
figclass: sticky-margin
source: https://github.com/Structural-Mechanics-CEG/mechanics-figures-source/tree/main/verplaatsingenmethode_vrijheidsgraden_2
---

```

Waarbij de stijfheid van de veren bekend is.

::::{admonition} Opgave
:class: exercise

Bepaal de krachten in de pendelstaven.

Tip: de constructie is meervoudig statisch onbepaald, je hebt dus ook meerdere statisch onbepaalde krachten nodig en vormveranderingsvoorwaardes nodig en je zal een stelsel vergelijkingen moeten oplossen.

::::

% solution_start

::::{admonition} Uitwerking
:class: solution, dropdown

De constructie is drievoudig statisch onbepaald en kan statisch bepaald worden gemaakt door drie van de verende opleggingen te verwijderen. In deze uitwerking worden de krachten in de staven bij $\rm{C}$, $\rm{D}$ en $\rm{E}$ gekozen als statisch onbepaalde krachten, maar elke combinatie van drie krachten is mogelijk. Voor de krachten in de veren wordt trek aangehouden als positief. 

Nu de constructie statisch bepaald is gemaakt kan de vervorming worden opgelost. Hiertoe worden eerste de krachten $N_{\rm{A}}$ en $N_{\rm{B}}$ opgelost als functie van $N_{\rm{C}}$, $N_{\rm{D}}$ en $N_{\rm{E}}$ met behulp van evenwicht. 

$$
\begin{align}
\sum \left. T \right|  _ {\rm{A}} &= 0 \\
- N_{\rm{B}} \cdot 2 - N_{\rm{C}} \cdot 5 - N_{\rm{D}} \cdot 9 - N_{\rm{E}} \cdot 10 - 2580 \cdot 8 &= 0 \\
N_{\rm{B}} &= - \cfrac{5}{2} \cdot N_{\rm{C}} - \cfrac{9}{2} \cdot N_{\rm{D}} - 5 \cdot N_{\rm{E}} - 10320
\end{align}
$$

$$
\begin{align}
\sum  \left. F  _ {\rm{v}} &= 0 \\
- N_{\rm{A}} - N_{\rm{B}} - N_{\rm{C}} - N_{\rm{D}} - N_{\rm{E}} - 2580 &= 0 \\
N_{\rm{A}} &= - N_{\rm{B}} - N_{\rm{C}} - N_{\rm{D}} - N_{\rm{E}} - 2580 \\
 &= 7740 + \cfrac{3}{2} \cdot N_{\rm{C}} + \cfrac{7}{2} \cdot N_{\rm{D}} + 4 \cdot N_{\rm{E}}
\end{align}
$$

De verplaatsingen van de punten $\rm{A}$ en $\rm{B}$ worden bepaald uit de normaalkrachten $N_{\rm{A}}$ en $N_{\rm{B}}$ en de stijfheid van de veren bij A en B, $K_{\rm{A}}$ en $K_{\rm{B}}$. 

$$ w_{\rm{A}} = \cfrac{N_{\rm{A}}}{K_{\rm{A}}} = \cfrac{7740 + \cfrac{3}{2} \cdot N_{\rm{C}} + \cfrac{7}{2} \cdot N_{\rm{D}} + 4 \cdot N_{\rm{E}}}{100} = 77.4 + \cfrac{3}{200} \cdot N_{\rm{C}} + \cfrac{7}{200} \cdot N_{\rm{D}} + \cfrac{1}{25} \cdot N_{\rm{E}} $$

$$ w_{\rm{B}} = \cfrac{N_{\rm{B}}}{K_{\rm{B}}} = \cfrac{- 10320 - \cfrac{5}{2} \cdot N_{\rm{C}} - \cfrac{9}{2} \cdot N_{\rm{D}} - 5 \cdot N_{\rm{E}}}{200} = -51.6 - \cfrac{1}{80} \cdot N_{\rm{C}} - \cfrac{9}{400} \cdot N_{\rm{D}} - \cfrac{1}{40} \cdot N_{\rm{E}} $$

Gegeven is dat de buigstijfheid $EI$ veel groter is dan de rekstijfheid $EA$. Deel $\rm{ABCDE}$ moet dus recht blijven, dit wordt gebruikt om de vormveranderingsvoorwaarden op te stellen. 

$$
\begin{align}
w_{\rm{C}} &= w_{\rm{A}} + \cfrac{w_{\rm{B}} - w_{\rm{A}}}{2} \cdot 5 \\
\cfrac{N_{\rm{C}}}{K_{\rm{C}}} &= 77.4 + \cfrac{3}{200} \cdot N_{\rm{C}} + \cfrac{7}{200} \cdot N_{\rm{D}} + \cfrac{1}{25} \cdot N_{\rm{E}} + 5 \cdot \left( -64.5 - \cfrac{11}{800} \cdot N_{\rm{C}} - \cfrac{23}{800} \cdot N_{\rm{D}} - \cfrac{13}{400} \cdot N_{\rm{E}} \right) \\
\cfrac{N_{\rm{C}}}{300} &= -245.1 - \cfrac{43}{800} \cdot N_{\rm{C}} - \cfrac{87}{800} \cdot N_{\rm{D}} - \cfrac{49}{400} \cdot N_{\rm{E}} \\
245.1 &= -\cfrac{137}{2400} \cdot N_{\rm{C}} - \cfrac{87}{800} \cdot N_{\rm{D}} - \cfrac{49}{400} \cdot N_{\rm{E}}
\end{align}
$$

$$
\begin{align}
w_{\rm{D}} &= w_{\rm{A}} + \cfrac{w_{\rm{B}} - w_{\rm{A}}}{2} \cdot 9 \\
\cfrac{N_{\rm{D}}}{K_{\rm{D}}} &= 77.4 + \cfrac{3}{200} \cdot N_{\rm{C}} + \cfrac{7}{200} \cdot N_{\rm{D}} + \cfrac{1}{25} \cdot N_{\rm{E}} + 9 \cdot \left( -64.5 - \cfrac{11}{800} \cdot N_{\rm{C}} - \cfrac{23}{800} \cdot N_{\rm{D}} - \cfrac{13}{400} \cdot N_{\rm{E}} \right) \\
\cfrac{N_{\rm{D}}}{400} &= -503.1 - \cfrac{87}{800} \cdot N_{\rm{C}} - \cfrac{179}{800} \cdot N_{\rm{D}} - \cfrac{101}{400} \cdot N_{\rm{E}} \\
503.1 &= -\cfrac{87}{800} \cdot N_{\rm{C}} - \cfrac{181}{800} \cdot N_{\rm{D}} - \cfrac{101}{400} \cdot N_{\rm{E}}
\end{align}
$$

$$
\begin{align}
w_{\rm{E}} &= w_{\rm{A}} + \cfrac{w_{\rm{B}} - w_{\rm{A}}}{2} \cdot 10 \\
\cfrac{N_{\rm{E}}}{K_{\rm{E}}} &= 77.4 + \cfrac{3}{200} \cdot N_{\rm{C}} + \cfrac{7}{200} \cdot N_{\rm{D}} + \cfrac{1}{25} \cdot N_{\rm{E}} + 10 \cdot \left( -64.5 - \cfrac{11}{800} \cdot N_{\rm{C}} - \cfrac{23}{800} \cdot N_{\rm{D}} - \cfrac{13}{400} \cdot N_{\rm{E}} \right) \\
\cfrac{N_{\rm{E}}}{500} &= -567.6 - \cfrac{49}{400} \cdot N_{\rm{C}} - \cfrac{101}{400} \cdot N_{\rm{D}} - \cfrac{57}{200} \cdot N_{\rm{E}} \\
567.6 &= -\cfrac{49}{400} \cdot N_{\rm{C}} - \cfrac{101}{400} \cdot N_{\rm{D}} - \cfrac{287}{1000} \cdot N_{\rm{E}}
\end{align}
$$

De bovenstaande drie vormveranderingsvoorwaarden vormen drie vergelijkingen die kunnen worden opgelost voor $N_{\rm{C}}$, $N_{\rm{D}}$ en $N_{\rm{E}}$. Daarna kunnen $N_{\rm{A}}$ en $N_{\rm{B}}$ worden bepaald uit de evenwichtsvergelijkingen.

De staafkrachten zijn:
- $N_{\rm{A}} = -67 \ \rm{kN}$
- $N_{\rm{B}} = -194 \ \rm{kN}$
- $N_{\rm{C}} = -426 \ \rm{kN}$
- $N_{\rm{D}} = -808 \ \rm{kN}$
- $N_{\rm{E}} = -1085 \ \rm{kN}$

::::

% solution_end
