---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Below is a brief summary of my main research areas.

# Quantum Key Distribution

Quantum Key Distribution allows for Alice and Bob to prepare and transmit quantum states over an untrusted quantum channel, perform measurements, communicate classically over an authenticated (but insecure) classical channel, and produce a *shared secret key*.
The key produced is universally composable, and can be subsequently used in any cryptographic protocol of one's choice. 
I am broadly interested in all aspects of Quantum Key Distribution. I am especially interested in working towards *practical* Quantum Key Distribution, from the theory side. 



During my PhD, I worked on the security proof of variable-length QKD protocols. Such protocols are practically relevant, since they allow users to adaptively determine the length of the final key produced, depending on observations during the protocol. This is in contrast to fixed-length protocols, that either produce a key of fixed-length or abort, and require careful (albeit untrusted) characterization of the honest behaviour of the quantum channel. 

*  **Security Proof for Variable-Length Quantum Key Distribution**.  [arXiv](https://arxiv.org/abs/2307.00576). Devashish Tupkary, Ernest Y.-Z. Tan, Norbert L&uuml;tkenhaus.

I also worked on applying the Postselection (a generic technique to reduce the analysis of arbitrary attacks to independent-and-indentically distributed attacks) technique to QKD protocols.
* **Postselection technique for optical prepare-and-measure QKD protocols**. Shlok Nahar, Devashish Tupkary, Yuming Zhao, Norbert L&uuml;tkenhaus, Ernest Y.-Z. Tan. *Manuscript under Preparation*. 

Previously, for my Master's thesis, I worked on improving the analysis of the *classical* part of QKD protocols.
My master's thesis involved improving the performance for QKD protocols by inventing improved ways of processing *classical* data in QKD protocols. This is particularly useful, since compared to hardware changes, such modifications can be implemented very easily.

* **Improved Keyrates for Quantum Key Distribution from two-way Classical Communication**. [link](https://www.uwspace.uwaterloo.ca/handle/10012/18772). Devashish Tupkary.

I have also worked on the correct analysis of  information leakage during two-way error-correction protocols in QKD, such as Cascade. 

* **Using Cascade in Quantum Key Distribution**.  [arXiv link](https://arxiv.org/abs/2311.01600). Devashish Tupkary , Norbert L&uuml;tkenhaus.







# Open Quantum Systems
There are a myriad number of ways to study the dynamics of systems weakly connected to baths. A common approach is to use a quantum master equation (QME) for the setup we are interested in studying, which typically requires various approximations to derive. Depending on the choice of approxmiations, a variety of quantum master equations can be obtained.

I am interested in studying the validity of various QMEs, *independent* of specific system-bath setups. What kind of master equations can predict thermalization correctly? or transport properties? or preserve complete positity?. What conditions do such requirements impose on the QMEs themselves? How can we derive such QMEs ?

My recent work lays down fundamental requirements on QMEs that must be satisfied in order to avoid physical inconsistencies. 


*  **Fundamental Limitations in Lindblad Descriptions of systems weakly coupled to baths**. [Phys. Rev. A 105, 032208](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.105.032208).
    Devashish Tupkary, Archak Purkayastha, Abhishek Dhar, Manas Kulkarni. 
 
 A follow up work addresses the question of whether a QME in Lindblad form can a) Predict thermalization when coupled to baths in thermal equilibrium and b) Preserve local conservation laws at the same time.  
 * **Searching for Lindbladians obeying local conservation laws and showing thermalization**. [Phys. Rev. A 107, 062216](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.107.062216). Devashish Tupkary, Abhishek Dhar, Manas Kulkarni, and Archak Purkayastha.