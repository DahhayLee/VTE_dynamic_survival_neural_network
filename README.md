# A dynamic survival neural network to predict the risk of clinical event
Codes of deep-Learning-based predictive survival networks, accompanying the paper  
> A dynamic survival neural network to predict the risk of venous thromboembolism among ovarian cancer patients: Model development and validation in electronic health record-based real-world settings (2023)  
Authors: Dahhay Lee, Seongyoon Kim, Sanghee Lee, Hak Jin Kim, Myong Cheol Lim, Hyunsoon Cho  

### Repository description
This repository contains jupyter notebooks of  
1. Classification models (MLP, multi-MLP),  
2. Survival neural networks (cause-specific, competing risks) based on [DeepHit](https://github.com/chl8856/DeepHit) (Lee et al., 2018)
3. Dynamic survival neural network

### Data requirement
Study data should include  
1. The event indicator  
2. Time-to-event  
3. Static variables e.g. demographic information of patients, tumor stage, etc.
4. Longitudinal variables e.g. laboratory test results, treatment information, etc.  
