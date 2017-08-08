# linearized-pendulum
Linearizing pendulum with MATLAB Simulink

A simple model of pendulum, linearized around a trajectory. At initial condition, the result is exact. As time grows, the linearization error grows as well. Therefore, periodically, the linearization is 'resetted', by resetting and feeding a new initial value to the integrator (or the solver).  
