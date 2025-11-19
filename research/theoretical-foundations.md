---
layout: research
title: Theoretical Foundations - Non-convex Theory
---

<!-- Drop this <style> block once on the page -->
<style>
  .row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    column-gap: 12px;
    row-gap: 12px;
    align-items: start;
  }
  .subfig {
    width: 100%;
    aspect-ratio: 1 / 1;
    max-width: 400px;   /* <— choose your target size */
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .subfig .frame {
    width: 100%;
    height: 100%;
    border: 1px solid #ddd;
    border-radius: 6px;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #fafafa;
    overflow: hidden;
  }
  .subfig img {
    width: 100%;
    height: 100%;
    object-fit: contain;
  }
  .subfig figcaption {
    margin-top: 8px;
    font-size: 14px;
    line-height: 1.5;
    text-align: center;
  }
</style>

# Theoretical Foundations: Hidden Convexity and Global Optimization

<div style="display:flex; gap:24px; align-items:flex-start; flex-wrap:wrap; margin:12px 0;">
  <!-- Figures column -->

  <div style="flex:1 1 50%; min-width:300px;">
    <div class="row">
      <figure class="subfig">
        <div class="frame">
          <img src="/assets/smooth_geometric_programming_X.png" alt="Non-Convex formulation">
        </div>
        <figcaption>
          <strong>Non-Convex Formulation.</strong><br>
          Level sets of objective F1 and the <span style="color:#6c757d;">feasible set {F2 ≤ 0}</span> in the original X-domain.
        </figcaption>
      </figure>


      <figure class="subfig">
        <div class="frame">
          <img src="/assets/smooth_geometric_programming_U.png" alt="Convex reformulation">
        </div>
        <figcaption>
          <strong>Convex Reformulation.</strong><br>
          Level sets of reformulated objective H1 and the <span style="color:#6c757d;">feasible set {H2 ≤ 0}</span> in the U-domain.
        </figcaption>
      </figure>
    </div>
  </div>

  <!-- Text column -->
  <div style="flex:1 1 50%; min-width:300px;">
    <p><strong>The Challenge</strong>: Most practically successful machine learning models involve highly non-convex optimization problems, yet their landscapes remain poorly understood. Traditional optimization theory often fails to explain why gradient methods work so well in practice.</p>

    <p><strong>My Approach</strong>: I develop the theory of "hidden convexity" — the idea that many seemingly non-convex problems actually admit equivalent convex structures, even if these structures are not directly computable. This framework provides rigorous explanations for the surprising success of optimization methods and enables the design of global solution algorithms.
    </p>

    <p><strong>Key Contributions</strong>:</p>
    <ul style="margin-top:6px;">
      <li>Analysis of optimization algorithms under hidden convexity (<a href="https://arxiv.org/abs/2401.00108">SIAM J. Optim., 2025</a>); helps to resolve open questions in reinforcement learning and variational inference.
      </li>
      <li>Tackling scenarios with non-convex functional constraints under hidden convexity (<a href="https://arxiv.org/abs/2511.10626">NeurIPS COML Workshop, 2025 (Oral)</a>); implies the first global solution method for safe convex reinforcement learning and other applications.
      </li>
      <li>Global convergence guarantees for natural gradient variational inference in non-conjugate models, using non-Euclidean projections and uncovering the hidden convexity in the variational loss (<a href="https://arxiv.org/abs/2510.19163">NeurIPS, 2025</a>).</li>
      <li>Using proporties of hidden convex structure for designing faster policy gradient methods in general utility RL (<a href="https://proceedings.mlr.press/v202/barakat23a.html">ICML, 2023</a>).
      </li>
      <li>Discovering new landscape structures in zero-sum game settings, which allow us improve complexities by orders of magnitude (<a href="https://epubs.siam.org/doi/10.1137/23M1626104">SIAM J. Contr. Optim., 2025</a>).</li>
      <li>Analyzing the fundamental structures of a linear quadratic regulator with output control. Convergence of carefully designed gradient method (<a href="https://epubs.siam.org/doi/10.1137/20M1329858">SIAM J. Contr. Optim., 2021</a>). </li>
    </ul>

    <p><strong>Impact</strong>: This line of work has led to substantial understanding of efficiency of policy gradient methods and provides a principled path for understanding non-convex optimization landscapes in safety-critical applications.</p>
  </div>
</div>

## Selected Publications

- *Stochastic Optimization under Hidden Convexity.* with N. He, Y. Hu. [SIAM Journal on Optimization, 2025](https://arxiv.org/abs/2401.00108).

- *Natural Gradient VI: Guarantees for Non-Conjugate Models.* with F. Sun, N. He. [NeurIPS, 2025](https://arxiv.org/abs/2510.19163).

- *Global Solutions to Non-Convex Functional Constrained Problems with Hidden Convexity.* with N. He, G. Lan, F. Wolf. [NeurIPS Workshop COML’25 (Oral)](https://constrained-opt-ml.github.io/papers/). Preprint: [arXiv](https://arxiv.org/abs/2511.10626).

- *Learning Zero-Sum Linear Quadratic Games with Improved Sample Complexity and Last-Iterate Convergence.* with J. Wu, A. Barakat, N. He. [SIAM Journal on Control and Optimization, 2025](https://epubs.siam.org/doi/10.1137/23M1626104). Preliminary version in [Conference on Decision and Control, 2023](https://ieeexplore.ieee.org/abstract/document/10384025).

- *Reinforcement Learning with General Utilities: Simpler Variance Reduction and Large State-Action Space.* with A. Barakat, N. He. [ICML, 2023](https://proceedings.mlr.press/v202/barakat23a.html).

- *Optimizing Static Linear Feedback: Gradient Method.* with B. Polyak. [SIAM Journal on Control and Optimization, 2021](https://epubs.siam.org/doi/10.1137/20M1329858).

## Research Impact

This theoretical framework has enabled breakthrough results in understanding why modern optimization methods work so well in practice, providing the mathematical foundations for reliable AI systems in safety-critical applications.
