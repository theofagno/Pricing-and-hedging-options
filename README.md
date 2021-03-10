# Pricing-and-hedging-options

This first-year Data Science Master academic project aims to explore some mathematical financial theories and the use of Machine Learning to cope with computational finance problems. 
It is supported by the University of Lille and the Ecole Centrale de Lille.

Mathematical settings for financial market modeling are at the basis of this study, as they are for the pricing and covering options problem.

Here, this financial issue is explored in two major ways. 

From the scope of mathematic first, by studying Black-Scholes (B-S) discrete and continuous models. It gives us analytical solutions thanks to Itô's stochastic calculus methods, but under constraining hypothesis on the underlying market rules.

Then, the role of Deep Neural Networks (DNNs) naturally comes up. DNNs and their growing computational power can be efficiently implemented to simulate the stochastic pricing equation at the very beginning of B-S work. They have the advantage of not requiring market hypothesis as strong as the B-S resolution ones, and their needed input data is massive and available. More, they can easily handle non-observable parameters such as the volatility which is at the heart of the B-S equation. Implementations and optimizations of option pricing and volatility estimating DNNs are presented.
