# 2.6 Quadratic Formula Notes

## Interactive HTML

Open these files in any web browser (download them, then double-click):

- [`html/quadratic-formula-discriminant-slides.html`](html/quadratic-formula-discriminant-slides.html): the 24-slide lesson deck, *The Quadratic Formula and the Discriminant*. Use the arrow keys or space bar to move through the slides. Press **N** to show speaker notes and **F** for full screen.
- [`html/quadratic-lab.html`](html/quadratic-lab.html): **Quadratic Lab**, the five practice games the gold slides link to (Factor Finder, Spot the Slip, Discriminant Dash, Parabola Lab, Solution Showdown).

The game links in the slides open `quadratic-lab.html` from the same folder, so keep both files together.

## The Quadratic Formula

For any quadratic equation in **standard form**

$$ax^2 + bx + c = 0, \quad a \neq 0$$

the solutions are

$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

> Memory aid (sung to "Pop Goes the Weasel"): *"x equals negative b, plus or minus the square root, of b squared minus four a c, all over two a."*

---

## Steps for Using the Quadratic Formula

1. **Write the equation in standard form** — get everything on one side so it equals 0.
2. **Identify** $a$, $b$, and $c$ (include the signs!).
3. **Substitute** into the formula. Use parentheses, especially for negative values.
4. **Simplify** the discriminant $b^2 - 4ac$ first.
5. **Simplify** the radical and reduce the fraction if possible.

---

## The Discriminant

The expression under the radical, $b^2 - 4ac$, is called the **discriminant**. It tells you the number and type of solutions **before** you solve.

| Value of $b^2 - 4ac$ | Number & Type of Solutions | Graph of $y = ax^2 + bx + c$ |
|---|---|---|
| Positive (perfect square) | 2 real, rational solutions | Crosses the x-axis twice |
| Positive (not a perfect square) | 2 real, irrational solutions | Crosses the x-axis twice |
| Zero | 1 real (repeated) solution | Touches the x-axis once (vertex) |
| Negative | 2 complex (imaginary) solutions | Does not touch the x-axis |

---

## Where Does It Come From? (Completing the Square)

$$
\begin{aligned}
ax^2 + bx + c &= 0 \\
x^2 + \frac{b}{a}x &= -\frac{c}{a} \\
x^2 + \frac{b}{a}x + \frac{b^2}{4a^2} &= \frac{b^2}{4a^2} - \frac{c}{a} \\
\left(x + \frac{b}{2a}\right)^2 &= \frac{b^2 - 4ac}{4a^2} \\
x + \frac{b}{2a} &= \pm\frac{\sqrt{b^2 - 4ac}}{2a} \\
x &= \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
\end{aligned}
$$

---

## Worked Examples

### Example 1: Two rational solutions
Solve $x^2 + 5x + 6 = 0$.

- $a = 1,\ b = 5,\ c = 6$
- Discriminant: $5^2 - 4(1)(6) = 25 - 24 = 1$

$$x = \frac{-5 \pm \sqrt{1}}{2(1)} = \frac{-5 \pm 1}{2}$$

$$x = -2 \quad \text{or} \quad x = -3$$

### Example 2: Two irrational solutions
Solve $2x^2 - 4x - 3 = 0$.

- $a = 2,\ b = -4,\ c = -3$
- Discriminant: $(-4)^2 - 4(2)(-3) = 16 + 24 = 40$

$$x = \frac{-(-4) \pm \sqrt{40}}{2(2)} = \frac{4 \pm 2\sqrt{10}}{4} = \frac{2 \pm \sqrt{10}}{2}$$

### Example 3: One repeated solution
Solve $x^2 - 6x + 9 = 0$.

- $a = 1,\ b = -6,\ c = 9$
- Discriminant: $(-6)^2 - 4(1)(9) = 36 - 36 = 0$

$$x = \frac{6 \pm \sqrt{0}}{2} = 3$$

### Example 4: Two complex solutions
Solve $x^2 + 2x + 5 = 0$.

- $a = 1,\ b = 2,\ c = 5$
- Discriminant: $2^2 - 4(1)(5) = 4 - 20 = -16$

$$x = \frac{-2 \pm \sqrt{-16}}{2} = \frac{-2 \pm 4i}{2} = -1 \pm 2i$$

---

## Common Mistakes to Avoid

- Forgetting to set the equation equal to **0** before identifying $a$, $b$, $c$.
- Dropping the negative sign on $b$ — if $b = -4$, then $-b = 4$.
- Writing $-4^2$ instead of $(-4)^2$. Always square $b$ in parentheses: $b^2$ is never negative.
- Dividing only part of the numerator by $2a$ — the fraction bar goes under the **entire** numerator.
- Not simplifying the radical (e.g., $\sqrt{40} = 2\sqrt{10}$).

---

## Practice Problems

Solve each equation using the quadratic formula. Use the discriminant first to predict the number and type of solutions.

1. $3x^2 + x - 2 = 0$
2. $x^2 - 2x - 7 = 0$
3. $4x^2 + 4x + 1 = 0$
4. $x^2 + 4x + 13 = 0$
5. $5x^2 = 3x + 1$

<details>
<summary><strong>Answer Key</strong></summary>

| # | Discriminant | Solutions |
|---|---|---|
| 1 | $25$ (2 rational) | $x = \frac{2}{3},\ x = -1$ |
| 2 | $32$ (2 irrational) | $x = 1 \pm 2\sqrt{2}$ |
| 3 | $0$ (1 repeated) | $x = -\frac{1}{2}$ |
| 4 | $-36$ (2 complex) | $x = -2 \pm 3i$ |
| 5 | $29$ (2 irrational) | $x = \frac{3 \pm \sqrt{29}}{10}$ |

</details>
