---
layout: archive
#title: "Projects"
permalink: /projects/
author_profile: true
---

**Page under construction**

<html>
<body>
<h1>Past projects</h1>
    <table style = "background-color:#D2FBFF;">
        
        <tr><td colspan = "2" style="border: none;padding-right:40px;vertical-align:bottom;text-align:center;"><p style="font-size:20px;margin-bottom: -15px;"><b>Viability of branch-and-bound (B&B) algorithms</b></p></td></tr>  
        <tr>
        <td style = "border: none;">
          <p style="font-size:16px;text-align:justify"><br>
              B&B algorithms provide the main theoretical framework for solving nonconvex problems to global optimality. Their major drawback is that they can take exponentially many iterations in the search space dimension to converge. Reduced-space B&B algorithms mitigate this issue by working in a low-dimensional subspace. They can be effective in solving stochastic programs. I built a general theory to identify properties that a B&B algorithm must possess to be computationally tractable. I discovered that reduced-space algorithms may be impractical unless auxiliary techniques are used to boost their performance. I used these insights to design an efficient reduced-space B&B algorithm for two-stage stochastic programs. </p>
        </td>
        <td style = "border: none;width: 453.5px;padding-right: 20px;">
          <img src="https://rohitkannan.github.io/images/fig1.png" style = "clear:both;width:auto;height:auto"/>
        </td>
      </tr>
   <tr>
       <td colspan = "2"><p>Kannan, R., & Barton, P. I. (2017). The cluster problem in constrained global optimization. Journal of Global Optimization, 69(3), 629-676.</p> 
           <p>Kannan, R., & Barton, P. I. (2018). Convergence-order analysis of branch-and-bound algorithms for constrained problems. Journal of Global Optimization, 71(4), 753-813.</p>
       </td> 
   </tr>    
        
  </table>
        
  <table style = "border: none;">
        
       <tr>
        <td colspan = "2" style="border: none;padding-right:40px;vertical-align:bottom;text-align:center;"><p style="font-size:20px;margin-bottom: -15px;"><b>Algorithms for two-stage stochastic programs</b></p></td>
        </tr>
        <tr>
            <td style = "border: none;width: 453.5px;padding-right: 20px;">
          <img src="https://rohitkannan.github.io/images/fig2.png" style = "clear:both;width:auto;height:auto"/>
        </td>
        <td style = "border: none;">
          <p style="font-size:16px; text-align: justify">
              Scenario-based two-stage stochastic programming requires a set of first-stage decisions to be made before the uncertainty is resolved. The uncertain parameters are then assumed to take one of a finite set of values with known probabilities, following which recourse decisions can be taken to ensure the system's feasibility. The goal is to determine decisions that optimize the sum of first-stage and expected recourse objectives. In my PhD thesis, I designed the first reduced-space B&B algorithm with provable finite convergence properties for solving two-stage stochastic mixed-integer nonlinear programs (MINLPs). I also developed a software that implements state-of-the-art algorithms for this problem class, which enabled a $70$x speedup in the solution of my sponsor's application of integrated crude selection and refinery operation. My software is currently being used at MIT for the design of flexible energy polygeneration systems.</p>
        </td>
         </tr>
     </table>
    
    <table style = "background-color:#D2FBFF;">
        <tr>
        <td colspan = "2" style="border: none;padding-right:40px;vertical-align:bottom;text-align:center;"><p style="font-size:20px;margin-bottom: -15px;"><b>Optimization with reliability constraints</b></p></td>
        </tr>
        <tr>
        <td style = "border: none;">
          <p style="font-size:16px; text-align: justify">
              Chance-constrained optimization requires constraints with uncertain parameters to be satisfied with a minimum probability (reliability). It has applications in finance, energy, and chemical process systems. Despite their intuitive appeal, reliability constraints are difficult to tackle - they can be nonsmooth, nonconvex, and hard to evaluate! Popular approaches use convex and/or sample-based approximations to circumvent these difficulties, but they typically yield suboptimal solutions or intractable models. Adopting a bi-objective viewpoint, I designed a stochastic subgradient method to approximate the efficient frontier of minimum objective value versus solution reliability. I established theoretical guarantees and designed a tailored implementation of my method. My algorithm consistently yields better approximations of the efficient frontier than existing approaches on test cases.</p>
        </td>
            <td style = "border: none;width: 453.5px;padding-right: 20px;">
          <img src="https://rohitkannan.github.io/images/fig3.png" style = "clear:both;width:auto;height:auto"/>
        </td>
         </tr>
    </table>
    </body>
</html>
