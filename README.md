# Application of Physics-informed Neural Networks on (chaotic) nonlinear ODE systems
# Combined Bachelor Thesis (NS-320B), June 2022
## Mathematics & Physics and Astronomy (NS-320B)
*'Applying Physics-informed Neural Networks to Chaotic Nonlinear Systems of Ordinary Differential Equations'*

**Author:** Martijn Sebastiaan Brouwer (6859488)

**Mathematics supervisors:** prof. dr. ir. C.W. Oosterlee

**Physics supervisor:** dr. J. de Graaf

**PhD supervisor:** B. Negyesi

* *Abstract Recent developments in unsupervised deep learning have shown that physical systems described by differential equations can be approximated using neural networks. This brings rise to a novel class of frameworks, called physics-informed neural networks. The loss functions of these networks make use of automatic differentiation and respects the physical laws described by the considered system. Using these networks, we apply methods to predict futures states of (chaotic) nonlinear systems of ordinary differential equations. It has been observed that the origin greatly affects this network's approximation due to the fact that the loss is being minimized the closer it gets to the origin. To counter this attractive property of the origin, we train on a restricted time scale until convergence is reached - i.e. the loss decreasing below a certain threshold - and repeatedly extent the considered final time to converge over large time scales. Besides this approach, we also develop a fixed point loss component which is applicable to systems with globally attracting fixed points. These methods are tested on the Lorenz system and the Mackey-Glass time series and have shown to converge over large time scales for several non-chaotic settings. Considering highly tortuous chaotic settings still lead to complications to converge over large time scales, but show accurate approximations on small time scales. 
