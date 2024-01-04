**IMPORTANT: Note all default PID values for increment reference**


## Basic Stability Tuning
### Before we fly, we must first hover without crashing.
- Set all I and D values to 0 
- Lower the P terms from the default by about 50%
- Check that the motors are stabilized correctly by moving the vehicle and the transmitter sticks. 
- Attempt a hover and note oscillations. 
- Increase the D gain in increments of ~20% of the default value. 
- Repeat until oscillations are dampened. 


## Tune for Good Control Authority
### Reducing the gains means the controller doesn't reach the target fast enough.
- Increase the P gain in ~15% increments, increasing the D gain in similar increments as needed. 
- Attempt a flight and note oscillations and response by commanding a fast roll or pitch change.
    - Very slow response indicates that the system is over-damped and the D gain should be lowered.
    - Low frequency oscillations indicate that more D gain is needed 
    - High frequency oscillations with good control response indicates the gains are set too high.
- Repeat and refine as the P and D gains are slowly increased together. 
Please note that this process requires individual treatment of each axis which can be done at the same
time, but should be thought of as independent things being tuned.


## Rock Steady Flight Tuning
### The vehicle might want to drift around even with no angle input.
- Increase I gains in increments of about 15% of the default gain values for each axis. 
- Do this for each axis until letting go of the sticks brings the vehicle to level and shows no drift.
    - Too high gains cause low frequency oscillations.