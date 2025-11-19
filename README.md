# AI-Driven-Network-Anomaly-Detection-and-Traffic-Analysis-On-AWS-Cloud
This project focuses on building an AI powered detection system that detects anomalies and suspicious activities in network traffic using AWS cloud services and advanced anomaly detection models.
This project integrates Network Security, Cloud Computing, DevOps, and Machine Learning, making it suitable for a Master’s-level cloud/cybersecurity project.

🚀 Project Summary

This project analyzes network flow logs to detect unusual traffic patterns such as:

DDoS attacks

Port scans

Unusual connection bursts

Data exfiltration attempts

Suspicious IP or port behavior

Using AWS services for data ingestion and ML-based anomaly detection models, the system provides actionable insights for cloud security monitoring.

🧠 Key Features

✔ AI/ML–based anomaly detection
✔ Analysis of VPC Flow Logs / network datasets
✔ AWS-based scalable data pipeline
✔ Preprocessing, feature engineering & model training
✔ Accurate anomaly classification
✔ Interactive visualizations
✔ Cloud-native alerting (SNS / CloudWatch)
✔ Production-ready architecture

🏗️ Architecture Overview

User Network Traffic  
        ↓  
AWS VPC Flow Logs  
        ↓  
Amazon S3 (Raw Logs Storage)  
        ↓  
AWS Lambda (Optional Preprocessing)  
        ↓  
S3 Processed Logs  
        ↓  
Jupyter Notebook / EC2 / Local Machine  
        ↓  
Machine Learning Model (Isolation Forest / LOF)  
        ↓  
Anomaly Detection Output  
        ↓  
CloudWatch / SNS Alerts


-> AWS Services Used

1. VPC Flow Logs
2. Amazon S3
3. AWS Lambda
4. AWS EC2/ SageMaker
5. Amazon CloudWatch
6. IAM roles and policies

-> DataSet Used

1. Source and Destination IP
2. Ports
3. Bytes Transferred
4. Packets
5. Protocol
6. Flow Duration
7. Connection State

-> Dataset Sources include:

AWS VPC Flow Logs
CICIDS / UNSW NB-15
Custom captured logs 

-> Data Preprocessing Steps:

1. Removal of invalid rows
2. Handling missing values
3. Scaling numerical features
4. Encoding categorical attributes

-> Feature engineering:

1. Bytes per second
2. Packets per flow
3. Unique target connections
4. Traffic bursts

-> Machine Learning Models:
1. Isolation Forest
2. Local Outlier Factor(LOF)
3. One-Class SVM
4. Random Forest (Supervised)

-> Results

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 94–96% |
| Precision | 88–90% |
| Recall    | 92–95% |
| F1 Score  | ~0.93  |

-> Visualisation Outputs
1. Anomaly Score Graph
2. Traffic Distribution
3. Heatmaps
4. Normal vs Anomaly Scatter Plots
5. Feature Correlations

-> Security Usecases Detected
1. Port Scanning Attempts
2. DoS/DDoS attack patterns
3. Unusual Outbound Traffic
4. High frequency connection bursts
5. Traffic from Unknown IPs
6. Abnormal Protocol Behavior

-> Project Overflow
1. Clone the Repository
   
git clone https://github.com/SAAI-2020/AI-Driven-Network-Anomaly-Detection-and-Traffic-Analysis-On-AWS-Cloud
cd AI-Driven-Network-Anomaly-Detection-and-Traffic-Analysis-On-AWS-Cloud

2. Install dependencies

pip install -r requirements.txt

3. Open the jupyter Notebook

jupyter notebook

4. Upload or Load Network log data

Use:
flowlogs.txt
AWS VPC Flow Logs
Any CSV-based network dataset

5. Run all notebook cells

Use:
preprocess data
train ML model
detect anomalies
generate graphs

-> Tools, Technologies, Skills:

Python
Pandas/NumPy
Scikit Learn
Matplotlib/Seaborn
AWS Cloud (S3,VPC,Lambda,EC2,CloudWatch)
Network Security Concepts
ML: Isolation Forest, LOF, OCSVM
Data Engineering
Anomaly Detection Systems

🏁 Conclusion

This project successfully demonstrates:

1. Real-world cloud security monitoring
2. Application of ML to network traffic analysis
3. Scalable cloud-native architecture
4. Strong accuracy and anomaly detection performance

It is a high-value Master’s-level cloud/cybersecurity project and highly relevant for roles such as:

1.Cloud Engineer
2.Security Analyst
3.SOC Analyst
4.Cybersecurity Intern
5.Network Engineer

🚀 Future Enhancements

Planned improvements:

1.Real-time detection using AWS Kinesis
2.Deployment via AWS SageMaker
3.Advanced deep learning (Autoencoders / LSTMs)
4.Integration with ELK / Splunk
5.Web dashboard (Streamlit / Dash)
6.Automated threat classification


👤 Author

Sai Vignesh Kumar
Master's in Computer Science – UIS Springfield
Cloud | Networking | Cybersecurity | AI

   





Dataset Used 
