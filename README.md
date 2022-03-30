## Construction of an arbitrage portfolio using a linear factor modele

* Our universe of stocks will be the CAC40, the french index.
* We first pick stocks from our universe, which will constitute our portfolio. For this, we will use a Long/Short strategy. <br>
* We then regress the excess return of the stocks versus the excess return of the market, which will be modeled by the CAC40
For each stock, we get : <br><br> <img src="https://latex.codecogs.com/svg.image?R_{i,t}&space;=&space;\alpha_{i}&space;&plus;&space;\beta_iR_{CAC,t}&space;&plus;&space;\epsilon_{i,t}">

* We then take the stock with the lowest alpha, and the one with the biggest alpha: our strategy consists in shorting the first one to finance the second one.
