# Ben & Jerry's Claw Machine

Quick little notebook to model the claw machine at UTown.  
Each play is a Bernoulli trial (win/lose), so the number of tries until you win follows a geometric distribution.  

- Estimate success probability: p_hat = (number of sessions) / (total tries)  
- Expected tries = 1 / p_hat  
- Expected cost = $1 * (1 / p_hat)  

Notebook shows a simple simulation + histogram. 
Most wins happen early, but sometimes you get a long unlucky run which is just like the real machine.  
