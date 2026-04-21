---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<!-- Navigation Bar -->
<nav style="background: white; border-bottom: 1px solid #e1e4e8; padding: 20px 0; margin-bottom: 40px; width: 100%;">
  <div style="max-width: 1200px; margin: 0 auto; padding: 0 20px;">
    <div style="display: flex; justify-content: center; align-items: center; gap: 30px; flex-wrap: nowrap;">
      <a href="#about" style="text-decoration: none; color: #2c3e50; font-weight: 600; font-size: 18px; padding: 12px 24px; border-radius: 25px; background: white; box-shadow: 0 2px 6px rgba(0,0,0,0.08); transition: all 0.3s ease; border: 2px solid transparent;" onmouseover="this.style.background='#e8f5e8'; this.style.borderColor='#2e7d32'; this.style.transform='translateY(-2px)'; this.style.boxShadow='0 4px 12px rgba(0,0,0,0.15)'" onmouseout="this.style.background='white'; this.style.borderColor='transparent'; this.style.transform='translateY(0)'; this.style.boxShadow='0 2px 6px rgba(0,0,0,0.08)'">About</a>
      <a href="/research" style="text-decoration: none; color: #2c3e50; font-weight: 600; font-size: 18px; padding: 12px 24px; border-radius: 25px; background: white; box-shadow: 0 2px 6px rgba(0,0,0,0.08); transition: all 0.3s ease; border: 2px solid transparent;" onmouseover="this.style.background='#e3f2fd'; this.style.borderColor='#1565c0'; this.style.transform='translateY(-2px)'; this.style.boxShadow='0 4px 12px rgba(0,0,0,0.15)'" onmouseout="this.style.background='white'; this.style.borderColor='transparent'; this.style.transform='translateY(0)'; this.style.boxShadow='0 2px 6px rgba(0,0,0,0.08)'">Research</a>
      <a href="/publications" style="text-decoration: none; color: #2c3e50; font-weight: 600; font-size: 18px; padding: 12px 24px; border-radius: 25px; background: white; box-shadow: 0 2px 6px rgba(0,0,0,0.08); transition: all 0.3s ease; border: 2px solid transparent;" onmouseover="this.style.background='#fff8e1'; this.style.borderColor='#e65100'; this.style.transform='translateY(-2px)'; this.style.boxShadow='0 4px 12px rgba(0,0,0,0.15)'" onmouseout="this.style.background='white'; this.style.borderColor='transparent'; this.style.transform='translateY(0)'; this.style.boxShadow='0 2px 6px rgba(0,0,0,0.08)'">Publications</a>
      <a href="/contact" style="text-decoration: none; color: #2c3e50; font-weight: 600; font-size: 18px; padding: 12px 24px; border-radius: 25px; background: white; box-shadow: 0 2px 6px rgba(0,0,0,0.08); transition: all 0.3s ease; border: 2px solid transparent;" onmouseover="this.style.background='#f3e5f5'; this.style.borderColor='#7b1fa2'; this.style.transform='translateY(-2px)'; this.style.boxShadow='0 4px 12px rgba(0,0,0,0.15)'" onmouseout="this.style.background='white'; this.style.borderColor='transparent'; this.style.transform='translateY(0)'; this.style.boxShadow='0 2px 6px rgba(0,0,0,0.08)'">Contact</a>
    </div>
  </div>
</nav>

## About {#about}

