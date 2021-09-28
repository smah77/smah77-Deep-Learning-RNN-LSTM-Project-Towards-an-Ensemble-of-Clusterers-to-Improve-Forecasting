#“Towards an Ensemble of Clusterers to Improve Forecasting for Self-Driving Data Management”

o Preprocessing time-series data : In our project we are using the same preprocessing component of QueryBot5000 [11], where queries of identical templates (i.e, which are formed after removing some tokens and individual information from queries) are counted to predict the workload. 

o Clustering time-series data: 
	1) QueryBot 5000 Clustering
		1.1) Variant of DBSCAN
		1.2) Uses Cosine Similarity as Similarity measure

	2)K-Means with dynamic time warping 
		2.1) Variant of K-Means
		2.2)Uses Dynamic Time Warping as Similarity measure


o Forecasting of DB workload using LSTM(RNN), TensorFlow
