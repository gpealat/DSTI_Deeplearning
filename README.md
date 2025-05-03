# DSTI_Deeplearning

This repository is a holding repo for all the sub projects we created for the deep learning class.

# Introduction 

Network security traditionally relies on signature-based detection (e.g., Snort, Suricata) or machine learning models analyzing packet headers and payload statistics. However, modern cyberattacks—such as zero-day exploits, polymorphic malware, and adversarial evasion techniques—increasingly bypass these methods by mimicking benign traffic or using obfuscated payloads. 

This project proposes an unconventional use of Natural Language Processing (NLP) and Computer Vision (CV) to detect malicious TCP/IP packets by interpreting raw network traffic as both structured textual data and visual patterns. Unlike traditional approaches, we treat packet analysis as: 

An NLP problem: Analyzing byte sequences as "language" (e.g., ASCII/hex payloads, protocol syntax) using transformers/RNNs to detect anomalies. 

A CV problem: Visualizing packets as 2D entropy maps, byte distribution heatmaps to spot structural irregularities. 

Given the size of the data and the resulting models, we have decided to create different repos which will hold the different subprojects.

# Computer vision projects:

We have created 2 sub projects:

1. Implementation of a model from a research paper

During our initial research, we have found the paper named [**Intrusion Detection Using Tcp/Ip Single Packet Header Binary Image** ](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5000577) <br>
The first subproject located here [Subproject 1](https://github.com/afra-muhammad/Deeplearning-binary-IDS) is a tensorflow implementation of such paper.

2. Extenstion of this work

We have decided to extend the work above by adding a new type of data (payload entropy) and a more complex model with.
The implementation is located here [Subproject 2 ](gpealat/IDSDeepLearning: IDS Deep Learning Intrusion model).

# NLP Projects:

https://github.com/susmitha-ann/DeepLearning/tree/main 
