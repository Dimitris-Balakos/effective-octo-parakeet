# efficient_frontier

In this repository I posted a short code enabling the user to import data of stock prices from yahoo_api and then construct the efficient 
  frontier of those stocks using different weighting schemes through an iterative process. I have added an input() method which allows the user 
  to directly ask for the specific tickers' prices and to define the specified time periods. The iteration which produces the weights is currently
  set to 1000. Application of upwards of 50000 iterations renders the time needed for completion of the process quite long. 
