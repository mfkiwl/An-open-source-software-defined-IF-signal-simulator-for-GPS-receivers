# An open source software-defined IF signal simulator for GPS receivers

Originally developed by Yafeng Li, with gratitude to Professor Li. The current version has been modified by Jie Sun.

Features
-------------------------------------------------------------------------------
This simulator is implemented in MATLAB to leverage easy-to-use feature of the interpreted language. 
The IF signal generation is driven by user-specified trajectory and real ephemeris data from IGS Rinex files. 
Configurable parameters are provided to set the characteristics of the IF samples, C⁄No, and front-end filter. 
The power spectral density and time-domain histogram of the generated IF signals are presented. The signals 
are further analysed and validated by a real software receiver. The results show the outputs of the receiver 
fit well with the configurations of the simulator. We expect this open-source simulator can offer researchers, 
students, and developers a useful tool for developing innovative algorithms with almost zero cost.

Update
-------------------------------------------------------------------------------
1. Fix some bug, modified the L1 signal generation vulnerability that produces IQ channel components.
2. An additional step for pseudorange calculation of each satellite has been added.
3. Including delays caused by the ionosphere.

Future
-------------------------------------------------------------------------------
Future updates will include simulation of IF signals for other GPS frequency bands. If you're interested, please follow me.
