 # 📌 Project Overview
## Analysis-of-the-condition-of-the-VVER-1000-core-based-on-data-from-the-in-reactor-monitoring-system <br />
     The purpose of this work is to improve the reliability of identifying changes in the state of VVER-1000 reactor cores through the development and implementation of additional methods and algorithms for monitoring the reactor core condition based on in-core monitoring system (ICMS) data, as well as the state of the in-core monitoring software (Grand), in order to ensure timely detection of physical processes occurring in the reactor core and to identify unreliable readings of the measuring system.<br />
     To solve this task, the Principal Component Method (PCA) is used.<br />
     The normal state of the reactor core is represented by a graph of the detector signal readings (DPZ) in the first two principal components, preserving up to 98% of the information contained in the original data. The Principal Component Method is one of the key approaches for reducing data dimensionality with minimal loss of information. The detection of transient processes in the reactor core is carried out by comparing the current state with the reference graph and is visualized on a map diagram.<br />
     The algorithms were applied to analyze the state of the core at Kalinin NPP during the sequential insertion of control rod clusters in order to verify the correct connection of measuring channels to the system.<br />
     The effectiveness of the proposed method is demonstrated using real operational data from Unit 2 of the Kalinin Nuclear Power Plant.<br />

 # 💻 INTRODUCTION
     The reactor core is the part of the reactor that contains the nuclear fuel, moderator, absorber, coolant, reactivity control devices, and structural elements designed to sustain a controlled nuclear fission chain reaction and transfer energy to the coolant. <br />
     From the perspective of accident classification, reactor core accidents are considered low-probability events, with an occurrence likelihood of 10⁻⁴ – 10⁻⁶ per reactor per year. However, the consequences of such failures are so severe that significant attention is given to reactor core safety control and operating conditions. The requirements for ensuring safe operation are becoming increasingly strict, taking into account the JSC “Rosenergoatom Concern” program to increase the power output of VVER-1000 reactor units up to 104% during 2007–2015, as well as recent events in Japan.<br />
     The subject of this study is the operating conditions of the reactor core, the informativeness of the measuring system, and the software of the in-core monitoring system (ICMS) for VVER-1000 reactors.<br />
     The main objective of the study is to improve the reliability of identifying changes in the state of VVER-1000 reactor cores by developing and implementing supplementary methods and algorithms, in addition to existing ones, for monitoring the core condition using ICMS data and the state of the in-core monitoring software (Grand). This aims to ensure timely detection of physical processes in the reactor core and to identify inaccurate readings of the measuring system, while enhancing the quality of information presentation and the efficiency of data analysis.<br />
     To achieve this objective, the following research methods were applied: analysis of the VVER-1000 ICMS structure and its information presentation to the operator; analysis of current methods for verifying the state of the measuring system and reactor core based on ICMS data; and development of methods and algorithms for analyzing the measuring system data and the ICMS software of VVER-1000.<br />
The relevance of this work lies in the need to implement additional monitoring methods for the state of the ICMS and reactor core of VVER-1000 reactors, due to design modifications of the ICMS and the increasing volume of data provided to operational personnel.<br />

 # 🎯 Key Objectives
1. Improve reliability of identifying changes in the state of VVER-1000 reactor cores.<br />
2. Develop and implement supplementary methods and algorithms for reactor core condition monitoring, in addition to existing ones.<br />
3. Ensure timely detection of physical processes in the reactor core.<br />
4. Identify inaccurate or unreliable measurements from the in-core monitoring system (ICMS).<br />
5. Enhance quality and efficiency of information presentation and analysis for operators.<br />
6. Analyze the ICMS structure and data presentation for VVER-1000 reactors.<br />
7. Evaluate existing verification methods of the measuring system and reactor core condition.<br />
8. Design new algorithms and methods for processing ICMS data and software outputs.<br />
9. Address the need for additional monitoring due to ICMS design modifications and increasing data volume.<br />

 # 🛠️ Tools and Technologies
1. Matlab / Simuling: Modelling and simualion<br />
2. GARANT information system: For VVER-1000 units in Russia, the ICMS software commonly used is “GRAND”, which supports monitoring, diagnostics, and validation of measurement channels, and helps operators identify both physical processes in the reactor core and unreliable detector readings.<br />

 # 🔒 Key Features
1. Real-time data acquisition – collects signals from in-core detectors (neutron flux, temperature, etc.) with high reliability.<br />
2. 3D core state reconstruction – calculates neutron flux, power distribution, fuel burnup, and temperature fields across the reactor core.<br />
3. Transient and anomaly detection – identifies deviations, transients, and abnormal processes through comparison with reference models.<br />
4. Measurement channel diagnostics – verifies the correctness of detector signals and identifies faulty or unreliable channels.<br />
5. Data reduction and analysis – applies methods such as the Principal Component Method to reduce dimensionality while preserving essential information.<br />
6. Visualization tools – provides operators with maps, graphs, and diagrams of core parameters for decision support.<br />
7. Integration with safety and control systems – supplies validated input for reactivity management and protection system functions.<br />
8. Support for power uprates and design modifications – adapts to expanded operational ranges (e.g., VVER-1000 uprating to 104%).<br />
9. Operator support functions – improves information clarity and analysis efficiency to enhance situational awareness in the control room.<br />
10. Mathematical Modelling - Simulate the in-core detectors and in-core monitoring system (ICMS).<br />
11. HMI - Monitor and adjust parameters in real-time.<br />

 # 📈 Conclusions and Results
1. Algorithms for analyzing and visually representing changes in the state of the VVER-1000 reactor core based on in-core monitoring system data have been developed and presented.<br />
2. Using the Principal Component Method, the initial ICMS measurement data are represented in a two-dimensional coordinate system of eigenvectors of the correlation matrix corresponding to the maximum eigenvalues, while preserving 98% of the original information.<br />
3. Processing of ICMS data from Unit 2 of the Kalinin NPP was carried out during the verification of the correct connection of DPZ sensors to the measuring system and during a transient process associated with the self-movement of control rod clusters.<br />
4. The obtained results demonstrated the effectiveness of the proposed algorithms for clear and prompt analysis of the reactor core state.<br />
5. The presented algorithms can be used in the development of an automated system for analyzing the state of the VVER-1000 reactor core.<br />

 # 💡 About VVER-1000
The VVER-1000 is a pressurized water reactor (PWR) with ~1000 MWe output. It uses light water as coolant and moderator, contains 163 fuel assemblies with enriched uranium fuel, and employs control rods and safety systems to ensure reliable, long-term operation in many countries.<br />

 # 👥 Author 
Muhammed Yasir Ayaz specialist degree in Nuclear Enginering National Research Nuclear University MEPHİ (Moscow Engineering Physics Institute)<br />
