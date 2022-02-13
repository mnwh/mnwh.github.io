
### Mark Howell

![CARLA Logo](/CARLA.jpg "Text to show on mouseover").


### Development of embedded Continuous Action Reinforcement Learning Automata for cyber-physical systems

#### Background

Cyber-physical systems research has been identified as a key area of research by the US National Science Foundation (NSF). A cyber-physical system (CPS) is a system of collaborating computational elements capable of controlling physical entities. Mechatronic approaches can enhance the performance of traditionally mechanical devices and of critical importance to this is embedded real-time control.

Machine learning technologies have been extensively studied over the past few decades and provide a new methodology applicable to real-time modeling and control. The CARLA algorithm is an extension of Learning Automata technology that was developed at Loughborough University during a highly successful EPSRC project on the application of learning automata to advanced suspension control. Its methodology is well understood and has been applied in wide variety of different application. The fundamental principle is that the learning system iteratively adapts, in real time, within an environment containing high levels of background disturbance and stochastic uncertainty. The internal structures within the automaton vary to improve relevant pre-specified measures of system performance. The technique is appropriate for real-time systems modeling and control applications and can be applied to complex systems with many states and high degrees of non-linearity and uncertainty in system parameters.   

The embedded system implementation of the CARLA is a building block for the development of a reconfigurable multi-agent machine learning system. The modular nature of CARLA enables them to be connected as a network of interacting elements. With potential plug & play capabilities they offer continuous online monitoring and self-adjustment for plant variations and self-optimizing behavior against disturbances. The CARLA technology offers a fast product development cycle for automatic online process control tuning improvements. CARLA can be applied to online parameter identification and real-time system model estimation for performance and condition monitoring. Reconfigurable control and smart analytics for system degradation, health management and performance prediction and can be used as the basis of resilient control systems. A distributed network of CARLA collaborating computational elements can optimally control physical system and open a wide range of potential application of cyber-physical systems. The CARLA provide an intelligent mechanism to link computational and physical elements that have the capability to dramatically increasing the adaptability, autonomy, efficiency, functionality, reliability, safety, and usability of cyber-physical systems.

A few relevant publications are cited here:

•	M.N. Howell, T.J. Gordon, 'Continuous Action Reinforcement Learning Automata and their Application to Adaptive Digital Filter Design', Engineering Applications of Artificial Intelligence, Vol. 14/5, 549-561, Mar 2002.

•	M.N. Howell, M.C. Best, On-line PID tuning for engine idle-speed control using continuous action reinforcement learning automata, Journal of Control Engineering Practice, Vol. 8., Issue 2, 147 - 154, Feb 2000.

•	M.N. Howell, G.P. Frost, T.J. Gordon and Q.H. Wu., 'Continuous action reinforcement learning applied to vehicle suspension control', Mechatronics, Vol. 7, No. 3, pp263-276, 1997.

•	M.N. Howell, G.P. Frost, T.J. Gordon and Q.H. Wu., 'Real-time Learning of Vehicle Suspension Control Laws' Workshop on modeling in reinforcement learning at the Fourteenth International Conference on Machine Learning, ICML-97, July 1997

#### Research Problem:

The aim of this project is to implement machine learning algorithms on a microcontroller hardware platform. Various low cost, open-source microcontroller systems, such as Arduino and Raspberry-pi are available that enable the implementation of algorithms in an embedding hardware environment. A microcontroller implementation of these algorithms makes possible the development of cyber-physical systems that can enhance the performance of traditional mechanical devices by augmenting them with embedded actuation requiring real-time control. 

A novel learning technique, the Continuous Action Reinforcement Learning Automata (CARLA), will be implemented initially on the Arduino platform. The modular nature of the CARLA concept combined with the flexibility of an embedded implementation will rapidly expand its possible applications. These include online multi-objective optimization and adaptive controller tuning. A modular implementation demonstration the capabilities available will be produced and will be available as a general research tool for the development and enhancement of systems modeling and controller design technology.

#### Technical Approach:

The critical elements to the project are:

•	Investigate the application of low cost, open-source microcontroller systems to a modular embedded implementation of the CARLA algorithm. 

•	Investigate the versatility that the modular nature of the embedded CARLA implementation offers by developing a range of enterprise level applications.

•	Develop a demonstration tool to capitalize on the approach.

#### Significant Milestones:

The following milestones have been identified:

•	Restructure the CARLA algorithms into a form suitable for implementation on an embedded platform.

•	Implement, test and validate the embedded implementation on different test environments.

•	Connect several of the modular CARLA together to provide a standard controller structure and test the robustness of the approach.

•	Develop a black box modeling methodology using the technique for the modeling of complex industrial systems.

•	Provide a demonstration platform to show the real-time learning technology.

•	Visualization and convergence monitoring tools for performance assessment.

![Embedded Architecture](/Embedded_CARLA.png "Embedded CARLA Architecture").
