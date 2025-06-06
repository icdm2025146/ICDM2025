# Brain_Age_Prediction__Federated_Learning
##### OA : The ML model is trained individually with all silos data

##### OB: The ML model is trained with all silo data in a centralized setup

##### Pre‑H  : We will train the global model with the global data, train the local model with local silo data and updating the global model weights with the gradients.

##### Feature-H : First we will train the global model with the global data, then local silo data and global data feature harmonization using neuroCombat followed by training the local silos with harmonized data and updating the global model weights with the gradients.

##### Local Gradient-H : We will train the global model with the global data, train the local model with local silo data followed by harmonizing the local gradients and updating the global model weights with the aggregated (harmonized local) gradients.

##### Dual Gradient-H : We will train the global model with the global data, train the local model with local silo data, fine-tuned by global data, then followed by harmonizing the local gradients (gradients extracted from local ML model) and global (gradients extracted from locally fine-tuned ML model) gradients and updating the global model weights with the aggregated (harmonized) gradients.
