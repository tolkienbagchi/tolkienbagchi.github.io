---
---
# Welcome to Tolkien's Website
### PhD Student, Systems Engineering
Hi, I'm Tolkien! 
I am a PhD student in the [Department of Systems Engineering](https://www.engineering.cornell.edu/sys/) at Cornell University. I work on decision making under uncertainty, game theory, and mechanism design particularly as they apply to climate policy. 

{% include mathjax.html %}

## On robust optimization for climate policy
In decision making under uncertainty we have a function $f:\mathcal{X} \times \mathcal{Y} \to O$. We have control over one input $x \in \mathcal{X}$ but the other input $y \in \mathcal{Y}$ is unknown to us. There are two primary approaches to dealing with uncertainty in decision making:
1. **Stochastic Optimization:** Place a probability distribution $\mu$ over $Y$. If $f$ is reasonable (measurable) for any given $x$ this induces a family of probability distributions $\mu_f( \cdot \mid x)$ on $O$. We then define a new function $g$ on probability measures over $x$ 
2.
