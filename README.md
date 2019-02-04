# earthquake_Mag_by_Modeling_ML
Using magnitude data from earthquake rupture simulations, we predict maximum possible magnitude of induced earthquakes using Machine learning (ML) approach. 

We run 4000 earthquake rupture simulations with different initial parameters and then use these to predict the magnitude of induced earthquakes. Our simulations are performed using a code that solves for fault slip and then solves for the earthquake wave propagation using 3D seismic wave equation. We use Neural Networks of machine learning approach to model the output using given input parameters.
We use both regression as well as Classification method of ML to learn more about induced earthquakes. The classification problem is used to describe the possibility of a rupture to grow into a hazardeous earthquake and then the regression problem is used to describe the magnitude of the earthquake under given initial fault geometry and stress conditions.

