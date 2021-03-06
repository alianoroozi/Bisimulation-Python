# Bisimulation-Python
Computing strong and weak (stutter) bisimulation equivalence classes of a graph (transition system) using NetworkX.
 
The code constructs a transition system using explicit model files. States and transitions are handled by NetworkX package of Python3.
 
It then applies Kanellakis Smolka algorithm to compute strong bisimulation and Groote Vaandrager algorithm to compute weak (stutter) bisimulation equivalence classes.


For more information on:
1. explicit model files, please see: http://www.prismmodelchecker.org/manual/Appendices/ExplicitModelFiles
2. strong bisimulation, please see: Section 7.1 of "Principles of model checking", Christel Baier and Joost-Pieter Katoen
3. Kanellakis Smolka algorithm, please see: Section 7.3 of "Principles of model checking", Christel Baier and Joost-Pieter Katoen
4. weak bisimulation and Groote Vaandrager algorithm, please see: Section 7.8 of "Principles of model checking", Christel Baier and Joost-Pieter Katoen
