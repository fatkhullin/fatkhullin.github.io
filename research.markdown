---
layout: research
title: Research
---

# Research

<div style="text-align: center; margin: 40px 0; padding: 30px; background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%); border-radius: 15px; border-left: 5px solid #0366d6;">
<h2 style="color: #2c3e50; margin-top: 0; font-size: 1.4em;">Building the Next Generation of AI Systems</h2>
<p style="color: #666; font-size: 1.1em; margin-bottom: 0; font-style: italic;">Through rigorous theoretical foundations and principled algorithm design</p>
</div>

<!--
<div style="text-align: center; margin: 40px 0;">
  <img src="/assets/model_data_to_rl.png" 
       alt="Research Framework: From Complex Models to Trustworthy AI" 
       style="max-width: 80%; height: auto; border: 1px solid #ddd; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  <figcaption style="font-size: 14px; margin-top: 12px; color: #666; font-style: italic;">
    Research framework: transforming complex models and data through principled training dynamics into trustworthy, data-efficient, and scalable AI systems.
  </figcaption>
</div>
-->

My research develops the theoretical and algorithmic foundations of optimization and reinforcement learning (RL), aiming to understand how model structures, stochasticity, and their interaction shape the behavior of modern learning algorithms. Drawing on optimization and statistics foundations, I study questions in policy optimization, statistical inference, and distributed training–developing methods that remain principled even in complex and uncertain environments. Since AI systems are increasingly deployed in critical environments, such principled approaches are essential for creating trustworthy, efficient, and scalable learning algorithms.




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
  
  /* Mobile responsive styles */
  @media (max-width: 768px) {
    .research-cards-container {
      gap: 30px !important;
      flex-direction: column !important;
      align-items: center !important;
    }
    .research-card {
      max-width: 350px !important;
      width: 100% !important;
    }
  }
  
  @media (max-width: 480px) {
    .research-cards-container {
      gap: 20px !important;
      margin: 20px 0 !important;
    }
    .research-card {
      max-width: 300px !important;
      padding: 15px !important;
    }
    .research-card img {
      height: 120px !important;
    }
  }
</style>



<h2 style="text-align:center;">Key Research Directions</h2>

<div class="research-cards-container" style="display: flex; justify-content: center; align-items: stretch; gap: 60px; margin: 40px 0; flex-wrap: wrap;">

<!-- Non-convex Theory Card -->
<a href="/research/theoretical-foundations" style="text-decoration: none; color: inherit; flex: 0 1 300px; min-width: 0;">
<div class="research-card" style="background: white; padding: 20px; border-radius: 15px; box-shadow: 0 6px 12px rgba(0,0,0,0.1); width: 100%; text-align: center; transition: transform 0.3s ease, box-shadow 0.3s ease; height: 100%; display: flex; flex-direction: column;" onmouseover="this.style.transform='translateY(-5px)'; this.style.boxShadow='0 8px 20px rgba(0,0,0,0.15)'" onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='0 6px 12px rgba(0,0,0,0.1)'">
  <img src="/assets/landscape.png" alt="Hidden Convexity" style="width: 80%; height: 200px; object-fit: contain; margin: 0 auto 15px auto; flex-shrink: 0; display: block;">
  <h3 style="color: #2c3e50; margin: 15px 0 10px 0; flex-shrink: 0;">🔬 Non-convex Theory</h3>
  <div style="display: flex; flex-wrap: wrap; gap: 8px; justify-content: center; margin: 15px 0; flex-shrink: 0;">
    <span style="background: #e8f5e8; color: #2e7d32; padding: 4px 8px; border-radius: 12px; font-size: 0.8em;">Hidden Convexity</span>
    <span style="background: #e8f5e8; color: #2e7d32; padding: 4px 8px; border-radius: 12px; font-size: 0.8em;">Global Optimization</span>
    <span style="background: #e8f5e8; color: #2e7d32; padding: 4px 8px; border-radius: 12px; font-size: 0.8em;">Minima Selection</span>
  </div>
  <p style="color: #666; font-size: 0.9em; margin: 0; flex-grow: 1; display: flex; align-items: flex-end;">Mathematical frameworks for complex optimization landscapes.</p>
