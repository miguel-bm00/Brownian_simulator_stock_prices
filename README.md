Script that simulates possible paths of the movement of a portfolio or stock in a given period.
Takes into account expected return, volatility, change in volatility and different returns distributions like T-student trying to solve fat tails in investment returns.
This code is inspired in:  https://www.quantstart.com/articles/geometric-brownian-motion-simulation-with-python/

To run this program use the following command. Note that most of the flags could be ommited, resulting in default values.

    python Brownian_simulator_v2.py --num-paths=10 --random-seed=33 --start-date='2013-01-01' --end-date='2022-07-31' --output-dir=simulaciones_brownian --symbol-length=5 --init-price=100.0 --mu=0.065 --sigma=0.09 --sigma_prime=0.75 --pareto-shape=1.5
