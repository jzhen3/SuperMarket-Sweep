# SuperMarket-Sweep
Optimally filling up baskets with items for a team of 2 shopper contestants.

Supermarket Sweep was an American television game show that first ran in the 1960s. It was
later brought back in the 1990s. And it was brought back again in the early 2000s. There are even
plans to bring it back in the next few years. The concept of this game was simple: contestants had
a specified amount of time to run through a supermarket and pick up items; upon returning to the
starting point, they would then receive a cash prize based on the total monetary value of the goods
they brought back.

For most contestants on the show, strategies were simple. Some would run straight for the most
expensive items; others would choose a path that allowed them to collect as many items as possible,
regardless of values. 

The project models the problem of optimally filling up two baskets for a team of two contestants using Gurobi Solver.

A organized data file contains information about 56 different grocery
items. This information includes each item’s name, monetary value, and X and Y coordinates

 team of two shoppers has a 60-second window of time to collect items and return to the
start point location. They begin at a specified start point location in the store, and must
return to that point before the time limit is up.

And each shopper only can only include 10 items in their respective basket.
within the store aisles. each shopper moves at a speed of 10 feet per second, and takes 2 seconds to
pick up an item and place it in their cart. And each item can only be picked up once.

The goal of the team is to maximize the total value of the items they bring back.
