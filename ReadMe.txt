Description of benchmark test implementations for the paper
by Versace et al. (2008). KInNeSS: A modular framework for 
computational neuroscience, Submitted to Neuroinformatics. 

Specifically, this code can be used to simulate in Kinness 
either of the following two networks:

1. A network of spiking Hodgkin-Huxley neurons whose topology 
follows that used in the 'cobahh' model presented in: Brette 
et al. (2007). Simulation of networks of spiking neurons: a 
review of tools and strategies. J Comp Neurosci 23:349-98.

2. A network of quadratic Integrate & Fire neurons with the 
same network topology as in (1).

Simulation notes:
The input pattern is stored in 'paperTest0.png'. From the Kinness 
GUI, open file 'paperTest.xml' to load this pattern. This can be 
done by clicking File/Open...

The network of Hodgkin-Huxley cells is defined in 'paperTestHH.nml'. 
The network of quadratic Integrate and Fire cells is defined in 
'paperTestQIAF.nml'. Load either network from the Kinness GUI 
by clicking Network/Load... The structure of the loaded network is 
then easily accessed by clicking Network/Edit...

After loading both input and network files, the simulation can be run 
by clicking Simulation/Run...
