# Bond-Yield-Bootstrapper
Generate the yield of given bonds, and linearly or cubic interpolate the yield when the maturity &amp; market_price pair is not given.

Simply run the code, and there are some tests included.

Calculating the yields based on the bond:
  Give the necessary parameters with the same structure given in the first part (initial parameters)
  Create a class Bond, and call the method calculate_yield() to generate the yield.

Calculating the yield when the market price is missing:
  Give plenty pairs of data: (maturity in year, market price, frequency) to the Bootstrapper class.
  Generate the YieldCurve class by calling bootstrap, and call rate(missing maturity in year) to estimate the yield.
