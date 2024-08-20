## Electric field
Is the measure of force applied to any charge **Q** at a certain point in space **P** by existing charges **q<sub>1</sub>, q<sub>2</sub>, ... q<sub>N</sub>**. 
Additional definitions:
1. The vector between charge q<sub>N</sub> and point P is:
$$\vec{R_N}$$
### Expanded formula from Coulomb's law and simple definition
$$
\begin{gather}
\boxed{\tag*{Coulomb's law}F = k \frac{q_1 q_2}{r^2}}\\
\boxed{\tag*{E as Force and charge ratio} \vec{E} = \frac{\vec{F}}{Q}}
\end{gather}
$$
$$
\begin{gather}
\vec{F} = k\bigg(\frac{Qq_1}{|\vec{R_1}|^2}*\hat{R_1} + \frac{Qq_2}{|\vec{R_2}|^2}*\hat{R_2} ... + \frac{Qq_N}{|\vec{R_N}|^2}*\hat{R_N}\bigg)\\ \tag*{}\\

\vec{F} = kQ\bigg(\frac{q_1}{|\vec{R_1}|^2}*\hat{R_1} + \frac{q_2}{|\vec{R_2}|^2}*\hat{R_2} ... + \frac{q_N}{|\vec{R_N}|^2}*\hat{R_N}\bigg)\\ \tag*{}\\

\vec{E} = \frac{k\cancel{Q}\bigg(\frac{q_1}{|\vec{R_1}|^2}*\hat{R_1} + \frac{q_2}{|\vec{R_2}|^2}*\hat{R_2} ... + \frac{q_N}{|\vec{R_N}|^2}*\hat{R_N}\bigg)}{\cancel{Q}}\\ \tag*{}\\

\underline{\vec{E} = k\bigg(\frac{q_1}{|\vec{R_1}|^2}*\hat{R_1} + \frac{q_2}{|\vec{R_2}|^2}*\hat{R_2} ... + \frac{q_N}{|\vec{R_N}|^2}*\hat{R_N}\bigg)}\\ \tag*{}\\

\text{Shortened form:}\\

\vec{E} = k\sum_{i=1}^{N} {\frac{q_i}{|\vec{R_i}|^2}*\hat{R_i}}

\end{gather}
$$

This essentially boils down to "How much force will a charged particle experience at a point in space, where an electric field is present.". This is a very convenient understanding when looking at the electric field as a vector field realized, most commonly, on a plane, as it allows for easy identification, and prediction of forces applied to a charge once in the given arrangment since it scales linearly with the charge value.

## Electric potential and potential energy

Electric potential is another spacial property of a charge, just like the electric field. It is the measure of work needed to move a test charge **Q** from infinity to a point closer to charge **q**, or simply its's potential energy of **Q** in a certain point in space

### Electric potential energy

From the work equation: $W = \vec{F}\cdot\vec{r}$ we know that work only applies when the displacement vector is aligned with the force vector or its' component. This implies That in an electric field, work is done only when displacement (or its' component) is parallel to the field lines, as that is always how the force is aligned (see the definition of field lines).

knowing this we can simplify the equation for work (and thus, potential enegry), knowing that: $\vec{r}\iff\vec{qQ}$ and $|\vec{F}| = \vec{E}Q$
$$
\begin{gather}
\boxed{\tag*{Geometric work equation}{W = |\vec{F}||\vec{r}|cos( \measuredangle \vec{F}\vec{r})}}\\ \tag*{}\\

W = EQ|\vec{r}|cos( \measuredangle \vec{F}\vec{r})\\ \tag*{}\\
 \tag*{}\text{knowing that } \vec{F}\text{ is a product of the electric field, and vector } \vec{r} \text{ is originated in q, just like the field. We can deduce that they will always be parralel, meaning:}\\ \tag*{}\\
 
\measuredangle \vec{F}\vec{r} = 0 \iff cos( \measuredangle \vec{F}\vec{r}) = 1 \\ \tag*{}\\

\large \underline{W = U = EQ|\vec{r}|}\\ \tag*{}\\
\text{Expanded form:}\\ \tag*{}\\
W=U=k\frac{qQ}{|\vec{r}|}
\end{gather}
$$
This equation bears a very convenient resemblance to the equation for potential energy within a gravitiational field $U = mgh$, which might be useful when trying to understand the equation. The expanded form is useful when formulating a detailed equation for **electric potential: V**

### Electric potential
Starting off the derivation with the simple expression:
$$
\begin{gather}
\boxed{V=\frac{U}{Q}}\\\tag*{}\\
\text{we can simply substitue the equation for U}\\\tag*{}\\
\large  V=\frac{k\frac{q\cancel{Q}}{|\vec{r}|}}{\cancel{Q}}\\\tag*{}\\
\large \underline{V=k\frac{q}{|\vec{r}|}}
\end{gather}
$$
Leaving us with an elegant formula for the potential at an arbitrary point around a charge **q**. An important observation to make is the fact the division uses the value of the vector $\vec{r}$, without its' directional component. This Introduces the concept of **Equipotential**, and equpotential lines. It simply states that on a circle (or sphere in a 3 dimensional cartesian system), with its' centre in the centre of the charge, The potential is identical. In other words, the vector can be rotated around its' base, and as long as we keep the length, the end of this vector will trace an equipotential line (or surface, in 3 dimensions).
