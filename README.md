# Yield curve principal component analysis with Eikon Data API

This python model performs the PCA decomposition of a defined list of rates instruments (e.g. treasuries or IR swaps) using Eikon Data API, Additionally this model calculates the mean reversion on a curve trade as well as optimal holding period. [Full article is provided here](https://developers.refinitiv.com/article/yield-curve-principal-component-analysis-eikon-data-api).

#### Pre-requisites:

Refinitiv Eikon or Refinitiv Workspace with access to Eikon Data APIs

<b>Required Python Packages:</b> eikon, pandas, cufflinks, sklearn, scipy, numpy, random
