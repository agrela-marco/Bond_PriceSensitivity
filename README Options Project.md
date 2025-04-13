Task 2:
The sensitivity analysis of a put option using the binomial pricing model above highlights signifant numerical trends in option pricing. When the risk-free (Rf) increases from 0.01 to 0.10, the put price decreases from approximately 14.2 to 5.8, confirming that higher discount rates reduce the present value of the strike price making put options less attractive. As volatility (Sigma) rises from 0.01 to 0.50, the put price increases sharply from about 1.2 to 29.7 demonstrating that higher uncertainty raises the likelihood of deep in-the-money scenarios increasing option value. The number of binomial periods(m) shows rapid convergence with the put price stabilising around 6.5 after 200 periods indicating that further refinements beyond this threshold add minimal impact. For the initial stock price (S0), as it rises from 50 to 150, the put price declines from approximately 35.2 to nearly 0 highlighting that when S0 is much lower than the strike price, the put option is deep in-the-money, whereas when S0 approaches or exceeds the strike price, the option loses its intrinsic value. These nurmerical results align with theoretical expectations: higher Rf lowers put values due to discounting, higher sigma significantly increases option value, larger m stabilizes pricing after a certain limit and higher S0 reduces put prices as the option moves out-of-the-moeny. This analysis reinforces key option pricing principles and their quantitative impact.

Task 3 :Explain graphically and analyse how the put-call parity works 
Section A) First visualisation:
This graph visually represents the payoffs of:

Call Option Payoff (dashed blue line)

A call option is worthless when the stock price is below the strike price ((K)) but increases as the stock price rises. Put Option Payoff (dotted orange line)

A put option is valuable when the stock price is below (K) (as it allows selling at a higher strike price) but is worthless above (K). Put-Call Parity Equation (solid black line)

This line represents the right-hand side of the put-call parity equation ( P + S - PV(K) ), which should align with the call price. Key Takeaway: The fact that the put-call parity line crosses across the call option payoff demonstrates that the put-call parity equation appropriately represents the call's value.

Second Visualisation:
This bar chart compares:

Call price from the binomial model
Call price computed via put-call parity
If put-call parity holds perfectly, both values should be nearly identical.
Conclusion:

The parity relationship ensures that call and put options are priced appropriately in the market.
Any deviation from this relationship indicates an arbitrage opportunity in which equal_weighted_index_dfrs could profit from mispricing.
The graphs visually indicate that the put-call parity formula is valid over a range of stock values.
