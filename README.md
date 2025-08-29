# Introduction

In this study, I implemented five most used mab algorithms on the [movielens100k dataset](https://grouplens.org/datasets/movielens/100k/). 

1. epsilone-greedy
2. UCB
3. Thompson Sampling
4. Contextual Thompson sampling
5. LinUCB

I computed thier average reward after online training on training data and precision@k on test data. Both Contextual Thompson Sampling and LinUCB outperformed significantly non-contextual methods: epsilon-greedy, UCB, and Thompson Sampling.

In the table below I compared the precision@5 of these methods.


|  method  | precision@5 |
|----------|-------------|
| e-greedy |    0.027    |
|   UCB    |    0.115    |
|   TS     |    0.180    |
|  LinUCB  |    0.560    |
|    CTS   |    0.5216   |
