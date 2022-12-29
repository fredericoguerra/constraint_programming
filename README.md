## The 0/1 Knapsack Problem

Given a set $I$ of items, each item has weight $w_{i}$ and estimated profit $p_{i}$. The problem consists of selecting a subset of total items with maximum profit such that the summation of the weights of the selected items does not exceed the knapsack capacity $c$.

### Problem Formulation

#### Data

$n$ Number of items in $I$ <br/>
$c$ Knapsack capacity <br/>
$p_{i}$ Profit of item $i$ <br/>
$w_{i}$ Weight of item $i$

#### Decision variables

$x_{i}$ Binary variable representing the assignement of item $i$ into the knapsack. 1 if selected, 0 otherwise.

#### Objective Function

$$ \max \left( \sum_{i \in I} {p_{i} {x_{i}}} \right)$$

##### Subject to:

$$ \sum_{i = 1}^{n} {w_{i} * {x_{i}}} \le c \qquad i \in n $$ <br/>

$$ x_{i} \in \\{ 0,1 \\} $$ <br/>

## Diet Problem

## House Building Problem

## Sudoku Solver
