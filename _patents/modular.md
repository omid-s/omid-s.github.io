---
title: "Automated software safeness categorization with installation lineage and hybrid information sources"
collection: patents
permalink: /patents/modular
excerpt: 'This patent explins a modular system that calulates how safe a software is based on its lineage, behaviours and third party sources'
date: 2017-08-11
venue: 'US&International Patent'
paperurl: 'https://patents.google.com/patent/US20190050571A1/en'
citation: 'Rhee, J., Wu, Z., Korts-Parn, L., Jee, K., Zhichun, L.I. and Setayeshfar, O., NEC Corp and NEC Laboratories America Inc, 2019. Automated software safeness categorization with installation lineage and hybrid information sources. U.S. Patent Application 16/040,086.'
---


# Abstract 

Systems and methods are disclosed for enhancing cybersecurity in a computer system by detecting safeness levels of executables. An installation lineage of an executable is identified in which entities forming the installation lineage include at least an installer of the monitored executable, and a network address from which the executable is retrieved. Each entity of the entities forming the installation lineage is individually analyzed using at least one safeness analysis. Results of the at least one safeness analysis of each entity are inherited by other entities in the lineage of the executable. A backtrace result for the executable is determined based on the inherited safeness evaluation of the executable. A total safeness of the executable, based on at least the backtrace result, is evaluated against a set of thresholds to detect a safeness level of the executable. The safeness level of the executable is output on a display screen.