# Enhanced-Security-in-Automobile-Edge-Computing-through-FL-Blockchain

Vehicular networks that consist of interlinked automobiles and transportation network are prone to cyberattacks due to the increased use of software and the presence of wireless interfaces. To counter these threats, intrusion detection systems can be tailored efficiently. In recent years, there has been significant development in detection of malicious attack traffic through the use of machine learning. However, traditional systems require powerful computing devices to continuously train and update complex network models, which can reduce the efficiency and effectiveness of the system due to resource constraints, untimely updates and dealing with large volumes of data. 

To address this issue, a cooperative intrusion detection mechanism which had been proposed has been improved with a classification based novel approach, that eases the burden by distributing the training model to distributed edge devices such as connected vehicles and roadside units. The previous approach has a slow response time to the increasing network issues. The proposed work offers a new approach through federated learning with the  Extra Trees Classification algorithm. The Extra Trees Classifier performs better than other machine learning models in all aspects. The proposed approach provides a faster response to security threats in automobile edge computing. The use of a distributed federated approach reduces the load on the server while maintaining confidentiality by aggregating modelsusing a blockchain.

# Results

![image](https://github.com/Atharva092002/Enhanced-Security-in-Automobile-Edge-Computing-through-FL-Blockchain/assets/95115949/64f9dfbe-2adb-42fb-bca6-7c1bfadc0554)

Figure 1 - Process Flow Diagram

![image](https://github.com/Atharva092002/Enhanced-Security-in-Automobile-Edge-Computing-through-FL-Blockchain/assets/95115949/a5232778-7476-4792-ba9d-914fbff18c39)

Figure 2 - Logistic Regression Confusion Matrix

![image](https://github.com/Atharva092002/Enhanced-Security-in-Automobile-Edge-Computing-through-FL-Blockchain/assets/95115949/cb48042d-747c-4dde-9416-97b4ae8c8434)

Figure 3 - KNN Confusion Matrix

![image](https://github.com/Atharva092002/Enhanced-Security-in-Automobile-Edge-Computing-through-FL-Blockchain/assets/95115949/95d660fd-0d80-44cd-b45b-bf8b90f7a985)

Figure 4 - Decision Tree Confusion Matrix

![image](https://github.com/Atharva092002/Enhanced-Security-in-Automobile-Edge-Computing-through-FL-Blockchain/assets/95115949/ce393760-6e69-44c9-aef1-677c8d97bfa6)

Figure 5 - Extra Trees Confusion Matrix

![image](https://github.com/Atharva092002/Enhanced-Security-in-Automobile-Edge-Computing-through-FL-Blockchain/assets/95115949/340332a1-8d87-4b01-8dff-88339dd456d4)

Figure 6 - Random Forest Confusion Matrix

# Comparison Report of all Chosen Models

|  Model	        |    Accuracy | Recall	|  Precision  | F1-Score  |Time to train |Time to predict | Total time |
|-------------------|-------------|---------|-------------|-----------|--------------|----------------|------------|
|  Logistic	        |    44.85%	  | 26.44%	|  77.99%	  | 39.49%	  | 0.92	     |  0.01	      |   0.93     |
|  KNN	            |    88.36%	  | 85.12%	|  97.45%	  | 90.87%	  | 0.01	     |  220.09	      |   220.10   |
|  Decision Tree	|    79.23%	  | 73.28%	|  95.06%	  | 82.76%	  | 1.39	     |  0.02	      |   1.41     |
|  Extra Trees	    |    93.07%	  | 97.09%	|  93.03%	  | 95.01%	  | 2.76	     |  0.42	      |   3.17     |
|  Random Forest	|    92.13%	  | 91.75%	|  96.51%     | 94.07%	  | 4.46	     |  0.52	      |   4.98     |
|  MLP (Keras)	    |    90.27%	  | 90.27%	|  90.27%	  | 90.27%	  | 29.66	     |  7.41	      |   37.07    |
|  GRU (Keras)	    |    86.29%	  | 86.29%	|  86.29%	  | 86.29%	  | 76.84	     |  21.16	      |   98.01    |

# Conclusion

In conclusion, the study finds that among the five ML models evaluated, the Extra Trees Classifier is the best performing model. This model can be effectively deployed on vehicles as part of a federated learning scenario, with the leader model running on RSUs that act as nodes in a blockchain network.

The performance metrics of various ML models used on the dataset are compared in the table. 
Accuracy, recall, precision, F1-score, time to train, time to forecast, and overall time are some of these metrics. It was observed that the Extra Trees Classifier had the best accuracy—93.07%—which is significant for this particular experiment. It is also important to note that the KNN model outperformed the Extra Trees Classifier in terms of precision score. 

However, it is important to understand that for an IDS system which has low accuracy, it may not detect all attacks, leaving the system vulnerable. In contrast, if an IDS system has high precision but low accuracy, it may generate false alarms which can be expensive. Therefore, for an IDS system accuracy is of paramount importance and thus, Extra Trees Classifier becomes the most ideal model to be deployed on this architecture
