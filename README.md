# S3-Quicksight-Visualization-01
Project: Visualizing Amazon Bestsellers with QuickSight

To explore data visualization on AWS, I created interactive dashboards using Amazon QuickSight and a dataset of 50,000 best-selling products from Amazon.com.

	1.	Dataset Preparation
I downloaded a large CSV file and a manifest.json file containing metadata. After updating the manifest to match my S3 path, I uploaded both files to an S3 bucket 

2.	S3 + QuickSight Integration

Inside QuickSight, I connected the service to my S3 bucket using the manifest file. This allowed QuickSight to recognize and import the dataset seamlessly.

	3.	Building Visualizations
Once connected, I used QuickSight’s interface to drag and drop fields to explore trends like the most popular product categories and brands. I experimented with bar charts, pie charts, and line graphs to compare sales and ratings.

This project helped me understand how to connect data stored in S3 to QuickSight and create clear, insightful visualizations from raw datasets.
