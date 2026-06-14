# AI-Powered Bottleneck Detection

This repository contains the implementation of Graph Convolutional Networks (GCN) and Graph Attention Networks (GAT) for detecting bottlenecks in systems. 

## Contents

- `GCN_.ipynb`: Graph Convolutional Network implementation and bottleneck analysis.
- `GAT_.ipynb`: Graph Attention Network implementation and bottleneck analysis.

## Overview

The models leverage graph neural network architectures to analyze network structures and identify critical points that act as bottlenecks. By applying GCN and GAT methodologies, the system efficiently captures spatial dependencies and node relationships to isolate constrained pathways.

## Performance Metrics

The framework combines spatio-temporal bottleneck prediction (GCN/GAT + LSTM) with Double DQN (DDQN) for adaptive routing.

**Final Routing Performance:**
- **GCN-DDQN:** 98.0% Success Rate | 4,422.9 paths/s Throughput | 0.27 ms Latency
- **GAT-DDQN:** 98.5% Success Rate | 3,908.9 paths/s Throughput | 0.40 ms Latency

**Spatio-Temporal Prediction (Accuracy):**
- **GCN + LSTM:** 90.82%
- **GAT + LSTM:** 100.0%
