# Architecture Design Document

## Contents

1. Introduction
1.1 What is Architecture Design Document?
1.2 Scope
Architecture
2.1 Tableau Architecture
2.2 Tableau Server Architecture
2.3 Gateway/Load Balancer
2.4 Application Server
2.5 VIZQL Server
2.6 Data Engine
2.7 Backgrounder
2.8 Data Server
2.9 Tableau Communication Flow
Deployment
3.1 Deployment Options in Tableau
3.2 Single Node Architecture
3.3 Three Node Architecture
3.4 Five Node Architecture

### 1. Introduction

Our Indian Crop Analysis Prediction project aims to revolutionize agriculture by leveraging advanced data analytics and machine learning techniques. By analyzing extensive data sets related to crop yields, weather patterns, soil composition, and market trends, we seek to develop accurate predictions for crop productivity and identify potential risks and opportunities. This project will empower farmers and policymakers with actionable insights to make informed decisions, optimize resource allocation, mitigate crop failures, and maximize agricultural output. By harnessing the power of technology, we strive to enhance food security, improve livelihoods, and drive sustainable growth in India's agricultural sector.

### 2.Architecture

#### Tableau Server Architecture

Tableau's n-tier, highly scalable client-server architecture supports desktop-installed software, web clients, and mobile clients. Fast and adaptable deployments are supported Tableau's n-tier, highly scalable client-server architecture supports desktop-installed software, web clients, and mobile clients. Fast and adaptable deployments are supported by the Tableau Server architecture.

<figure markdown>
  ![Image title]https://whimsical.com/architecture-design-JMYD1hZjXPz5mYSvbuTHnW@2bsEvpTYFZsxPKLNiZgecZFkcdGpeHh4SaY/600x400/){ width="300" }
  <figcaption>Tableau server is internally managed by the multiple server processes.</figcaption>
</figure>
