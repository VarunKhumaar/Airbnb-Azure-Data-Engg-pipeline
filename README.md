# Sydney Airbnb-Azure-Data-Engg-pipeline

Architecture:
![image](https://github.com/VarunKhumaar/Airbnb-Azure-Data-Engg-pipeline/assets/67249540/e81b4b78-bfce-4f03-8b55-51393c7e31a0)

Summary
- Using Azure Data Factory performed data ingestion for Airbnb dataset to load the raw data into Data Lake Gen 2 container
- Performed data transformations on the raw dataset using Azure Databricks
- Loaded the transformed data back to Data Lake Gen 2
- Loaded the dataset to Azure Synapse to perform analysis using SQL
- Finally, connected the table in Azure Synapse to Tableau

Final Dashboard: https://public.tableau.com/app/profile/varunkhumaar/viz/AirbnbSydney-AzureDataPipeline/Dashboard
![image](https://github.com/VarunKhumaar/Airbnb-Azure-Data-Engg-pipeline/assets/67249540/526928ba-3c19-43af-8672-e048be82c4fc)

_Note: The entire pipeline can be built in one of the Azure services itself, but different services have been used here just to get an understanding and hands-on experience with popular Azure products._

Ideas/Inspiration:
- Olympic Data Analytics | Azure End-To-End Data Engineering Project: https://www.youtube.com/watch?v=IaA9YNlg5hM
- Airbnb in Sydney 2021 | #VOTD: https://public.tableau.com/app/profile/johanna.josodipuro/viz/AirbnbinSydney2021/Dashboard1
- Airbnb in New York: https://public.tableau.com/app/profile/doris.nekesa/viz/AirbnbinNewYork_15792695848850/Airbnb
- InsideAirbnb: https://public.tableau.com/app/profile/j.trajkovic/viz/InsideAirbnb/InsideAirbnb

Data Source: http://insideairbnb.com/get-the-data/

