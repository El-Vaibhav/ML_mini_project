# Intrusion Detection System for DOS attacks

( Pls refer the Overview Presentation and Transforms_accuracy document for detailed study of the project)

# Overview 

This project focuses on developing an Intrusion Detection System (IDS) that uses Wavelet Transform for effective detection of network attacks. By Using the wavelet transform's ability to analyze both time and frequency, the IDS can identify subtle and abrupt changes in network traffic patterns. 

Trained with datasets like NSL-KDD, WSN-DS, NF-TON-IOT it can detect a wide range of cyber threats, including denial-of-service (DoS) attacks, probing, and unauthorized access attempts. The system uses machine learning to quickly and efficiently spot threats, even in resource-constrained environments like IoT devices and wireless networks, ensuring robust protection against both known and new attacks!

# Methodology 

![image](https://github.com/user-attachments/assets/d7098102-dd7f-4f16-b21c-e3730f2ed289)

# Results got so far 

Till now we have a got around 98% accuracy with classifiers like ada boost , cat boost , decision tree , random forest when used in hybrid mode.

Below are some of the results that we got initially with simple classifiers like Random Forest and Decision Tree

![image](https://github.com/user-attachments/assets/f25ae35f-da1a-418b-a250-e72ff27f6947)

![image](https://github.com/user-attachments/assets/629bfad6-9297-4c21-9b8d-3b7bc0e3bc7b)

![image](https://github.com/user-attachments/assets/aab919b9-bb76-4393-b8cb-ce4ab2f3c9fb)

![image](https://github.com/user-attachments/assets/9a793e1b-b038-4f52-8274-db518b20582e)

![image](https://github.com/user-attachments/assets/4d3a227e-14a7-48bc-9d36-68d6baf6996c)




# Used Wavelet Transform

We are moving from Time Domain Data to frequency domain as we believe  that mapping our data into a frequency can help detect small attacks  (possible threats) that might be ignored when using time domain data

The Transforms_accuracy document will explain in detail why we are choosing wavelet transforms only ...

![image](https://github.com/user-attachments/assets/0214bfa7-c8df-4f1a-a42b-6b659f5b0fbc)






