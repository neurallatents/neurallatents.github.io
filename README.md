<!-- <div style="margin-bottom:1em"> -->
<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/o7dvFLHb5AY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->
<!-- </div> -->
## Overview

Advances in neural recording present increasing opportunities to study neural activity in unprecedented detail. Latent variable models (LVMs) are promising tools for analyzing this rich activity across diverse neural systems and behaviors, as LVMs do not depend on known relationships between the activity and external
experimental variables. To coordinate LVM modeling efforts, we introduce the Neural Latents Benchmark (NLB). The first benchmark suite, *NLB 2021*, evaluates models on 7 datasets of neural spiking activity spanning 4 tasks and brain areas.

 <!-- However, progress in latent variable modeling is currently impeded by a lack of standardization, resulting in methods being developed and compared in an ad hoc manner. -->
<!-- Models should take multi-channel spiking activity as input and produce firing rate estimates as output. Rate estimates should then be submitted to the public challenge hosted on [EvalAI](https://eval.ai/).  -->

- [Read about NLB 2021 in our technical paper](http://arxiv.org/abs/2109.04463)
- [Get started using NLB 2021 with our codepack](https://github.com/neurallatents/nlb_tools)
- [See past submissions on EvalAI](https://eval.ai/web/challenges/challenge-page/1256/leaderboard)
- [Join our Slack workspace](https://neurallatents.slack.com). Please email `fpei6 [at] gatech [dot] edu` for an invite link

## EvalAI submissions closed as of January 2026
We have been extremely grateful to see community engagement with our benchmark through two competition phases and continuing use of the benchmark ever since. 
Over 4+ years, NLB'21 has received hundreds of submissions and has been used to evaluate many innovative, state-of-the-art modeling methods. 
Unfortunately, we are unable to continue hosting our challenge on EvalAI. 
To our understanding, the leaderboard will remain visible in its current state, but new submission will no longer be accepted.

In response, we are publishing the previously-private evaluation data for the benchmark test split. The data are available in our [GitHub repo](https://github.com/neurallatents/nlb_tools) and can be used to run local model evaluation.

We note that this change will make it easier to overfit to the test split. Previously, submissions on EvalAI were rate-limited, discouraging this strategy (and we did not observe this from any groups that submitted to the benchmark). However, we hope that the ease of evaluation will instead encourage transparency in reporting model performance, for example by reporting scores across multiple random seeds.

## NLB Virtual Workshop
We hosted a virtual workshop on 2/27/2022, and **all materials from the workshop are available [here](https://github.com/neurallatents/nlb_workshop)**. The workshop featured several presentations on the benchmark and on developing neural data models, including talks about:
- Motivations behind the benchmark and how to participate
- nlb-lightning, a PyTorch lightning framework to facilitate development for NLB 2021
- Leading submissions and baselines, such as AESMTE3 (AEStudio), iLQR-VAE (Marine Schimel), and MINT (Sean Perkins)

---

## FAQ
### How do I submit a model to the benchmark?
As of January 2026, our challenge on EvalAI is no longer accepting submissions. Instead, you can evaluate your model locally with the test data available in [GitHub repo](https://github.com/neurallatents/nlb_tools). Unfortunately, it will not be possible to display new models on the public EvalAI leaderboard.

### Can I view the leaderboard without submitting?
Yes, the full leaderboard will be available on [EvalAI](https://eval.ai/web/challenges/challenge-page/1256/leaderboard), and EvalAI is also synced with [Papers With Code](https://paperswithcode.com/). Model open-sourcing is encouraged and thus may be available through the leaderboard.

### Is NLB one benchmark or many benchmarks?
NLB was originally intended to grow into a collection of benchmarks on neural latent variable modeling. Since NLB'21, members of our group have developed related benchmarks, including [FALCON](https://www.biorxiv.org/content/10.1101/2024.09.15.613126v1) (Karpowicz, Ye, et al. 2024) for robust, long-term neural decoding and the [Computation-thru-Dynamics Benchmark](https://www.biorxiv.org/content/10.1101/2025.02.07.637062v1) (Versteeg et al. 2025) for evaluation of neural dynamical models.

## Citation
If you use the Neural Latents Benchmark in your work, please cite our NeurIPS paper:
```
@inproceedings{PeiYe2021NeuralLatents,
  title={Neural Latents Benchmark '21: Evaluating latent variable models of neural population activity},
  author={Felix Pei and Joel Ye and David M. Zoltowski and Anqi Wu and Raeed H. Chowdhury and Hansem Sohn and Joseph E. O’Doherty and Krishna V. Shenoy and Matthew T. Kaufman and Mark Churchland and Mehrdad Jazayeri and Lee E. Miller and Jonathan Pillow and Il Memming Park and Eva L. Dyer and Chethan Pandarinath},
  booktitle={Advances in Neural Information Processing Systems (NeurIPS), Track on Datasets and Benchmarks},
  year={2021},
  url={https://arxiv.org/abs/2109.04463}
}
```

## Contact
The Neural Latents Benchmark is being led by the Systems Neural Engineering Lab in collaboration with labs across several universities. General inquiries should be directed to [Dr. Pandarinath] at `chethan [at] gatech [dot] edu`.
