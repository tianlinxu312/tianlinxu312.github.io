## Hello Hello

I am a final year PhD student of Statistics at London School of Economics. I'm jointly supervised by [Dr. Wicher Bergsma](https://www.lse.ac.uk/Statistics/People/Dr-Wicher-Bergsma) and [Prof. Beatrice Acciaio](http://beatrice-acciaio.net/). 
My research interests lie in deep generative models and computer vision.  

You can reach me at firstname.surname1@gmail.com

# Preprints
(\* indicates equal contributions. )

[Quantized Conditional COT-GAN for Video Prediction](https://arxiv.org/pdf/2106.05658.pdf) Xu T. & Acciaio B. (2021). Under review.  

<!--
- QCCOT-GAN is a conditional version of COT-GAN suitable for sequence prediction, further improved on the convergence results of Causal Optimal Transport by modifying the empirical measures via a specific type of quantization.
--> 

[SPATE-GAN: Improved Generative Modeling of Dynamic Spatio-Temporal Patterns with an Autoregressive Embedding Loss](https://arxiv.org/pdf/2109.15044.pdf) Klemmer K.\*, Xu T.\*, Acciaio B. and Neill D. (2021). Under review. 
<!--
- SPATE-GAN is a novel loss objective combined with COT-GAN based on an autoregressive embedding to reinforce the learning of spatio-temporal dynamics. SPATE (spatio-temporal association) is devised as a new metric measuring spatio-temporal autocorrelation by using the deviance of observations from their expected values.
--> 
**Code**: [PyTorch implementation](https://github.com/konstantinklemmer/spate-gan)

[Double Generative Adversarial Networks for Conditional Independence Testing.](https://arxiv.org/pdf/2006.02615.pdf) Shi C., Xu T., Bergsma W, & Li L. (2021+). Journal of Machine Learning Research, accepted.
<!--
- The contributions of this paper involves 1. we construct a doubly-robust test statistic which offers additional protections against potential misspecification of the conditional distributions, 2. we propose a double GAN-based inference procedure for the conditional independence testing problem.
--> 
**Code**: [TensorFlow 2.x implementation](https://github.com/tianlinxu312/dgcit)

# Publications

[Generative modeling of spatio-temporal weather patterns with extreme event conditioning](https://arxiv.org/pdf/2104.12469.pdf). Klemmer K., Saha S., Kahl M., Xu T., Zhu XX. (2021). AIMOCC workshop, ICLR.

[COT-GAN: Generating Sequential Data via Causal Optimal Transport.](https://papers.nips.cc/paper/2020/file/641d77dd5271fca28764612a028d9c8e-Paper.pdf) Xu T., Wenliang L., Munn M, & Acciaio B. (2020). Conference on Neural Information Processing Systems(NeurIPS).
<!--
- COT-GAN proposed an objective function, formulated using ideas from Causal Optimal Transport (COT), which naturally encodes an additional temporal causality constraint in order to better learn time dependent data distributions. It is generic for most applications of sequential nature, e.g., video, music, speech, stock prices, etc.  
--> 
**Code**: [TensorFlow 2.x implementation](https://github.com/tianlinxu312/cot-gan) and [PyTorch implementation](https://github.com/tianlinxu312/cot-gan-pytorch)

[Variational f-divergence Minimization.](https://arxiv.org/pdf/1907.11891.pdf) Zhang M., Bird T., Habib R., Xu T., & Barber D. (2019). Conference on Neural Information Processing Systems(NeurIPS) workshop.
<!--
- Probabilistic models are often trained by maximum likelihood, which corresponds to minimizing a specific f-divergence (forward KL divergence) between the model and data distribution. The contribution of this paper is the derivation of a generic variational upper bound that can be applied to train a large class of latent variable models using any f-divergence.
--> 

# Volunteer work in ML community

- Volunteer poster mentor for WiML 2020 workshop at NeurIPS
- Super volunteer for the WiML 2021 workshop at NeurIPS
