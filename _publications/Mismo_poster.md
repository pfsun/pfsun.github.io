---
title: "Towards Robust Semantic Reverse Engineering of Control System Binaries"
collection: publications
permalink: /publications/Mismo_poster
venue: "Poster Session of the 28th USENIX Security Symposium (Usenix Security-19)"
date: 2019-8-15
citation: '<b>Pengfei Sun</b>, Luis Garcia, Saman Zonouz. <i>Poster Session of the 28th USENIX Security Symposium</i>. <b>Usenix Security 2019</b>.'
---
[[PDF]](https://www.researchgate.net/profile/Pengfei_Sun2/publication/334466560_Towards_Robust_Semantic_Reverse_Engineering_of_Control_System_Binaries/links/5d2c9ff9458515c11c33559b/Towards-Robust-Semantic-Reverse-Engineering-of-Control-System-Binaries.pdf)


## Abstract
The safety of critical cyber-physical IoT devices hinges on the security of their embedded software that implements control algorithms for monitoring and control of the associated physical processes, e.g., robotics and drones. Reverse engineering of the corresponding embedded controller software binaries enables their security analysis by extracting high-level, domain-specific, and cyber-physical execution semantic information from executables. We present MISMO, a domain-specific reverse engineering framework for embedded binary code in emerging cyber-physical IoT control application domains. The reverse engineering outcomes can be used for firmware vulnerability assessment, memory forensics analysis, targeted memory data attacks, or binary patching for dynamic selective memory protection (e.g., important control algorithm parameters). MISMO performs semantic-matching at an algorithmic level that can help with the understanding of any possible cyber-physical security flaws. MISMO compares low-level binary symbolic values and high-level algorithmic expressions to extract domain-specific semantic information for the binary's code and data. MISMO enables a finer-grained understanding of the controller by identifying the specific control and state estimation algorithms used. We evaluated MISMO on 2,263 popular firmware binaries by 30 commercial vendors from 6 application domains including drones, self-driving cars, smart homes, robotics, 3D printers, and the Linux kernel controllers. The results show that MISMO can accurately extract the algorithm-level semantics of the embedded binary code and data regions. We discovered a zero-day vulnerability 1 in the Linux kernel controllers versions 3.13 and above.