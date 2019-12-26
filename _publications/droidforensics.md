---
title: "DroidForensics: Accurate Reconstruction of Android Attacks via Multi-layer Forensic Logging"
collection: publications
permalink: /publication/droidforensics
excerpt: 'This paper is about android forensics.'
date: 2017-04-06
venue: 'AsiaCCS'
paperurl: 'https://dl.acm.org/citation.cfm?id=3052984'
citation: 'Yuan, X., Setayeshfar, O., Yan, H., Panage, P., Wei, X. and Lee, K.H., 2017, April. DroidForensics: Accurate Reconstruction of Android Attacks via Multi-layer Forensic Logging. In Proceedings of the 2017 ACM on Asia Conference on Computer and Communications Security (pp. 666-677). ACM.'
---

In this paper we propose an auditing system for android devices which imposes minimal overhead, and produces queryable logs. 


[Download paper here](https://kyuhlee.github.io/publications/asiaccs17.pdf)

# Abstract 

The goal of cyber attack investigation is to fully reconstruct the details of an attack, so we can trace back to its origin, and recover the system from the damage caused by the attack. However, it is often difficult and requires tremendous manual efforts because attack events occurred days or even weeks before the investigation and detailed information we need is not available anymore. Consequently, forensic logging is significantly important for cyber attack investigation. In this paper, we present DroidForensics, a multi-layer forensic logging technique for Android. Our goal is to provide the user with detailed information about attack behaviors that can enable accurate post-mortem investigation of Android attacks. DroidForensics consists of three logging modules. API logger captures Android API calls that contain high-level semantics of an application. Binder logger records interactions between applications to identify causal relations between processes, and system call logger efficiently monitors low-level system events. We also provide the user interface that the user can compose SQL-like queries to inspect an attack. Our experiments show that Droid Forensics has low runtime overhead (2.9% on average) and low space overhead (105 ~ 169 MByte during 24 hours) on real Android devices. It is effective in the reconstruction of realworld Android attacks we have studied.