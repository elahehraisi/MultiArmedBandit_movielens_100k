# Introduction

In this study, I implemented five most used mab algorithms on the [movielens100k dataset](https://grouplens.org/datasets/movielens/100k/). 

1. [epsilone-greedy](https://github.com/elahehraisi/MultiArmedBandit_movielens_100k/blob/main/e-greedy.ipynb)
2. [UCB](https://github.com/elahehraisi/MultiArmedBandit_movielens_100k/blob/main/UCB.ipynb)
3. [Thompson Sampling](https://github.com/elahehraisi/MultiArmedBandit_movielens_100k/blob/main/Thompson_Sampling.ipynb)
4. [Contextual Thompson sampling](https://github.com/elahehraisi/MultiArmedBandit_movielens_100k/blob/main/Contextual%20Thompson%20Sampling.ipynb)
5. [LinUCB](https://github.com/elahehraisi/MultiArmedBandit_movielens_100k/blob/main/linUCB.ipynb)

I computed thier average reward after online training on training data and precision@k on test data. Both Contextual Thompson Sampling and LinUCB outperformed significantly non-contextual methods: epsilon-greedy, UCB, and Thompson Sampling.

In the table below I compared the precision@5 of these methods.


|  method  | precision@5 |
|----------|-------------|
| e-greedy |    0.027    |
|   UCB    |    0.115    |
|   TS     |    0.180    |
|  LinUCB  |    0.560    |
|    CTS   |    0.5216   |
