---
title: "Path-based program lineage inference analysis"
collection: patents
permalink: /patents/lineage
excerpt: 'This patent explins a methods for infering program lineage from a crowd sources enviroment'
date: 2017-08-11
venue: 'US&International Patent'
paperurl: 'https://patents.google.com/patent/US20190050562A1/en'
citation: 'Rhee, J., Wu, Z., Korts-Parn, L., Jee, K., Zhichun, L.I. and Setayeshfar, O., NEC Corp and NEC Laboratories America Inc, 2019. Path-based program lineage inference analysis. U.S. Patent Application 16/039,993.'
---

<!-- [Download paper here](https://kyuhlee.github.io/publications/asiaccs17.pdf) -->

# Abstract 

Systems and methods are disclosed for securing an enterprise environment by detecting suspicious software. A global program lineage graph is constructed. Construction of the global program lineage graph includes creating a node for each version of a program having been installed on a set of user machines. Additionally, at least two nodes are linked with a directional edge. For each version of the program, a prevalence number of the set of user machines on which each version of the program had been installed is determined; and the prevalence number is recorded to the metadata associated with the respective node. Anomalous behavior is identified based on structures formed by the at least two nodes and associated directional edge in the global program lineage graph. An alarm is displayed on a graphical user interface for each suspicious software based on the identified anomalous behavior.