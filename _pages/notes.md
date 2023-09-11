---
layout: archive
title: "Miscellaneous notes"
permalink: /notes/
author_profile: true
redirect_from:
  - /notes
---

{% include base_path %}

<head>
<style>
a.blog:link {
  color: #003CA4;
  background-color: transparent;
  text-decoration: underline;
  font-weight:bold;
}
a.blog:visited {
  color: #003CA4;
  background-color: transparent;
  text-decoration: underline;
  font-weight:bold;
}
</style>
</head>

This page contains a collection of notes on various topics that are more or less related to computational neuroscience and machine learning.
Some of these can be considered 'original research' in a preliminary or non-publishable form, and some of them are simply notes and summaries of existing research.

<p style="padding-bottom:-12px; margin-bottom:-12px; padding-top:8px; margin-top:8px">
<a style="font-size:1.3em" class="blog" href="http://KrisJensen.github.io/files/notes/svgp.pdf">
Stochastic variational Gaussian processes regression
</a>
</p>

{: style="text-align: justify" }
In GP regression, we are often limited by the cubic complexity of inference and hyperparameter optimization.
Several approaches have therefore been developed in order to mitigate this cost and scale GP regression to larger datasets.
A popular approach is the variational 'SVGP' approach developed by James Hensman and colleagues.
In this note, we provide a brief overview of the mathematical underpinnings of this method.

<p style="padding-bottom:-12px; margin-bottom:-12px; padding-top:8px; margin-top:8px">
<a style="font-size:1.3em" class="blog" href="http://KrisJensen.github.io/files/notes/manifold_ARs.pdf">
Autoregressive priors on non-Euclidean manifolds
</a>
</p>

{: style="text-align: justify" }
In Jensen et al. (2020), we developed a set of latent variable models with non-Euclidean latent spaces.
One shortcoming of this approach compared to standard Eucliean methods such as GPFA or LFADS is that it is non-trivial to build in inductive biases of smoothness or continuity across time.
At Cosyne 2021, we presented a method to overcome this challenge based on autoregressive processes on non-Euclidean manifolds, which we also put on bioRxiv as a short note (Jensen, Liu & Kao et al., 2022).
Here, we provide a more mathematical description of the approach as well as a generalization to higher-order processes in contrast to the 'Brownian' process presented at Cosyne.

<p style="padding-bottom:-12px; margin-bottom:-12px; padding-top:8px; margin-top:8px">
<a style="font-size:1.3em" class="blog" href="http://KrisJensen.github.io/files/notes/pg.pdf">
Policy gradient methods
</a>
</p>

{: style="text-align: justify" }
Policy gradient methods are commonly used to train deep neural networks in a reinforcement learning setting, and we also use this approach to train our RL agents in Jensen et al. (2023).
In this note, we provide a brief overview of the reinforcement learning problem setting and then derive some simple policy gradient methods including REINFORCE and actor critic reinforcement learning.

<p style="padding-bottom:-12px; margin-bottom:-12px; padding-top:8px; margin-top:8px">
<a style="font-size:1.3em" class="blog" href="http://KrisJensen.github.io/files/notes/supervised_mgplvm.pdf">
Supervised manifold GPLVMs
</a>
</p>

{: style="text-align: justify" }
In Jensen et al. (2020), we developed a new method for latent variable modeling on non-Euclidean manifolds.
However, another common problem is to perform _supervised learning_ in such non-Euclidean spaces.
This is desirable e.g. if we want to fit a model to predict head direction from neural data and then test the model during periods without labelled data, such as during sleep or mental processing.
In this note, we build on our mGPLVM work to develop a GP-based model for supervised learning from neural data in non-Euclidean settings and demonstrate its utility over common methods used in the neuroscience literature.

<!-- <p style="padding-bottom:-12px; margin-bottom:-12px; padding-top:8px; margin-top:8px">
<a style="font-size:1.3em" class="blog" href="http://KrisJensen.github.io/files/blog_stability.pdf">
An algorithmic hypothesis of differential neural stability in the brain
</a>
</p>

{: style="text-align: justify" }
There is a long-running debate in the neuroscience community about whether task-specific neural representations are stable after task learning or whether they drift in some null-space that does not affect task performance, and there is a large body of experimental support for both hypotheses in different brain regions and contexts.
In this short note, we consider how differences in neural stability between brain regions may reflect different algorithmic approaches to addressing the challenge of continual learning, drawing inspiration from both the machine learning literature on continual learning and the neuroscience literature on neural stability and memory consolidation. -->

<!-- <p style="padding-bottom:-12px; margin-bottom:-12px; padding-top:8px; margin-top:8px">
<a style="font-size:1.3em" class="blog" href="http://KrisJensen.github.io/files/blog_stability.pdf">
GPLVMs for neuroscience
</a>
</p>

{: style="text-align: justify" }
Many neuroscience LVMs can be considered GPLVMs. We provide an overview here. -->
