#	Federated Learning for Privacy-Preserving Load Forecasting
Federated Learning  •  Privacy  •  Smart Meters  •  Load Forecasting

Utility companies want smart meter data to predict energy demand — but users want their privacy. Uploading raw consumption profiles to a central server creates significant privacy risks and faces increasing regulatory constraints under GDPR.  This project investigates Federated Learning (FL) as a solution: training a global demand forecasting model by aggregating only model updates, never raw data, from local devices. Each household or transformer station trains a local model on its own data; only gradient updates or model weights are shared with a central aggregation server.

## Research Questions
*	How much forecasting accuracy is sacrificed by using Federated Learning compared to a fully centralized model?
*	How does data heterogeneity across clients (non-IID data) affect model convergence and final accuracy?
*	Can Differential Privacy guarantees be added to the FL pipeline without unacceptable loss of forecast quality?

## Focus Areas
*	Implement a Federated Learning pipeline for 24-hour-ahead electricity demand forecasting across multiple clients.
*	Evaluate the accuracy trade-off between federated and centralized training under various data heterogeneity conditions.
*	Investigate privacy-enhancement techniques compatible with FL, such as Differential Privacy and Secure Aggregation.
*	Assess the communication overhead and convergence behavior of federated versus centralized approaches.


## Reading List
*	McMahan, B., Moore, E., Ramage, D. et al. "Communication-Efficient Learning of Deep Networks from Decentralized Data (FedAvg)." AISTATS, 2017.
*	Pirbazari, A.M., Sharma, E., Chakravorty, A., Elmenreich, W., Rong, C. "An Ensemble Approach for Multi-Step Ahead Energy Forecasting of Household Communities." IEEE Access, 2021.
*	Bousbiat, H., Faustine, A., Klemenjak, C., Pereira, L., Elmenreich, W. "Unlocking the Full Potential of Neural NILM: On Automation, Hyperparameters and Modular Pipelines." IEEE Transactions on Industrial Informatics, 2022.
