# Steps of a Simulation Study
==EACH of these step must be described in the assignment==
![[Screenshot from 2025-05-02 17-48-14.png]]
- **Discovery and orientation phase**
	- **Problem formulation**: problem must be clearly understood
	- **Setting objectives and overall project plan**
- **Model building phase**
	- **Model conceptualization**: start with a simple model, the build it towards greater complexity
	- **Data collection**: collect data from the conceptualized model to understand when it is enough feature-rich
	- **Model translation**: software implementation of the simulated model
	- **Model verification**: check whether the program is performed properly or not (unit testing)
	- **==Model validation==**: check whether the model is representing correctly the actual system behavior. Validation helps calibrating the model. Sometimes, discrepancies between model and the system can be insight to improve the model itself.
		- it is very important: invalid model deliver invalid decisions
- **Run phase**
	- **Experimental design**: which decisions should the model explore. It is defined the warm-up period, the length of simulation runs and the number of replicas. 
		- the objective is to perform unbiased estimates with low variance
		- design different scenarios: an easy one, a medium one and an hard one
- **Implementation phase**: implementation of real-world discoveries (show your results)
	- **Documentation and reporting**
	- **Implementation**