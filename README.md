# Solving-ODEs-using-PINNs

The notebook you can find here is intended as a concise introduction to the thrilling topic of using $Physically \hspace{1mm} Informed \hspace{1mm} Neural \hspace{1mm} Networks$ (PINNs) to solve $Ordinary \hspace{1mm} Differential \hspace{1mm} Equations$ (ODE) of various orders. These ODEs stem from well knwon physical systems or phenomena and can be solved either analytically or numerically employing classical numerical integration methods like Runge-Kutta of $4^{th}$ order. The aim of the exercises shown here is to enable students to: build a PINN, tune the hyperparameters, and many more.

In this notebook there are 3 exercises. The first exercise a typical exponential decay problem constituting a $1^{st}$ order ODE. Such equation can describe the time evolution of the number of undecayed nuclei $N$ in a given radioactive sample or the amount of electric charge $Q$ at the plates of a charged capacitor connected to a resistor with resisstance $R$.

The second exercise is related to a $2^{nd}$ order linear ODE with constant coefficients. This kind of equation is ubiquitos in physics starting from the elastic pendulum and can be encountered in every system that exhibits oscillatory behavior.

The third ODE, a $2^{nd}$ order nonlinear equation known as the Korteweg-de Vries (KdV) equation, can model solitons in ocean waves, fiber optics modes, and Bose-Einstein condensates in Quantum Statistical Mechanics. This example is quite interesting because it shows that PINNs have the potential to resolve complicated dynamics. 
