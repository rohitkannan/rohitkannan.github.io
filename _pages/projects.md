---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
<html>
<body>

<div>
    <table style = "border: none;">
      <tr>
        <td style = "border: none;">
          <p style="font-size:16px"><b>Viability of branch-and-bound (B&B) algorithms:</b><br>
              B&B algorithms provide the main theoretical framework for solving nonconvex problems to global optimality. Their major drawback is that they can take exponentially many iterations in the search space dimension to converge. Reduced-space B&B algorithms mitigate this issue by working in a low-dimensional subspace. They can be effective in solving stochastic programs. I built a general theory to identify properties that a B&B algorithm must possess to be computationally tractable. I discovered that reduced-space algorithms may be impractical unless auxiliary techniques are used to boost their performance. I used these insights to design an efficient reduced-space B&B algorithm for two-stage stochastic programs. </p>
        </td>
        <td style = "border: none;width: 453.5px;padding-right: 20px;">
          <img src="https://rohitkannan.github.io/images/fig1.png" style = "clear:both;width:auto;height:auto"/>
        </td>
      </tr> 
        <tr>
            <td style = "border: none;width: 453.5px;padding-right: 20px;">
          <img src="https://rohitkannan.github.io/images/fig2.png" style = "clear:both;width:auto;height:auto"/>
        </td>
        <td style = "border: none;">
          <p style="font-size:16px"><b>Algorithms for two-stage stochastic programs:</b><br>
              Scenario-based two-stage stochastic programming requires a set of first-stage decisions to be made before the uncertainty is resolved. The uncertain parameters are then assumed to take one of a finite set of values with known probabilities, following which recourse decisions can be taken to ensure the system's feasibility. The goal is to determine decisions that optimize the sum of first-stage and expected recourse objectives. In my PhD thesis, I designed the first reduced-space B&B algorithm with provable finite convergence properties for solving two-stage stochastic mixed-integer nonlinear programs (MINLPs). I also developed a software that implements state-of-the-art algorithms for this problem class, which enabled a $70$x speedup in the solution of my sponsor's application of integrated crude selection and refinery operation. My software is currently being used at MIT for the design of flexible energy polygeneration systems.</p>
        </td>
         </tr>
    </table>
</div>

  

</body>
</html>
