# FinancialDerivatives
Description of Option Theory

Options

## Black Scholes

$$
\begin{aligned}
    \frac{\partial V}{\partial t} + \frac{1}{2}\sigma^2 S^2 \frac{\partial^2 V}{\partial S^2} + rS \frac{\partial V}{\partial S} - r V = 0 
\end{aligned}
$$

### Geometric brownian motion

$$
\begin{aligned}
    \frac{dS}{S} & = \mu dt + \sigma dW
\end{aligned}
$$

### Call option

$$
\begin{aligned}
    C & = S_t N(d_1) - K e^{-rt} N(d_2) \\
    d_1 & = \frac{\log{\frac{S_t}{K}} + (r+\frac{\sigma^2}{2})t}{\sigma \sqrt{t}} \\
    d_2 & = d_1 - \sigma \sqrt{t}
\end{aligned}
$$