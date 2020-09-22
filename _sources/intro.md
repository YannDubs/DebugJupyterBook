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

```{warning}

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



`````{note}

```{admonition} Hierarchical
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

```{admonition} With dropdown
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


```python
print("some very long code cell to show that it has a nice scrollbar. It would be Nice to have the same for latex cells when they are too long.")
```

`````

## Code works
