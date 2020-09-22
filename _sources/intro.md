# Testing Long equations

## Long Equation

$$
\begin{align}
\mathrm{SetConv} \left( \{(x^{c},y^{c})\}_{c=1}^{C} \right)(x) \left( \{(x^{c},y^{c})\}_{c=1}^{C} \right)(x) \left( \{(x^{c},y^{c})\}_{c=1}^{C} \right)(x)
&= \sum_{c=1}^{C} y^{(c)} w_{\theta} \left( x - x^{(c)} \right)  \sum_{c=1}^{C} y^{(c)} w_{\theta} \left( x - x^{(c)} \right) \sum_{c=1}^{C} y^{(c)} w_{\theta} \left( x - x^{(c)} \right)\\
&= \left( y^{(c')} w_{\theta} \left( x - x^{(c')} \right) \right) + \sum_{c \neq c'}  y^{(c)} w_{\theta} \left( x - x^{(c)} \right) \\
&= 0 + \sum_{c \neq c'}  y^{(c)} w_{\theta} \left( x - x^{(c)} \right)
\end{align}
$$

## Long Equation in Admonition

```{admonition} Note$\qquad$Some verrrrrry long title spanning multiple lines to test dynamism and multi lines
---
class: note
---

$$
\begin{align}
\mathrm{SetConv} \left( \{(x^{c},y^{c})\}_{c=1}^{C} \right)(x) \left( \{(x^{c},y^{c})\}_{c=1}^{C} \right)(x) \left( \{(x^{c},y^{c})\}_{c=1}^{C} \right)(x)
&= \sum_{c=1}^{C} y^{(c)} w_{\theta} \left( x - x^{(c)} \right) \sum_{c=1}^{C} y^{(c)} w_{\theta} \left( x - x^{(c)} \right) \sum_{c=1}^{C} y^{(c)} w_{\theta} \left( x - x^{(c)} \right) \\
&= \left( y^{(c')} w_{\theta} \left( x - x^{(c')} \right) \right) + \sum_{c \neq c'}  y^{(c)} w_{\theta} \left( x - x^{(c)} \right) \\
&= 0 + \sum_{c \neq c'}  y^{(c)} w_{\theta} \left( x - x^{(c)} \right)
\end{align}
$$

```

## Long Equation in Hierarchical Admonitions



````{admonition} Note$\qquad$Some verrrrrry long title spanning multiple lines to test dynamism and multi lines
---
class: note
---


```{admonition} Warning$\qquad$Some verrrrrry long title spanning multiple lines to test dynamism and multi lines
---
class: warning
---

$$
\begin{align}
\mathrm{SetConv} \left( \{(x^{c},y^{c})\}_{c=1}^{C} \right)(x) \left( \{(x^{c},y^{c})\}_{c=1}^{C} \right)(x) \left( \{(x^{c},y^{c})\}_{c=1}^{C} \right)(x)
&= \sum_{c=1}^{C} y^{(c)} w_{\theta} \left( x - x^{(c)} \right) \sum_{c=1}^{C} y^{(c)} w_{\theta} \left( x - x^{(c)} \right) \sum_{c=1}^{C} y^{(c)} w_{\theta} \left( x - x^{(c)} \right)\\
&= \left( y^{(c')} w_{\theta} \left( x - x^{(c')} \right) \right) + \sum_{c \neq c'}  y^{(c)} w_{\theta} \left( x - x^{(c)} \right) \\
&= 0 + \sum_{c \neq c'}  y^{(c)} w_{\theta} \left( x - x^{(c)} \right)
\end{align}
$$

```

```{admonition} Warning$\qquad$With dropdown
---
class: warning, dropdown
---

$$
\begin{align}
\mathrm{SetConv} \left( \{(x^{c},y^{c})\}_{c=1}^{C} \right)(x) \left( \{(x^{c},y^{c})\}_{c=1}^{C} \right)(x) \left( \{(x^{c},y^{c})\}_{c=1}^{C} \right)(x)
&= \sum_{c=1}^{C} y^{(c)} w_{\theta} \left( x - x^{(c)} \right) \sum_{c=1}^{C} y^{(c)} w_{\theta} \left( x - x^{(c)} \right) \sum_{c=1}^{C} y^{(c)} w_{\theta} \left( x - x^{(c)} \right)\\
&= \left( y^{(c')} w_{\theta} \left( x - x^{(c')} \right) \right) + \sum_{c \neq c'}  y^{(c)} w_{\theta} \left( x - x^{(c)} \right) \\
&= 0 + \sum_{c \neq c'}  y^{(c)} w_{\theta} \left( x - x^{(c)} \right)
\end{align}
$$

```

````