</div>
</a>

<!-- Data Efficiency Card -->
<a href="/research/data-efficiency" style="text-decoration: none; color: inherit; flex: 0 1 300px; min-width: 0;">
<div class="research-card" style="background: white; padding: 20px; border-radius: 15px; box-shadow: 0 6px 12px rgba(0,0,0,0.1); width: 100%; text-align: center; transition: transform 0.3s ease, box-shadow 0.3s ease; height: 100%; display: flex; flex-direction: column;" onmouseover="this.style.transform='translateY(-5px)'; this.style.boxShadow='0 8px 20px rgba(0,0,0,0.15)'" onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='0 6px 12px rgba(0,0,0,0.1)'">
  <img src="/assets/robustness.png" alt="Robust Algorithms" style="width: 80%; height: 200px; object-fit: contain; margin: 0 auto 15px auto; flex-shrink: 0; display: block;">
  <h3 style="color: #2c3e50; margin: 15px 0 10px 0; flex-shrink: 0;">⚡ Data Efficiency</h3>
  <div style="display: flex; flex-wrap: wrap; gap: 8px; justify-content: center; margin: 15px 0; flex-shrink: 0;">
    <span style="background: #e3f2fd; color: #1565c0; padding: 4px 8px; border-radius: 12px; font-size: 0.8em;">Heavy-Tailed Noise</span>
    <span style="background: #e3f2fd; color: #1565c0; padding: 4px 8px; border-radius: 12px; font-size: 0.8em;">Policy Gradients</span>
    <span style="background: #e3f2fd; color: #1565c0; padding: 4px 8px; border-radius: 12px; font-size: 0.8em;">Sample Efficiency</span>
  </div>
  <p style="color: #666; font-size: 0.9em; margin: 0; flex-grow: 1; display: flex; align-items: flex-end;">Reliable algorithms for challenging statistical conditions.</p>
</div>
</a>

<!-- Scalable Systems Card -->
<a href="/research/scalable-systems" style="text-decoration: none; color: inherit; flex: 0 1 300px; min-width: 0;">
<div class="research-card" style="background: white; padding: 20px; border-radius: 15px; box-shadow: 0 6px 12px rgba(0,0,0,0.1); width: 100%; text-align: center; transition: transform 0.3s ease, box-shadow 0.3s ease; height: 100%; display: flex; flex-direction: column;" onmouseover="this.style.transform='translateY(-5px)'; this.style.boxShadow='0 8px 20px rgba(0,0,0,0.15)'" onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='0 6px 12px rgba(0,0,0,0.1)'">
  <img src="/assets/federated_learning.png" alt="EF21 Algorithm" style="width: 80%; height: 190px; object-fit: contain; margin: 0 auto 15px auto; flex-shrink: 0; display: block;">
  <h3 style="color: #2c3e50; margin: 15px 0 10px 0; flex-shrink: 0;">🚀 Scalable Systems</h3>
  <div style="display: flex; flex-wrap: wrap; gap: 8px; justify-content: center; margin: 15px 0; flex-shrink: 0;">
    <span style="background: #fff8e1; color: #e65100; padding: 4px 8px; border-radius: 12px; font-size: 0.8em;">Distributed Training</span>
    <span style="background: #fff8e1; color: #e65100; padding: 4px 8px; border-radius: 12px; font-size: 0.8em;">Communication</span>
    <span style="background: #fff8e1; color: #e65100; padding: 4px 8px; border-radius: 12px; font-size: 0.8em;">Error Feedback</span>
  </div>
  <p style="color: #666; font-size: 0.9em; margin: 0; flex-grow: 1; display: flex; align-items: flex-end;">Communication-efficient distributed training at scale.</p>
</div>
</a>

</div>
