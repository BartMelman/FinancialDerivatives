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

### Volatility Smile

[Description](https://www.investopedia.com/terms/v/volatilitysmile.asp)

The volatility smile is a graph of the strike price versus the implied volatility. The options tend to have a higher implied volatility for options which are further in- or out-of-the-money. The lowest implied volatility is for at-the-money options.

Not all options have a volatility smile. More near-term equity and currency options.

### Volatility Skew

[Description](https://www.investopedia.com/terms/v/volatility-skew.asp)

The volatility skew is the assymetric relationship between the strike price and implied volatility. It is a result of an assymmetric supply and demand. Fund managers are willing to overpay for downward striked options on stocks. E.g. downside protection is more important than upside speculation. Consequently, the shape is referred to as a 'smirk'.

### Put-Call Parity

$$
\begin{aligned}
    C(t) - P(t) = S(t) - e^{-rT}K
\end{aligned}
$$
