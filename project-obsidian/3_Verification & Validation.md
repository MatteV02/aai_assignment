# Verification
I plan to verify the correct behavior of the model by performing statical analysis of the code (code review) and code execution with logging on small simulation times.

# Validation
Some run characteristics can be computed analytically without running the simulation. The idea is to compare run statistics with the output of those close formulas.

- Little's Law: will check the simulation WIP and flow time
- Utilization: it is possible to estimate beforehand utilization of each working center and compare it with simulation utilization
- throughput: run throughput should be equal to arrival time if the system is stable

