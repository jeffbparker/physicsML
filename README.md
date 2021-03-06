# physicsML
Physics + Machine Learning

## PINN - Physics-Informed Neural Network
[Notebook](PINN/Physics_informed_neural_network.ipynb).  I build a PINN [[Raissi et al., (2019)](https://www.sciencedirect.com/science/article/pii/S0021999118307125)] to solve the PDE Burgers equation, arising from fluid dynamics.  The PINN is constructed using TensorFlow, making use of the built-in autodifferentiation.  The network is trained via the L-BFGS optimizer.  The trained neural network gives very good predictions to the true solution of the PDE (computed via direct numerical simulation).  
