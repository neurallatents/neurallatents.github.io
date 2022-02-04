<!-- <div style="margin-bottom:1em"> -->
<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/o7dvFLHb5AY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->
<!-- </div> -->
## Overview

Advances in neural recording present increasing opportunities to study neural activity in unprecedented detail. Latent variable models (LVMs) are promising tools for analyzing this rich activity across diverse neural systems and behaviors, as LVMs do not depend on known relationships between the activity and external
experimental variables. To coordinate LVM modeling efforts, we introduce the Neural Latents Benchmark (NLB). The first benchmark suite, *NLB 2021*, evaluates models on 7 datasets of neural spiking activity spanning 4 tasks and brain areas.

 <!-- However, progress in latent variable modeling is currently impeded by a lack of standardization, resulting in methods being developed and compared in an ad hoc manner. -->
<!-- Models should take multi-channel spiking activity as input and produce firing rate estimates as output. Rate estimates should then be submitted to the public challenge hosted on [EvalAI](https://eval.ai/).  -->
While the benchmark will be available indefinitely, the challenge (phase 2) will close April 3, 2022. To get started with the challenge, follow the links on the left.

- [Read about NLB 2021 in our technical paper](http://arxiv.org/abs/2109.04463).
- [Join the mailing list for updates](https://forms.gle/o7BejfJ2S9hqJpM28).
- [See our Cosyne '21 announcement](https://www.youtube.com/watch?v=o7dvFLHb5AY).
- [Join our Slack workspace](https://neurallatents.slack.com). Please email `fpei6 [at] gatech [dot] edu` for an invite link.

## NLB 2021, Phase 2: Calling all models!
Phase 1 of our challenge was won by [AE Studio](https://ae.studio/); their writeup will be online shortly. Their team comprised Darin Erat Sleiter, Joshua Schoenfield, and Mike Vaiana; the team additionally thanks Sumner L Norman for his guidance and advice in the areas of neuroscience and neural decoding.

The challenge continues into phase 2 with two updates:
- **Workshop on 2/27**: We will host a virtual workshop consisting of several presentations on developing neural data models and an open-hacking period where participants are invited to hang out and get feedback from others. [RSVP here](https://forms.gle/YqWfqngaTiGuH7AA8).
- **New Judge's choice prize**: We have revised the prize structure for Phase 2. In addition to the co-smoothing prizes for each dataset, we have added 3 prizes for models selected by an external panel of judges to promote qualitative interpretability and useability. The specific judging criteria will be posted in the [challenge info](/challenge).

**Motivation**: The Neural Latents effort is unique among machine learning benchmarks in that the downstream use of these models clearly depends on more than the measured metrics. Therefore, we wish to allow for a more qualitative evaluation of each model for their relative merits, and encourage the submission of all models. For example, there is no consensus manner in which to measure model interpretability, but such interpretability is key when using LVMs to infer the computational function of the modeled activity. We want to discourage instances where developers keep potentially valuable models private because the model doesn't recapitulate the data as perfectly as a powerful black-box approach. One of our primary goals as a benchmark is to populate an "accuracy-interpretability" paretofront. Highlighting such a set of models would provide a variety of downstream users with the model best matched to their requirements, at all levels of analysis. The judge's choice prize is a first effort towards this concept.

---

## FAQ
### How do I submit a model to the benchmark?
We are hosting our challenge on [EvalAI](https://eval.ai/web/challenges/challenge-page/1256/overview), a platform for evaluating machine learning models. On the platform, you can choose to make private or public submissions to any or all of the individual datasets.

### Can I view the leaderboard without submitting?
Yes, the full leaderboard will be available on [EvalAI](https://eval.ai/web/challenges/challenge-page/1256/leaderboard), and EvalAI is also synced with [Papers With Code](https://paperswithcode.com/). Model open-sourcing is encouraged and thus may be available through the leaderboard.

### Is there a deadline?
The benchmark and its leaderboard can be submitted to indefinitely on EvalAI as a resource for the community. Phase 2 of the challenge, which rewards top entries with prizes, will end on April 3rd, 2022.

### Is NLB one benchmark or many benchmarks?
NLB aims to regularly organize benchmark suites, a collection of tasks, datasets, and metrics around a theme in neural latent variable modeling. For example, NLB'21 will emphasize general population modeling.

## Contact
The Neural Latents Benchmark is being led by the Systems Neural Engineering Lab in collaboration with labs across several universities. General inquiries should be directed to [Dr. Pandarinath] at `chethan [at] gatech [dot] edu`.
