Client: Radmilo Racic, [IMC (Netherlands)](IMC_(Netherlands) "wikilink")
<Radmilo.racic@imc.nl>

Algorithmic trading is an essential part of today’s financial markets,
but releasing an algorithm out in the wild certainly comes with its own
hassles. One of the challenges associated with carrying a trading
algorithm into production is the evaluation of its performance,
preferably under different market conditions, and using different
parametrizations of the algorithm. This process, called back-testing,
allows one to understand the characteristics of a trading algorithm
before it hits the markets. In this project, the aim is to create a
game, where users will submit their algorithms to be evaluated under a
back-testing framework. An algorithm will pick which products it is
interested in, and the framework will supply the historical data for
those products. The algorithm can then give trading decisions, which
will be evaluated in order to characterize the algorithm.