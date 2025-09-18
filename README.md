# Automaton

_An interesting cellular automaton_

## What is this?

This JavaScript module implements a cellular automaton in which each cell has a value between 0 and 1. On each iteration, a new value is calculated by $\sin(\pi|K|\sum_{i=0}^7 K_i A_i)$, where $K_0 \ldots K_7$ are a series of *kernel weights* and $A_0 \ldots A_7$ are the values of the adjacent cells. This new value is then averaged with the previous value according to a weighting factor.

This automaton displays a variety of interesting patterns and behaviors depending on the choice of kernel weights and the weighting factor.