I am a final-year PhD student at [ETH Zurich](https://ethz.ch/en.html), advised by [Prof. Niao He](https://odi.inf.ethz.ch/niaohe). My research focuses on developing theoretically grounded algorithms for machine learning and optimization, with an emphasis on data efficiency, scalability, and safety. Previously, I had an honor to work with [Prof. Boris Polyak](https://scholar.google.com/citations?user=Zhlib28AAAAJ&hl=en) on control theory problems and with [Prof. Peter Richtárik](https://richtarik.org) on federated learning, focusing on communication-efficient distributed training.


My research contributions have appeared in leading machine learning venues including NeurIPS, ICML, AISTATS, Journal of Machine Learning Research, as well as SIAM Journal on Optimization, SIAM Journal on Control and Optimization. 

I am currently supported by the [ETH AI Center Doctoral Fellowship](https://ai.ethz.ch/education/phd-and-postdoc-programs/phd-fellowships.html) and previously received a [DAAD Scholarship](https://www2.daad.de/deutschland/stipendium/datenbank/en/21148-scholarship-database/?detail=50026200) for Master studies in Germany.



---
## Research Overview {#research}

My work centers on three interconnected pillars that address fundamental challenges in modern machine learning:

<div style="text-align: center; margin: 30px 0;">
  <a href="/research" style="text-decoration: none; color: #2c3e50; font-weight: 600; font-size: 16px; padding: 10px 25px; border-radius: 20px; background: white; box-shadow: 0 2px 6px rgba(0,0,0,0.08); transition: all 0.3s ease; border: 2px solid #e1e4e8; display: inline-block;" onmouseover="this.style.background='#e3f2fd'; this.style.borderColor='#1565c0'; this.style.transform='translateY(-2px)'; this.style.boxShadow='0 4px 12px rgba(0,0,0,0.15)'" onmouseout="this.style.background='white'; this.style.borderColor='#e1e4e8'; this.style.transform='translateY(0)'; this.style.boxShadow='0 2px 6px rgba(0,0,0,0.08)'">Explore Research Details →</a>
</div>

**🔬 Non-convex Optimization**: I develop rigorous mathematical frameworks to understand complex optimization landscapes, including hidden convexity structures that enable global solutions to seemingly intractable non-convex problems.

**⚡ Data Efficiency and Robustness**: I design robust algorithms that maintain performance under challenging statistical conditions, such as heavy-tailed noise and limited data scenarios, with particular relevance for policy gradient methods in reinforcement learning.

**🚀 Scalable Systems**: I create communication-efficient distributed training algorithms that enable large-scale machine learning while preserving theoretical guarantees, including the popular EF21 algorithm.

<div style="text-align: center; margin: 40px 0;">
  <div style="display: flex; justify-content: center; gap: 15px; flex-wrap: wrap;">
    <a href="/publications" style="text-decoration: none; color: #2c3e50; font-weight: 600; font-size: 16px; padding: 10px 25px; border-radius: 20px; background: white; box-shadow: 0 2px 6px rgba(0,0,0,0.08); transition: all 0.3s ease; border: 2px solid #e1e4e8; display: inline-block;" onmouseover="this.style.background='#fff8e1'; this.style.borderColor='#e65100'; this.style.transform='translateY(-2px)'; this.style.boxShadow='0 4px 12px rgba(0,0,0,0.15)'" onmouseout="this.style.background='white'; this.style.borderColor='#e1e4e8'; this.style.transform='translateY(0)'; this.style.boxShadow='0 2px 6px rgba(0,0,0,0.08)'">View All Publications →</a>
  </div>
</div>

<style>
div[style*="background-color: #f8f9fa"]:hover {
    transform: translateY(-5px);
    box-shadow: 0 4px 8px rgba(0,0,0,0.15);
}
</style>

<style>
.research-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 12px 20px rgba(0,0,0,0.2);
}
</style>

---
## Upcoming Events and Talks:

- **June 2026** - Attending SIAM Conference on Optimization (OP26) in Edinburgh, United Kingdom (June 2-5), as an organizer of Minisymposium and invited speaker.
- **May 2026** – Attending ELLIIT symposium and focus period on Optimization for Learning, Lund Sweden (Invited Visiting Scholar). 

## News {#news}

- **March 2026** – Attended INFORMS IOS in Atlanta, U.S.A., as a Session organizer and speaker.
- **February 2026** – Finished a 5-month internship at Amazon as Applied Scientist Intern.
- **December 2025** – Presented "Global Solutions to Non-Convex Functional Constrained Problems with Hidden Convexity." at NeurIPS Workshop on Constrained Optimization for Machine Learning. 
_Oral Presentation Award for the best fundamental (theoretical or algorithmic) contribution._
- **October 2025** – Started an Applied Scientist internship with Amazon’s Forecasting & Optimization team in Luxembourg, focusing on large-scale capacity management problems across the delivery network.
- **August 2025** – Delivered “Can SGD Handle Heavy-Tailed Noise?” at the H. Milton Stewart School of Industrial and Systems Engineering (Georgia Tech) student seminar in Atlanta.
- **July 2025** – Attended the International Conference on Continuous Optimization ICCOPT 2025 at the University of Southern California in Los Angeles, USA, and presented “Taming Nonconvex Stochastic Mirror Descent with General Bregman Divergence.”
- **July 2025** – Attended the International Conference on Stochastic Programming (ICSP) 2025 in Paris, France, and presented “Safe-EF: Error Feedback for Nonsmooth Constrained Optimization (with Applications to Humanoid Fleet Training).”
- **March 2025** – Research visit at Georgia Tech’s H. Milton Stewart School of ISyE with Prof. Guanghui (George) Lan.