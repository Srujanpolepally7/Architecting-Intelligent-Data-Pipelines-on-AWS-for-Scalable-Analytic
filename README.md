**🚀 Overview**

This project demonstrates how to build an end-to-end cloud data pipeline using Amazon Web Services (AWS).
The pipeline automates the ingestion, transformation, storage, and visualization of large datasets—specifically the Spotify Dataset 2023.

By leveraging AWS services such as S3, Glue, Athena, and QuickSight, this project showcases a scalable and cost-effective way to implement modern data analytics architecture in the cloud.
<img width="1126" height="4" alt="image" src="https://github.com/user-attachments/assets/3effa19c-452f-49a1-81fe-ad87d2001acf" />

**🧱 Architecture**

The pipeline consists of the following stages:

Data Ingestion: Raw Spotify data stored in Amazon S3 (staging area).

ETL Processing: AWS Glue performs extraction, transformation, and loading into a refined data warehouse.

Data Cataloging: AWS Glue Crawler catalogs data and creates a searchable schema.

Querying: AWS Athena enables SQL-based analysis directly from S3.

Visualization: AWS QuickSight provides rich, interactive dashboards for insights.

<img width="1126" height="4" alt="image" src="https://github.com/user-attachments/assets/17758039-b2f9-4800-86aa-524d3e88e08e" />

**📊 Dataset**
Source: Spotify Dataset 2023 on Kaggle
<img width="1126" height="4" alt="image" src="https://github.com/user-attachments/assets/9be5a525-768c-40ca-b482-6fd668d38fea" />

**Contents:**

Albums: Album name, ID, popularity, release date

Artists: Artist details, followers, genres

Tracks: Track-level metadata with features such as energy and danceability

Audio Features: Loudness, valence, speechiness, etc.
<img width="1126" height="4" alt="image" src="https://github.com/user-attachments/assets/a1088b3d-ad2e-43f4-ab0f-ab63f45fc705" />

**⚙️ AWS Services Used**
Service	Purpose
Amazon S3	Storage for raw and processed data
AWS Glue	ETL transformation and data pipeline automation
AWS Glue Crawler	Data cataloging and schema generation
Amazon Athena	SQL-like querying of data in S3
Amazon QuickSight	Data visualization and dashboard creation
<img width="1126" height="4" alt="image" src="https://github.com/user-attachments/assets/48037be4-7b41-41c6-bc46-a52a8cfbfc60" />

**🧩 Step-by-Step Implementation**

Set Up IAM User with the necessary permissions.

Create S3 Buckets for staging and data warehouse layers.

Build Glue ETL Jobs to clean, transform, and join datasets.

Run Glue Crawler to create a data catalog and schema.

Use Athena to query the processed data.

Visualize Results in QuickSight through interactive dashboards.

<img width="1126" height="4" alt="image" src="https://github.com/user-attachments/assets/cf5121b6-b354-4fbc-af70-275125575359" />

**🧠 Key Learnings**

Designing modular cloud data pipelines using AWS Glue.

Automating schema detection with AWS Glue Crawler.

Executing serverless queries efficiently using Athena.

Creating scalable, shareable dashboards in QuickSight.

<img width="1126" height="4" alt="image" src="https://github.com/user-attachments/assets/f32ce3e0-536a-4c67-b554-c0e8d29c2b6e" />

**💡 Real-World Applications**
Music Recommendation Systems — enhance playlist personalization.

Market Insights — track genre and artist performance trends.

User Engagement Analytics — optimize content recommendations.

Business Intelligence — empower decision-making through data visualization.
<img width="1126" height="4" alt="image" src="https://github.com/user-attachments/assets/fb5d34a7-7505-40c1-9c0b-6b020ff8a768" />

**🧰 Prerequisites**

AWS Account (Free Tier works)

Basic knowledge of AWS Console

Dataset files (CSV format)
<img width="1126" height="4" alt="image" src="https://github.com/user-attachments/assets/e23fd292-db7e-4dfd-a44d-1e74bf8256ea" />

**🪄 Future Enhancements**

Integrate AWS Lambda for automation triggers.

Add DynamoDB for real-time ingestion.

Implement Redshift for data warehousing at scale.

Introduce Machine Learning insights with Amazon SageMaker.
