# derivativeCVA

The Valuation of Financial Derivatives Subject to Counterparty Risk and Credit Value Adjustment

ABSTRACT

This article presents a generic model for pricing financial derivatives subject to counterparty credit risk. Both unilateral and bilateral types of credit risks are considered. Our study shows that credit risk should be modeled as American style options in most cases, which require a backward induction valuation. To correct a common mistake in the literature, we emphasize that the market value of a defaultable derivative is actually a risky value rather than a risk-free value. Credit value adjustment (CVA) is also elaborated. A practical framework is developed for pricing defaultable derivatives and calculating their CVAs at a portfolio level.

Conclusion
This article presents a theory for pricing defaultable financial derivatives and their CVAs. First, we want to indicate that the market value of a defaultable derivative is actually a risky value rather than a risk-free value. In fact, in applying the upfront CVA, we already converted the market value of a defaultable derivative from the risk-free value to the risky value.
For completeness, our theoretical study covers various cases. We find that the valuation of defaultable derivatives and their CVAs, in most situations, has a backward recursive nature and requires a backward induction valuation. An intuitive explanation is that two counterparties implicitly sell each other an option to default when entering into a defaultable transaction. If we assume that a default may occur at any time, the default options are American style options. If we assume that a default may only happen on the payment dates, the default options are either European options or Bermudan options. Both Bermudan and American options require backward induction valuations. 
Based on our theory, we propose a novel cash-flow-based practical framework for calculating the bilateral risky value and bilateral CVA at the counterparty portfolio level. This framework can easily incorporate various credit mitigation techniques, such as netting agreements and margin agreements, and can capture wrong/right way risk. Numerical results show that these credit mitigation techniques and wrong/right way risk have significant impacts on CVA. 

Reference
Duffie, Darrell, and Ming Huang, 1996, Swap rates and credit quality, Journal of Finance, 51, 921-949.

Duffie, Darrell, and Kenneth J. Singleton, 1999, Modeling term structure of defaultable bonds, Review of Financial Studies, 12, 687-720.

FinPricing, 2019, Market data provider, https://finpricing.com/lib/IrSwap.html

Gregory, Jon, 2009, Being two-faced over counterparty credit risk, RISK, 22, 86-90.

Jarrow, Robert A., and Stuart M. Turnbull, 1995, Pricing derivatives on financial securities subject to credit risk, Journal of Finance, 50, 53-85.

Longstaff, Francis A., and Eduardo S. Schwartz, 1995, A simple approach to valuing risky fixed and floating debt, Journal of Finance, 50, 789-819.

Longstaff, Francis A., and Eduardo S. Schwartz, 2001, Valuing American options by simulation: a simple least-squares approach, The Review of Financial Studies, 14 (1), 113-147.

Madian, Dilip.B., and Unal, Haluk, 1998, Pricing the risks of default, Review of Derivatives Research, 2, 121-160.

Merton, Robert C., 1974, On the pricing of corporate debt: the risk structure of interest rates, Journal of Finance, 29, 449-470.

Pykhtin, Michael, and Steven Zhu, 2007, A guide to modeling counterparty credit risk, GARP Risk Review, July/August, 16-22.

Xiao, Tim, 2015, An accurate solution for credit value adjustment (CVA) and wrong way risk, Journal of Fixed Income, Summer 2015, 25(1), 84-95.

Xiao, T., 2017, “A New Model for Pricing Collateralized OTC Derivatives.” Journal of Derivatives, 24(4), 8-20.
