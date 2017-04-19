# processor_simulator
Visualizing/Simulating a pipelined processor execution using C, flex, bison

Draw an SVG image of processor (with hazard detection and forwarding unit). 

Design a processor simulator, which reports, the time to execute a program and further gives a dump of (the contents) register file and memory. Assume each functional unit (to access) takes one cycle and a operating frequency of 2GHz. Assume all instructions/data are there in the cache. The memory/register file get updated in the respective write back stages.  You also need to keep a track of number of stalls and number of accesses to the instruction and data caches.
