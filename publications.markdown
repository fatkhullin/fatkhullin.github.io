---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
# /assets/posters/Poster_NC_SMD.pdf

layout: default
title: Publications
permalink: /publications/
---
<table>
  <tr>
    <td style="border:none">
      <a href="/index"><h3>About</h3></a>
    </td>
    <td style="border:none">
      <a href="#publ"><h3>Publications</h3></a>
    </td>
    <td style="border:none">
      <a href="/contact"><h3>Contact</h3></a>
    </td>
  </tr>
</table>
---

# Publications {#publ}


  <li style="margin-bottom: 20px;">
    Ilyas Fatkhullin, Niao He. <a href="https://arxiv.org/abs/2402.17722">Taming Nonconvex Stochastic Mirror Descent with General Bregman Divergence</a>, AISTATS 2024.
    <div style="display:block; margin-top: 10px;">
      <span style="cursor:pointer;" onclick="toggleVisibility('pub1', this)">&#x25BC; Poster</span>
    </div>
    <div id="pub1" style="display:none; margin-top: 10px;">
      <img src="/assets/posters/Poster_NC_SMD.pdf" alt="Poster Nonconvex SMD" style="width:100%; max-width:800px;" onclick="openModal(this.src)" />
    </div>
  </li>
  <li style="margin-bottom: 20px;">
    Ilyas Fatkhullin, Niao He, Yifan Hu. <a href="https://arxiv.org/abs/2401.00108">Stochastic Optimization under Hidden Convexity</a>, OptML workshop at NeurIPS 2023.
    <div style="display:block; margin-top: 10px;">
      <span style="cursor:pointer;" onclick="toggleVisibility('pub2', this)">&#x25BC; Poster</span>
    </div>
    <div id="pub2" style="display:none; margin-top: 10px;">
      <img src="/assets/posters/Poster_Hidden_Convexity.pdf" alt="Poster Hidden Convexity" style="width:100%; max-width:800px;" onclick="openModal(this.src)" />
    </div>
  </li>
  <li style="margin-bottom: 20px;">
    Jiduan Wu, Anas Barakat, Ilyas Fatkhullin, Niao He. <a href="https://arxiv.org/abs/2309.04272">Learning Zero-Sum Linear Quadratic Games with Improved Sample Complexity</a>, OptML workshop at NeurIPS 2023.
  </li>

  <li style="margin-bottom: 20px;">
    Ilyas Fatkhullin, Alexander Tyurin, Peter Richtárik. <a href="https://arxiv.org/abs/2305.15155">Momentum Provably Improves Error Feedback!</a>, NeurIPS 2023.
  </li>

  <li style="margin-bottom: 20px;">
    Junchi Yang, Xiang Li, Ilyas Fatkhullin, Niao He. <a href="https://arxiv.org/abs/2305.12475">Two Sides of One Coin: the Limits of Untuned SGD and the Power of Adaptive Methods</a>, NeurIPS 2023.
  </li>
  <li style="margin-bottom: 20px;">
    Anas Barakat, Ilyas Fatkhullin, Niao He. <a href="https://arxiv.org/abs/2306.01854">Reinforcement Learning with General Utilities: Simpler Variance Reduction and Large State-Action Space</a>, ICML 2023.
  </li>
  <li style="margin-bottom: 20px;">
    Ilyas Fatkhullin, Anas Barakat, Anastasia Kireeva, Niao He. <a href="https://proceedings.mlr.press/v202/fatkhullin23a.html">Stochastic Policy Gradient Methods: Improved Sample Complexity for Fisher-non-degenerate Policies</a>, ICML 2023.
  </li><li style="margin-bottom: 20px;">
    Ilyas Fatkhullin, Jalal Etesami, Niao He, Negar Kiyavash. <a href="https://arxiv.org/abs/2210.01748">Sharp Analysis of Stochastic Optimization under Global Kurdyka-Łojasiewicz Inequality</a>, NeurIPS 2022.
  </li><li style="margin-bottom: 20px;">
    Peter Richtárik, Igor Sokolov, Ilyas Fatkhullin, Elnur Gasanov, Eduard Gorbunov, Zhize Li. <a href="https://arxiv.org/abs/2202.00998">3PC: Three Point Compressors for Communication-Efficient Distributed Training and a Better Theory for Lazy Aggregation</a>, ICML 2022 (spotlight).
  </li><li style="margin-bottom: 20px;">
    Ilyas Fatkhullin, Igor Sokolov, Eduard Gorbunov, Zhize Li, Peter Richtárik. <a href="https://arxiv.org/abs/2110.03294">EF21 with Bells & Whistles: Practical Algorithmic Extensions of Modern Error Feedback</a>, OptML workshop at NeurIPS 2021.
  </li><li style="margin-bottom: 20px;">
    Peter Richtárik, Igor Sokolov, Ilyas Fatkhullin. <a href="https://arxiv.org/abs/2106.05203">EF21: A New, Simpler, Theoretically Better, and Practically Faster Error Feedback</a>, NeurIPS 2021 (oral).
  </li><li style="margin-bottom: 20px;">
    Ilyas Fatkhullin, Boris Polyak. <a href="https://arxiv.org/abs/2004.09875">Optimizing Static Linear Feedback: Gradient Method</a>, SIAM Journal on Control and Optimization 59, 3887-3911 (2021).
  </li><li style="margin-bottom: 20px;">
    Boris Polyak, Ilyas Fatkhullin. <a href="https://link.springer.com/article/10.1134/S0965542520050127">Use of Projective Coordinate Descent in the Fekete Problem</a>, Comput. Math. and Math. Phys. 60, 795–807 (2020).
  </li>
  <!-- Add more publications here, ensuring consistency -->


<!-- Modal for enlarged image -->
<div id="imageModal" style="display:none; position:fixed; z-index:1000; left:0; top:0; width:100%; height:100%; overflow:auto; background-color:rgba(0,0,0,0.9);">
  <span style="position:absolute; top:20px; right:35px; color:#fff; font-size:40px; font-weight:bold; cursor:pointer;" onclick="closeModal()">&times;</span>
  <img id="modalContent" style="margin:auto; display:block; width:80%; max-width:1000px;">
</div>

<script>
  function toggleVisibility(id, icon) {
    var element = document.getElementById(id);
    if (element.style.display === "none") {
      element.style.display = "block";
      icon.innerHTML = "&#x25B2; Poster";  // Change to an upside-down caret and label
    } else {
      element.style.display = "none";
      icon.innerHTML = "&#x25BC; Poster";  // Change back to a downward caret and label
    }
  }

  function openModal(src) {
    var modal = document.getElementById("imageModal");
    var modalImg = document.getElementById("modalContent");
    modal.style.display = "block";
    modalImg.src = src;
  }

  function closeModal() {
    var modal = document.getElementById("imageModal");
    modal.style.display = "none";
  }
</script>
