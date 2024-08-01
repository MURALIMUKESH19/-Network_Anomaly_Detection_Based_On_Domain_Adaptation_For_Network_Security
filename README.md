# 🛡 Network Anomaly Detection Based on Domain Adaptation for 5G Network Security

## Overview
This project presents a network anomaly detection system utilizing Domain Adaptation (DA) techniques to enhance security in 5G networks. The system addresses the challenges of data domain divergence and improves detection accuracy by applying DA methods. The approach focuses on reducing domain divergence through Probability of Anomaly Detection (PAD) measurement, enabling effective anomaly detection across different network domains.

## Introduction
With the rapid advancement of 5G networks, new security challenges have emerged, necessitating advanced solutions for network anomaly detection. This project leverages Domain Adaptation (DA) to address the problem of domain divergence between source and target datasets, improving the accuracy and robustness of anomaly detection systems in 5G environments.

## Modules

### Dataset Extraction 📊
- *Source Dataset:* [NSL-KDD](https://www.unb.ca/cic/datasets/nsl-kdd.html)
- *Target Dataset:* [UNSW-NB15](https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Dataset/)

### Domain Adaptation (DA) and Unsupervised Domain Adaptation (UDA) 🔄
- *Feature Extractor:* Utilizes autoencoders to learn efficient representations of input data.
- *Network Anomaly Classifier:* Implements a competitive learning approach with class and domain classifiers.

### Performance Evaluation 📈
The system's effectiveness is evaluated using the following metrics:
- *Accuracy:* Measures overall correctness of anomaly detection.
- *Precision:* Assesses the proportion of true positives among predicted positives.
- *Recall:* Evaluates the proportion of true positives among actual positives.
- *F1-Score:* Combines precision and recall into a balanced metric.

## Software Requirements 💻
- *Operating System:* Windows 8, 8.1, and 10
- *Front End:* Java Swing JFrame
- *Coding Language:* Core Java
- *Backend:* MySQL
- *Software Tool:* NetBeans

## 📊 Results

The experiments demonstrate the following:

- *Effectiveness*: The DA-based approach effectively detects anomalies across different network domains.
- *Improvement*: The approach shows enhanced accuracy and adaptability over traditional methods.

## 🔍 Future Work

Future research directions include:

1. *🔧 Refinement of DA Techniques*: Further improving the Domain Adaptation techniques to boost anomaly detection performance.
2. *📡 Expansion to 5G Scenarios*: Extending the application of the proposed method to additional 5G network scenarios.
3. *⏱ Real-time Integration*: Exploring the integration of the approach with real-time network monitoring systems.
