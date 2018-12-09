## Format

### 1. Author/Paper

Author: Vladimir V. V’yugin
Title: Online Aggregation of Unbounded Signed Losses Using Shifting Experts

### 2. Abstract

For the decision theoretic online (DTOL) setting, we consider methods to construct algorithms
that suffer loss not much more than of any sequence of experts distributed along
a time interval (shifting experts setting). We present a modified version of the method
of Mixing Past Posteriors which uses as basic algorithm AdaHedge with adaptive learning
rate. Due to this, we combine the advantages of both algorithms: regret bounds are valid
in the case of signed unbounded losses of the experts, also, we use the shifting regret which
is a more optimal characteristic of the algorithm. All results are obtained in the adversarial
setting – no assumptions are made about the nature of data source.
We present results of numerical experiments for the case where losses of the experts
cannot be bounded in advance.



### Notes

- **Decision-theoretic online learning (DTOL)** is a framework to capture learning problems that proceed
  in rounds.
- **AdaHedge**: adapts to the difficulty of the learning problem: in the worst case it still guarantees optimal performance, but on easy instances it achieves much smaller regret. Proposed by [E.Tim et al., 2011](https://arxiv.org/pdf/1110.6416.pdf)
- **Shifting experts setting**: please refer to [the lecture material](https://www.cs.huji.ac.il/~shais/Lecture5.pdf)

### 3. Problem Setting



### 4. Proposal

Mixing Past Posteriors (MPP) with AdaHedge which uses adaptive learning rate.

### 5. Experiments

Data source: https://www.finam.ru/

Results format: To be closer to financial terminology, they represent results in terms of incomes (gains) instead of losses

Experiments:

 	1. Zero-Sum game for US1.GLW stock from the datasource website
 	2. Seven Expert strategies are represented by daily incomes of Universal Algorithmic Trading strategy which operates for each of these stocks separately

### 6. Result

![figure3](https://github.com/Rowing0914/conformal_prediction/blob/master/notes/Online_Aggregation_of_Unbounded_Signed_Losses_Using/images/figure3.PNG)

![figure4](https://github.com/Rowing0914/conformal_prediction/blob/master/notes/Online_Aggregation_of_Unbounded_Signed_Losses_Using/images/figure4.PNG)

![figure5](https://github.com/Rowing0914/conformal_prediction/blob/master/notes/Online_Aggregation_of_Unbounded_Signed_Losses_Using/images/figure5.PNG)

### 7. Conclusion

Not stated....

