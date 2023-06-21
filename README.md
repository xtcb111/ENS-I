# ENS-I
The above codes are used as follows
## 1、Simulation & diagno
To run this file as the first step, you need to input the network structure(hamster_1.txt),the propagation probability of the individual (beta_.txt) , the time length of the propagation, and the initial number of seeds.Then, run the Simulation&diagno.cpp to generate the simulation propagation file (State.txt) and observation record (diagno.txt) as outputs.
## 2、Inference
Second, you need to input the network structure(hamster_1.txt),the propagation probability of the individual (beta_.txt) , observation record (diagno.txt), give the appropriate range of parameters (e.g. the number of samples,the upper and lower bounds of the probability of susceptible,the upper and lower bounds of the probability of propagation, a rational propagation probability range,the time length of the propagation) and run the infer.cpp to get infection probability data (infer.txt) as outputs.
## 3、DMP
Third, you need to input the network structure(hamster_1.txt),the propagation probability of the individual (beta_.txt) , observation record (diagno.txt), give the appropriate range of parameters (e.g. the upper and lower bounds of the probability of propagation or a rational propagation probability range,the time length of the propagation) and run the DMP.cpp  to get infection probability data (DMP.txt) as outputs.
