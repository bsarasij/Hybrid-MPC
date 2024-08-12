# Hybrid-MPC applied to epidemiology

The classic Susceptible-Infected-Removed (SIR) model provides a basis for understanding the propagation of infectious diseases through a set of differential equations. The standard SIR model compartmentalizes the 
overall population into three classes: the Susceptible, the Infected, and the Recovered. A susceptible person when exposed to an infected person becomes infected themselves. However, no transfer takes place in the reverse direction. This process draws an analogy from an irreversible auto-catalytic reaction. The removal happens from the infected population through either recovery or death.
<p align = "center">
  <img src = "https://github.com/user-attachments/assets/8a03b063-bbdc-4626-99bc-4e8aeb9a8961">
</p>

<br>
<br>

## Categorical Control of SIR Infection using 3DoF Hybrid MPC
<p align = "center">
  <img src = "https://github.com/user-attachments/assets/b5ce73de-5b66-4a8e-96d1-910ee4df057c">
</p>


## Mixed Logic Dynamic Modeling of SIR Problem
<p align = "center">
  <img src ="https://github.com/user-attachments/assets/03a651bd-7639-4920-8464-64e530dd4f43">
</p>

<br>
<br>

## 3DoF applied to SIR model

* Measured disturbance (Δkv = 0.25 Day−1) at t = 80 Days.

* Unmeasured disturbance (Δγ = 0.1 Day−1) at t = 120 Days. 

* Reconfiguration bounds on the population = [550 900].

* No Chattering. Slack enforces soft constraints.

* Unavoidable yet Acceptable offset. 

<br>
<br>
<p align = "center">
  <img src ="https://github.com/user-attachments/assets/5ea1e8b1-68d0-4987-9978-5c63910efbb4">
</p>
