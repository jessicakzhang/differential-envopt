## Optimization Layer for Solar Radiation Management

![Banner](./images/banner.jpeg)

This project explores the use of differentiable climate simulators to build an efficient optimization layer for environmental interventions, namely solar radiation management. 

### Overview
1. Forward Simulation: Simulates climate response to aerosol injections. 
    - This phase uses differentiable models (e.g., NeuralGCM, Earth-2) to track the thermal state of Earth in response to interventions.

2. Policy Optimization: Applies automatic differentiation to optimize for desired climate outcomes. The policy (i.e., when, where, and how much aerosol to inject) is updated using:
    - Gradient descent
    - Backpropagation through the simulator

### Requirements (planned)
- Python 3.10+
- Access to differentiable simulators (NeuralGCM, Earth-2 API or equivalents)
