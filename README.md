## Damage Propagation Modelling(CMAPSS)

### Aircraft Engine Run-to-Failure Simulation

- Damage propagation was allowed to continue until a failure criterion was reached. A health index was defined as the minimum of several superimposed operational margins at any given time instant and the failure criterion is reached when health index reaches zero. Output of the model was the time series (cycles) of sensed measurements typically available from aircraft gas turbine engines.

- Prognostics here exclusively as the estimation of remaining useful component life. The remaining useful life (RUL) estimates are in units of time (e.g., hours or cycles). End-of-life can be subjectively determined as a function of operational thresholds that can be measured. These thresholds depend on user specifications to determine safe operational limits.

- An important requirement for the damage modeling process was the availability of a suitable system model that allows input variations of health related parameters and recording of the resulting output sensor measurements. The recently released C-MAPSS (Commercial Modular Aero- Propulsion System Simulation)

- C-MAPSS is a tool for simulating a realistic large commercial turbofan engine. The software is coded in the MATLAB® and Simulink® environment, and includes a number of editable input parameters that allow the user to enter specific values of his/her own choice regarding operational profile, closed-loop controllers, environmental conditions, etc

>- Data Set: FD001 ==> Train trjectories: 100, Test trajectories: 100, Conditions: ONE (Sea Level), Fault Modes: ONE (HPC Degradation)




