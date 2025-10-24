---
layout: research
title: Data Efficiency - Robust Algorithms
---

# Data Efficiency: Robust Algorithms for Challenging Statistical Conditions

<div style="display:flex; gap:20px; align-items:flex-start; flex-wrap:wrap; margin:12px 0;">
  <!-- Text column -->
  <div style="flex:1 1 60%; min-width:300px;">
    <p><strong>The Challenge</strong>: Sample efficiency and training stability are major bottlenecks in reinforcement learning, particularly when dealing with heavy-tailed noise and limited data scenarios that are common in real-world applications.</p>

    <p><strong>My Approach</strong>: I investigate how statistical properties of data influence training dynamics, with emphasis on developing robust algorithms that maintain performance under challenging conditions while remaining tuning-free.</p>

    <p><strong>Key Contributions</strong>:</p>
    <ul style="margin-top:6px;">
      <li>Optimal sample efficiency guarantees for SGD under infinite variance noise
        (<a href="https://arxiv.org/abs/2508.04860">NeurIPS OptML Workshop, 2025</a>).
      </li>
      <li>Normalized SGD methods with high-probability fast convergence under heavy-tailed noise
        (<a href="https://openreview.net/forum?id=nuG0FYyWRT">AISTATS 2025</a>).
      </li>
      <li>Breaking sample efficiency limits for stochastic policy gradient methods, with improved theory and strong continuous-control results
        (<a href="https://proceedings.mlr.press/v202/fatkhullin23a.html">ICML 2023a</a>;
         <a href="https://proceedings.mlr.press/v202/barakat23a.html">ICML 2023b</a>).
      </li>
      <li>Hessian clipping: optimal second-order optimization under heavy-tailed noise (<a href="https://arxiv.org/abs/2510.10690">NeurIPS 2025</a>).</li>
    </ul>

    <p><strong>Impact</strong>: In practice, our proposed methods widen the range of stable step-sizes by a factor of three compared to standard SGD in challenging benchmarks like the Humanoid task, demonstrating both theoretical rigor and practical effectiveness.</p>
  </div>

  <!-- Image column -->
  <div style="flex:1 1 35%; min-width:250px; text-align:center;">
    <img src="/assets/humanoid_reacher_2algs.png"
         alt="Humanoid agent training robustness"
         style="max-width:100%; height:auto; border:1px solid #ddd; border-radius:6px;">
    <figcaption style="font-size: 13px; margin-top:6px; color:#555;">
      Robustness to step-size tuning in <code>Humanoid</code> agent training.
    </figcaption>
  </div>
</div>

## Selected Publications

- *Can SGD Handle Heavy-Tailed Noise?* with F. Hübler, G. Lan. [arXiv:2508.04860, 2025](https://arxiv.org/abs/2508.04860).

- *From Gradient Clipping to Normalization for Heavy-Tailed SGD.* with F. Hübler, N. He. [AISTATS, 2025](https://openreview.net/forum?id=nuG0FYyWRT).

- *Stochastic Policy Gradient Methods: Improved Sample Complexity for Fisher-non-degenerate Policies.* with A. Barakat, A. Kireeva, N. He. [ICML, 2023](https://proceedings.mlr.press/v202/fatkhullin23a.html).

- *Reinforcement Learning with General Utilities: Simpler Variance Reduction and Large State-Action Space.* with A. Barakat, N. He. [ICML, 2023](https://proceedings.mlr.press/v202/barakat23a.html).

- *Second-order Optimization under Heavy-Tailed Noise: Hessian Clipping and Sample Complexity Limits.* with A. Sadiev, P. Richtárik. [NeurIPS, 2025](https://arxiv.org/abs/2510.10690).

## Research Impact

These robust algorithms significantly improve training stability and sample efficiency, making reinforcement learning more practical for real-world applications with challenging statistical conditions.
