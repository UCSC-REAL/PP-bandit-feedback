# PP-bandit-feedback
This repository accompanies the paper Preformative Prediction with Bandit Feedback: Learning through Reparameterization, accepted by ICML 2024 -- [Yatong Chen](https://github.com/YatongChen/), [Wei Tang](https://wtang.org/), [Chien-Ju Ho](https://chienjuho.com/), [Yang Liu](https://yliuu.com/).

In particular, this Jupyter notebook reproduces the experimental results demonstrate in Figure 4 - 6 in Appendix H.  

# Abstract: 

Performative prediction, as introduced by \citeauthor{perdomo2020performative}, is a framework for studying social prediction in which the data distribution itself changes in response to the deployment of a model. 
Existing work in this field usually hinges on three assumptions that are easily violated in practice: that the performative risk is convex over the deployed model, that the mapping from the model to the data distribution is known to the model designer in advance, and the first-order information of the performative risk is available. 
In this paper, we initiate the study of performative prediction problems that do not require these assumptions.
Specifically, we develop a {\em reparameterization} framework that reparametrizes the performative prediction objective as a function of the induced data distribution. We then develop a two-level zeroth-order optimization procedure, where the first level performs iterative optimization on the distribution parameter space, and the second level learns the model that induces a particular target distribution 
% parameter 
at each iteration. 
Under mild conditions, this reparameterization allows us to transform the non-convex objective into a convex one and achieve provable regret guarantees. 
In particular, we provide a regret bound that is sublinear in the total number of performative samples taken and is only polynomial in the dimension of the model parameter.


# Citation

If you want to cite our paper, please cite the following format:

```
@article{chen2024performative,
  title={Performative Prediction with Bandit Feedback: Learning through Reparameterization},
  author={Chen, Yatong and Tang, Wei and Ho, Chien-Ju and Liu, Yang},
  booktitle={International Conference on Machine Learning},
  organization={PMLR}
  year={2024}
}
```
