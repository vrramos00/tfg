VPLS scenario with two customer organizations

First cust(A) includes three final users
Second cust(B) includes two final users 

When starting the scenario we must wait for at least a minute so it's correctly configured. 
We can check the correct configuration by tracing pings between the final users of each cust.
We can also check the correct configuration with the 'ldpctl' in each PE. 

The VPLS configuration  is runned by the start.interfaces script in each PE, which also includes
the ospfd and ldpd scripts .
