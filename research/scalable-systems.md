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

    <p><strong>Empirical Insight</strong>: Figure 1 shows the distributed reinforcement learning deployments that motivate these systems, Figure 2 highlights how identifying the stochastic limitations of EF21 and adding momentum restores stability, and Figure 3 demonstrates Safe-EF’s worker-scaling gains that keep communication budgets in check.</p>

    <p><strong>Key Contributions</strong>:</p>
    <ul style="margin-top:6px;">
      <li>EF21: a simple, theoretically strong, and practically fast error-feedback method with optimal communication complexity
        (<a href="https://proceedings.neurips.cc/paper/2021/hash/231141b34c82aa95e48810a9d1b33a79-Abstract.html">NeurIPS 2021, Oral</a>).
      </li>
      <li>Six extensions and a comprehensive study of error feedback for modern systems
        (<a href="https://jmlr.org/papers/v26/24-0059.html">JMLR 2025</a>).
      </li>
      <li>I identify the limitations of EF21 in stochastic settings and propose a theoretically grounded and practically relevant momentum method: momentum provably improves error feedback with stability benefits and linear speed-ups
        (<a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/f0b1515be276f6ba82b4f2b25e50bef0-Abstract-Conference.html">NeurIPS 2023</a>).
      </li>
      <li>Safe-EF: communication-efficient methods for nonsmooth constrained optimization in safety-critical settings, validated on the challenging fleet-scale Humanoid training task with PPO to meet strict safety limits. We prove the optimal communication complexity for such problems, while delivering 100× communication gains in practice. 
        (<a href="https://icml.cc/virtual/2025/poster/46242">ICML 2025</a>).
      </li>
    </ul>

    <p><strong>Impact</strong>: The EF21 line of work is now a foundation for communication-efficient federated learning systems.</p>

    <div style="margin-top:24px;">
      <h2 style="font-size:1.25rem; margin-bottom:10px;">Selected Publications</h2>
      <ul style="padding-left:18px;">
        <li><em>EF21: A New, Simpler, Theoretically Better, and Practically Faster Error Feedback.</em> with P. Richtárik, I. Sokolov. <a href="https://proceedings.neurips.cc/paper/2021/hash/231141b34c82aa95e48810a9d1b33a79-Abstract.html">NeurIPS (Oral), 2021</a>.</li>
        <li><em>EF21 with Bells &amp; Whistles: Six Algorithmic Extensions of Modern Error Feedback.</em> with I. Sokolov, E. Gorbunov, Z. Li, P. Richtárik. <a href="https://jmlr.org/papers/v26/24-0059.html">Journal of Machine Learning Research, 2025</a>.</li>
        <li><em>Momentum Provably Improves Error Feedback!</em> with A. Tyurin, P. Richtárik. <a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/f0b1515be276f6ba82b4f2b25e50bef0-Abstract-Conference.html">NeurIPS, 2023</a>.</li>
        <li><em>Safe-EF: Error Feedback for Nonsmooth Constrained Optimization.</em> with R. Islamov, Y. As. <a href="https://icml.cc/virtual/2025/poster/46242">ICML, 2025</a>.</li>
      </ul>
    </div>

    <div style="margin-top:24px;">
      <h2 style="font-size:1.25rem; margin-bottom:10px;">Research Impact</h2>
      <p>The EF21 algorithm and its extensions have become fundamental building blocks for communication-efficient distributed machine learning, enabling large-scale training while maintaining theoretical guarantees and practical performance.</p>
    </div>
  </div>

  <!-- Image column -->
  <div style="flex:1 1 35%; min-width:250px; text-align:center;">
    <div style="display:flex; flex-direction:column; gap:18px;">
      <div>
        <img src="/assets/federated_learning.png"
             alt="Federated learning illustration"
             style="max-width:100%; height:auto; border:1px solid #ddd; border-radius:6px; background:#fff;">
        <p style="font-size: 12px; margin-top:6px; color:#555;">
          <strong>Figure 1.</strong> Distributed safe reinforcement learning of humanoid agents across multi-node clusters that use compressed updates.
        </p>
      </div>
      <div>
        <img src="/assets/upd_divergence_const_sz_n_1.png"
             alt="EF21 stability comparison"
             style="max-width:100%; height:auto; border:1px solid #ddd; border-radius:6px; background:#fff;">
        <p style="font-size: 12px; margin-top:6px; color:#555;">
          <strong>Figure 2.</strong> EF21-SGD diverges under simple stochastic noise when using aggressive compression, whereas the momentum-enhanced EF21-SGDM remains stable near the optimum and remains efficient in more challenging tasks.
        </p>
      </div>
      <div>
        <img src="/assets/ablate-workers.png"
             alt="Safe-EF worker scaling"
             style="max-width:100%; height:auto; border:1px solid #ddd; border-radius:6px; background:#fff;">
        <p style="font-size: 12px; margin-top:6px; color:#555;">
          <strong>Figure 3.</strong> Safe-EF convergence across worker counts: more workers trim communication cost even as gains taper, highlighting the method's scalability.
        </p>
      </div>
    </div>
  </div>
</div>
