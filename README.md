This project is about detecting botnet attacks and DDoS attacks using Machine Learning and Deep Learning techniques.

A botnet is a group of infected devices controlled by an attacker. These devices are often used to perform DDoS (Distributed Denial of Service) attacks, where a large amount of fake traffic is sent to a server to make it unavailable for real users.
In this project, I used an IoT network traffic dataset that contains both normal traffic and attack traffic such as Mirai, Kaiten, and Qbot. First, I preprocessed the data by removing missing values, converting categorical data into numerical form, scaling features, and handling class imbalance using SMOTE.

Then, I trained multiple models like Random Forest, XGBoost, LSTM, and Bidirectional LSTM. Among them, deep learning models performed better because they can understand sequential patterns in network traffic.

I also used a Game Theory–Based Adaptive Security approach, where the attacker and defender are treated as players. Based on payoff values, the system chooses the best defense strategy to minimize attack impact.

Finally, I evaluated the system using accuracy, precision, recall, F1-score, and confusion matrix. This project helped me understand cybersecurity concepts, machine learning, and how intelligent systems can improve network security.”

