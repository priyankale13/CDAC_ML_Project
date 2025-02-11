# CDAC_ML_Project
Title: Unsupervised Anomaly Detection in Cloud Network Traffic

Dataset: According to technical paper -"CloudWatching: Understanding Attacks Against
Cloud-Hosted Services", data was collected from a combination of honeypots, network telescopes, and educational networks.

Data source: https://scans.io/study/cloud_watching

Objective
This project aims to analyze cloud network traffic using unsupervised machine learning techniques to detect anomalies that may indicate cyber threats.

Methodology
1.Preprocessing
	-Removing null value columns.
	-Removing duplicate rows.
	-Convert columns containing dictionaries and json strings into single valued fields.
	-One hot encoding on object, categorial datatypes columns.
	
2.Anomaly Detection using Unsupervised ML
	-DBSCAN (Density-Based Clustering) for identifying high-density attack clusters.
	-Isolation Forest for detecting outliers based on statistical behavior.

3.Evaluation 
	-Use silhouette assess model performance.

Concluding remark 
The results of this study can contribute to proactive threat detection, enabling cloud providers and security teams to mitigate risks before they escalate.
