# Towards Safe Decision-Making for Autonomous Driving on Unsignalized Intersections

Abstract--Decision-making for urban autonomous driving is quite challenging, especially for unsignalized intersections, due to the stochastic nature of interactive traffic participants. Although reinforcement learning (RL)-based decision-making scheme is regarded as effective solutions, safety and adaptability remain key. In particular, an RL-based decision-making model will output an action in whatever state it is in-even in previously unseen states where a safe command cannot be determined due to lack of training. To this end, a safe decision-making framework is proposed to improve driving safety on unsignalized intersections. First, the RL-based policy is constructed based on the soft actor-critic (SAC) that maps environmental observations into actions directly. Subsequently, the epistemic uncertainty of the RL policy is estimated at runtime to quantify its reliability. Then, the risky actions outputted by the RL policy are filtered based on the estimated reliability by integrating a risk-adaptive model predictive control (RAMPC) backup policy. Finally, an unsignalized intersection with occlusion is built via Simulation of Urban Mobility (SUMO). More importantly, several cases are carried out to simulate scenario data distribution shifts, i.e., traffic flow density variation, observation with sensor noise, and observation range decrease, which are not included in the RL policy training process. The results indicate that the proposed method can reduce decision-making risk and improve driving safety.  

Expriment------------------------------The Specific Cases---------------------------------------------

ESAC:

![ESAC](https://github.com/Kayne0401/Safe-Decision-Making/assets/112403512/6e6d3208-a2e9-43ce-a0ef-6255dcaa0658)

SDMF:

![SDMF](https://github.com/Kayne0401/Safe-Decision-Making/assets/112403512/460f0110-debd-4e66-b028-651bf1224cec)






