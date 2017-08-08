# linearized-pendulum
Linearizing pendulum with MATLAB Simulink

A simple model of pendulum, linearized around a trajectory. At initial positoin, te reuslt is exact. As time grows, the linearization error grows as well. Therefire, periodically, the linearization is 'resetted', by resetting and feeding new initial value to the integrator (or the solver).  
