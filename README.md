# Long-Short-Strategy

This repository contains an implementation of a Long-Short strategy on 250 most liquid Japanese equities using the LightGBM algorithm. It yielded yielded an average annual return of 8% with a maximum drawdown of 11% .The strategy enters long and short positions for the 25 assets with the highest positive and lowest negative predicted returns and trades every day, as long as there are at least 15 candidates on either side. 

The algorithm was written in Python and used the Zipline and Pyfolio modules. 
