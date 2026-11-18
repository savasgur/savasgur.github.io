---
id: 10978792
title: "Evaluation of Post-Quantum Key Encapsulation Methods in 5G Core Network"
authors: [Corsi, Alessandro and Gür, Savas and Brighente, Alessandro and Conti, Mauro]
venue: WCNC
venueType: conference
year: 2025
status: accepted
isFirstAuthor: false
isCorrespondingAuthor: true
links:
  arxiv: "#"
  code: "10.1109/WCNC61545.2025.10978792"
emoji: ""
featuredImage: /images/publications/ale_savas.png
---

The fifth generation of mobile networks (5G) is among the critical infrastructures whose security and privacy requirements are paramount. Compared to previous generations, 5G leverages a service-based architecture where many Network Functions (NF), i.e., the set of microservices on which is based the architecture, need secure communication means. NFs can communicate using HTTP2, and despite not being required by the standard, they can use Transport Layer Protocol (TLS) to ensure data integrity and authentication across the network. However, with the expected arrival of quantum computers in the near future, traditional cryptographic algorithms are under significant threat. With the recent run for post-quantum standardization, the NIST selected possible candidate algorithms. However, no study evaluates whether such algorithms would be applicable in the 5G core without significant performance degradation. In this paper, we perform the first assessment of the feasibility of using post-quantum secure Key Encapsulation Mechanism (KEM) for the 5G core network. To this aim, we implemented and compared the performances of five algorithms among those selected during the NIST standardization process. We adapted those algorithms to implement them in a standalone 5G core implemented via Open5GS, and tested their performance when performing user registration. Our results show that the KY-BER768 achieves comparable performance to TLS in terms of UE registration time and CPU utilization, thus being a candidate solution to improve the security posture of the 5G core.