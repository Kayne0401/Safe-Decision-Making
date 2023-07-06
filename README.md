# Towards Safe Decision-Making for Autonomous Driving on Unsignalized Intersections

Urban autonomous driving decision-making poses a significant challenge, particularly when navigating unsignalized intersections. This complexity mainly stems from the stochastic interactions between various traffic participants. While reinforcement learning (RL)-based decision-making has shown promise, there are valid concerns regarding safety and adaptability. In particular, current RL-based models lack safeguards to prevent issuing potentially unsafe commands in unfamiliar scenarios not covered during training. To this end, this paper proposes a novel framework for safer decision-making at unsignalized intersections. First, the RL-based policy is constructed based on the soft actor-critic (SAC) that maps environmental observations into actions directly. Subsequently, a mechanism to measure the reliability of the SAC policy in real-time is provided via epistemic uncertainty quantification. Then, the risky actions outputted by the RL policy are filtered based on the estimated reliability with integrating a risk-adaptive model predictive control (RAMPC) backup policy. Finally, an unsignalized intersection with occlusion is built via Simulation of Urban Mobility (SUMO). More importantly, several cases are carried out to simulate scenario data distribution shifts, \emph{i.e.}, traffic flow density variation, observation with sensor noise, and observation range decrease, which are not included in the RL policy training process. The results suggest that the proposed method can reduce risk and enhance the safety of autonomous driving at unsignalized intersections. 

Expriment------------------------------The Specific Cases---------------------------------------------

ESAC:

![ESAC](https://github.com/Kayne0401/Safe-Decision-Making/assets/112403512/6e6d3208-a2e9-43ce-a0ef-6255dcaa0658)

SDMF:

![SDMF](https://github.com/Kayne0401/Safe-Decision-Making/assets/112403512/460f0110-debd-4e66-b028-651bf1224cec)






