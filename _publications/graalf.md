---
title: "GrAALF: Supporting Graphical Analysis of Audit Logs for Forensics"
collection: publications
permalink: /publication/graalf
excerpt: 'In this paper we introduce an easy to use, flexible tool for forensics analysis'
date: 2019-09-03
venue: 'Journal 1'
paperurl: 'https://arxiv.org/abs/1909.00902'
citation: 'Setayeshfar, O., Adkins, C., Jones, M., Lee, K.H. and Doshi, P., 2019. GrAALF: Supporting Graphical Analysis of Audit Logs for Forensics. arXiv preprint arXiv:1909.00902.'
---

[Download paper here](https://arxiv.org/abs/1909.00902

# Abstract 

System-call level audit logs often play a critical role in computer forensics. They capture low-level interactions between programs and users in much detail, making them a rich source of insight on malicious user activity. However, using these logs to discover and understand malicious activities from a typical computer that produces more than 3GB of logs daily is both compute and time intensive. We introduce a graphical system for efficient loading, storing, processing, querying, and displaying system events to support computer forensics called GrAALF. In comparison to other related systems such as AIQL [13] and SAQL [12], GrAALF offers the flexibility of multiple backend storage solutions, easy-to-use and intuitive querying of logs, and the ability to trace back longer sequences of system events in (near) real-time to help identify and isolate attacks. Equally important, both AIQL and SAQL are not available for public use, whereas GrAALF is open-source. GrAALF offers the choice of compactly storing the logs in main memory, in a relational database system, in a hybrid main memory database system, and a graph-based database. We compare the responsiveness of each of these options, using multiple very large system-call log files. Next, in multiple real-world attack scenarios, we demonstrate the efficacy and usefulness of GrAALF in identifying the attack and discovering its provenance. Consequently, GrAALF offers a robust solution for analysis of audit logs to support computer forensics