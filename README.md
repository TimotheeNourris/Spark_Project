# Spark_Project

This project is a pure Data Engineering project, which is meant to simulate a full pipeline action.

## Technologies : 
Docker --> infrastructure    
Hadoop --> data lake    
Spark --> processing  
Scala --> ingestion  
Delta Lake --> storage  
Trino --> SQL query  
Metabase (Or Power BI) --> dashboard  
Airflow- -> orchestration  


## Structure du projet :  
sncf-data-engineering-project  
│  
├── docker-compose.yml  
├── .env  
│  
├── spark-jobs  
│   ├── build.sbt  
│   └── src/main/scala  
│       └── SncfIngest.scala  
│  
├── airflow  
│   └── dags  
│       └── sncf_pipeline.py  
│  
├── data  
│   ├── raw  
│   └── parquet  
│  
├── scripts  
│   └── setup.sh  
│  
└── README.md  


## But final de la pipeline :  
Task 1 : récupérer API  
Task 2 : lancer Spark job  
Task 3 : vérifier les données  
Task 4 : update tables  
Task 5 : refresh dashboards  
