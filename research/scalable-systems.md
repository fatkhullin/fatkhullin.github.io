---
layout: research
title: Scalable Systems - Distributed Training
---

# Communication-Efficient Distributed Training at Scale

<div style="display:flex; gap:20px; align-items:flex-start; flex-wrap:wrap; margin:12px 0;">
  <!-- Text column -->
  <div style="flex:1 1 60%; min-width:300px;">
    <p><strong>The Challenge</strong>: Modern machine learning requires training on massive datasets across distributed systems, where communication costs often dominate computational costs and can limit scalability.</p>

    <p><strong>My Approach</strong>: I develop methods that integrate communication compression with error compensation mechanisms to mitigate communication bottlenecks while preserving convergence guarantees.</p>

    <p><strong>Key Contributions</strong>:</p>
    <ul style="margin-top:6px;">
      <li>EF21: a simple, theoretically strong, and practically fast error-feedback method with optimal communication complexity
        (<a href="https://proceedings.neurips.cc/paper/2021/hash/231141b34c82aa95e48810a9d1b33a79-Abstract.html">NeurIPS 2021, Oral</a>).
      </li>
      <li>Six extensions and a comprehensive study of error feedback for modern systems
        (<a href="https://jmlr.org/papers/v26/24-0059.html">JMLR 2025</a>).
      </li>
      <li>Momentum provably improves error feedback with stability benefits and linear speed-ups
        (<a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/f0b1515be276f6ba82b4f2b25e50bef0-Abstract-Conference.html">NeurIPS 2023</a>).
      </li>
      <li>Safe-EF: communication-efficient methods for nonsmooth constrained optimization in safety-critical settings
        (<a href="https://icml.cc/virtual/2025/poster/46242">ICML 2025</a>).
      </li>
    </ul>

    <p><strong>Impact</strong>: The EF21 line of work is now a foundation for communication-efficient federated learning systems.</p>
  </div>

  <!-- Image column -->
  <div style="flex:1 1 35%; min-width:250px; text-align:center;">
    <img src="/assets/federated_learning.png"
         alt="Federated learning illustration"
         style="max-width:100%; height:auto; border:1px solid #ddd; border-radius:6px;">
    <figcaption style="font-size: 13px; margin-top:6px; color:#555;">
      Distributed Safe Reinforcement Learning of Humanoid Agents.
    </figcaption>
  </div>
</div>

## Selected Publications

- *EF21: A New, Simpler, Theoretically Better, and Practically Faster Error Feedback.* with P. Richtárik, I. Sokolov. [NeurIPS (Oral), 2021](https://proceedings.neurips.cc/paper/2021/hash/231141b34c82aa95e48810a9d1b33a79-Abstract.html).

- *EF21 with Bells & Whistles: Six Algorithmic Extensions of Modern Error Feedback.* with I. Sokolov, E. Gorbunov, Z. Li, P. Richtárik. [Journal of Machine Learning Research, 2025](https://jmlr.org/papers/v26/24-0059.html).

- *Momentum Provably Improves Error Feedback!* with A. Tyurin, P. Richtárik. [NeurIPS, 2023](https://proceedings.neurips.cc/paper_files/paper/2023/hash/f0b1515be276f6ba82b4f2b25e50bef0-Abstract-Conference.html).

- *Safe-EF: Error Feedback for Nonsmooth Constrained Optimization.* with R. Islamov, Y. As. [ICML, 2025](https://icml.cc/virtual/2025/poster/46242).

## Research Impact

The EF21 algorithm and its extensions have become fundamental building blocks for communication-efficient distributed machine learning, enabling large-scale training while maintaining theoretical guarantees and practical performance.
