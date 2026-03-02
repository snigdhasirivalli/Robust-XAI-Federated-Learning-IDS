# Robust Explainable AI for Distributed Network Security

A Federated Learning framework using Robust Explainable AI (LIME &amp; SHAP) for network intrusion detection across Edge, Gateway, and Cloud layers.

This project implements a multi-layer security architecture (Edge, Gateway, Fog, Proxy, and Cloud) to identify network threats. It features:

Hybrid Models: Combines Autoencoders, Random Forests, and TCN (Temporal Convolutional Networks) for robust classification.

Explainable AI (XAI): Uses LIME and SHAP to visualize why the model flagged specific network traffic as an "Attack" versus "Normal."

Federated Learning: Demonstrates High-Frequency Learning (HFL) results with an global accuracy of approximately 99.35%.

Visualizations Included in Video:
Feature Importance: Bar graphs showing which network features (like TotPkts, SrcJitter, and Loss) most influence the prediction.

Confusion Matrices: Detailed accuracy reports for each network layer.

Accuracy Comparison: A final bar chart comparing performance across all distributed layers.
