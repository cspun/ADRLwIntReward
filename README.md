# Portfolio Optimization with Learned Intrinsic Rewards

This repository provides the full codes and supplementary materials for the paper: "Autoregressive DRL with Learned Intrinsic Rewards for Portfolio Optimisation"

If you find any information from this repo helpful, please cite our work:
```
@inproceedings{10.1145/3677052.3698670,
author = {Lim, Magdalene Hui Qi and Lesmana, Nixie S and Pun, Chi Seng},
title = {Autoregressive DRL with Learned Intrinsic Rewards for Portfolio Optimisation},
year = {2024},
isbn = {9798400710810},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3677052.3698670},
doi = {10.1145/3677052.3698670},
abstract = {The recent success of deep reinforcement learning (DRL) in sequential learning tasks involving high-dimensional state spaces has sparked the interest of the finance research community. In portfolio optimization, mainstream research often overlooks the important question of optimal reward design, in favor of algorithm design. In this work, we focus on the former question, exploring different external reward functions in combination with reward-transforming internal systems. We put forth a novel strategy that combines two DRL frameworks: learned intrinsic rewards and autoregressive architectures, allowing individual intrinsic rewards to be learned for each dimension of the action space. We back-test each strategy using real financial data of 30 Dow Jones stocks over multiple years, and demonstrate that learned individual intrinsic rewards lead to the best performance that is robust across different training objectives.},
booktitle = {Proceedings of the 5th ACM International Conference on AI in Finance},
pages = {353–360},
numpages = {8},
keywords = {Autoregressive model, Empirical finance, Intrinsic reward, Markov decision process, Portfolio optimization, Reinforcement learning},
location = {Brooklyn, NY, USA},
series = {ICAIF '24}
}
```



