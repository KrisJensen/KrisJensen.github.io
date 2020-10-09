---
layout: archive
title: ""
permalink: /recommendations/
author_profile: true
redirect_from:
  - /recommendations
---

{% include base_path %}

<head>
<style>
a.rec:link {
  color: #003CA4;
  background-color: transparent;
  text-decoration: underline;
  font-weight:bold;
}
a.rec:visited {
  color: #003CA4;
  background-color: transparent;
  text-decoration: underline;
  font-weight:bold;
}
</style>
</head>

{: style="text-align: justify" }
The world wide web is full of excellent resources for learning more about neuroscience, machine learning, and many other interesting topics.
Unfortunately it's not always easy to know where to look.
Here is a short list of talks, tutorials and papers that I've found particularly insightful over the course of my own studies, and I would highly recommend anyone to have a look if they have time.

## Talks

{: style="text-align: justify" }
<a class="rec" href="https://www.youtube.com/watch?v=E29uad2FUVE&t=280s">About a biological ring attractor network</a><br>
<b>Vivek Jayaraman (2020)</b><br>
The human brain has ~100 billion neurons, the mouse brain ~100 million, and the fly brain just 250,000. However, we're increasingly beginning to understand how function and cognition arises from these 250,000 fly neurons, and this talk gives an awesome overview of how this understanding emerges in the context of the <i>Drosophila</i> navigation system.

{: style="text-align: justify" }
<a class="rec" href="https://bcs.mit.edu/news-events/media/seminar-earl-miller-working-memory-20">Working memory 2.0</a><br>
<b>Earl Miller (2020)</b><br>
As someone who does not work on working memory, this seminar was an awesome introduction to decades of work on how prefrontal cortex helps solve working memory tasks as well as a cool appetizer for new work looking at how the activity of neurons in PFC interact with brain-wide signals and oscillations.

{: style="text-align: justify" }
<a class="rec" href="http://online.kitp.ucsb.edu/online/snav18/stensmyr/">Where the wild things are - the biology of non-commensal Drosophila melanogaster in Southern Africa</a><br>
<b>Marcus Stensmyr (2018)</b><br>
A thrilling tale of an impressive quest to discover why <i>Drosophila melanogaster</i> loves oranges despite oranges not being native to Southern Africa where the wild <i>Drosophilae</i> live.

{: style="text-align: justify" }
<a class="rec" href="https://www.youtube.com/watch?v=55Wse17mXwQ&t=2851s">Human planning in large state spaces</a><br>
<b>Wei Ji Ma (2020)</b><br>
While deep reinforcemnt learning have given us a way to unlock previously unprecedented levels of performance in games such as chess and go with artificial agents, relativeely litte is still known about how humans approach such problems. Wei Ji Ma adresses this problem with custom-made apps and huge data sets, and in additon to cool conclusions it also provides an refreshing new approach to neuroscience in the 21st century.

## Tutorials

{: style="text-align: justify" }
<a class="rec" href="https://www.neuromatchacademy.org/syllabus">Neuromatch Academy</a><br>
<b>Neuromatch organizers and volunteers (2020)</b><br>
Arguably the best resource available for learning computational neuroscience.
Three weeks worth of material starting from simple principles of model selection and model fitting and moving to tutorials on dynamical systems and control, principles of deep learning & machine learning as applied to neuroscience, and much much more.

{: style="text-align: justify" }
<a class="rec" href="http://statisticalml.stat.columbia.edu/event/tutorials-on-reinforcement-learning/">The Mathematical Foundations of Policy Gradient Methods</a><br>
<b>Sham Kakade (2020)</b><br>
This tutorial provides a really useful overview of the policy gradient methods that underlie much of modern RL, and Sham Kakade does an excellent job explaining things in a way that provides intuition to accompany the equations.

## Papers

{: style="text-align: justify" }
<a class="rec" href="https://www.nature.com/articles/s41593-018-0147-8#Abs1">Prefrontal cortex as a meta-reinforcement learning system</a><br>
<b>Jane Wang, Zeb Kurth-Nelson et al. (2018)</b><br>
Deep reinforcement learning is becoming increasingly important in both AI and neuroscience, and I've joined the bandwagon of people convinced that it will be one of the keys to understanding the human brain. This paper shows how a plethora of observations in biological agents can be explain by teaching PFC to implement task-specific reinforcement learning algorithms in its internal dynamics via a slower `meta-reinforcement learning' loop across tasks.

{: style="text-align: justify" }
<a class="rec" href="http://jmlr.org/papers/volume15/srivastava14b/srivastava14b.pdf">Multimodal Learning with Deep Boltzmann Machines</a><br>
<b>Nitish Srivastava and Ruslan Salakhutdinov (2014)</b><br>
I'm convinced that multisensory alignment will turn out to be important for organizing neural circuits in early development, and this is a cool paper illustrating how two sensory modalities can be used to generate a powerful inference model in a machine learning model.

{: style="text-align: justify" }
<a class="rec" href="https://www.nature.com/articles/s41586-019-1767-1">Generation of stable heading representations in diverse visual scenes</a><br>
<b>Sung Soo Kim et al. (2019)</b><br>
This paper uses 2-photon imaging to investigate how visual scenes are mapped onto head direction circuits in <i>Drosophila</i> and includes both awesome experimental work by Sun Soo Kim and cool modelling work by Ann Hermundstad.

{: style="text-align: justify" }
<a class="rec" href="https://www.nature.com/articles/nn.3650">A temporal basis for predicting the sensory consequences of motor commands in an electric fish</a><br>
<b>Ann Kennedy et al. (2014)</b><br>
Electric fish sense the weak electric signals from their prey but also produce their own comparably large electric discharges. In this awesome paper, Ann Kennedy shows how the fish learns to cancel the sensory effect of its self-generated electric discharge using a set of temporal 'basis functions' in the form of the activity of the so-called 'granule cells'.

{: style="text-align: justify" }
<a class="rec" href="https://www.nature.com/articles/s41593-019-0534-9">Neural circuits for evidence accumulation and decision making in larval zebrafish</a><br>
<b>Armin Bahl and Florian Engert (2019)</b><br>
Evidence accumulation, decision making and sensory-driven motion are ubiquitous across organisms, and in this awesome work, Armin Bahl uses lightsheet imaging in thee zebrafish brain to elucidate how these algorithms are implemented at a mechanistic level in the context of the fish optomotor response.

{: style="text-align: justify" }
<a class="rec" href="https://www.nature.com/articles/s41593-019-0460-x">The intrinsic attractor manifold and population dynamics of a canonical cognitive circuit across waking and sleep</a><br>
<b>Rishidev Chaudhuri et al. (2019)</b><br>
This paper compares the head-direction circuit in mice that are awake and asleep, using 'spline parameterization for unsupervised decoding' (SPUD) to analyze the consistent ring topology.
This work has inspired a lot of our recent work on unsupervised learning in non-Euclidean spaces using Bayesian non-parametrics.

{: style="text-align: justify" }
<a class="rec" href="https://science.sciencemag.org/content/351/6268/84">Rationally engineered Cas9 nucleases with improved specificity</a><br>
<b>Ian Slaymaker et al. (2016)</b><br>
A cool example of how we can use an understanding of chemistry and protein structure to alter the functional properties of enzymes - in this case the Cas9 protein with use cases spanning basic science and medicine.
