# Hadoop_Project
PySpark, Sqoop, HDFS, Hive Case Scenarios

# Hadoop_Project
PySpark, Sqoop, HDFS, Hive Case Scenarios
## Project Background
These are the case scenarios which i accomplished during online Big Data BootCamp(www.Itversity.com). So these problems are solved on 12 node hortonworks cluster in the distributed environment. Main goal was to comprehend Hadoop Big Data Ecosystem and learn stuff per the industry level standards. 

## Frameworks/Libraries/Engine/Scripting language/Cluster:
1. HDFS(Hadoop Command Line)
2. Sqoop
3. Hive
4. Pyspark(Spark(Using Python), SparkRDD, SparkSql, Pyspark-DataFrames operations)
5. Jupyter notebook(IDE)
6. MySql Database
7. Environment(unix/linus shell)
8. Cluster
 
# Individual breakdown of coverage per each component:
  1. HDFS: Hadoop fs commands for  moving ,copying(from/to hdfs or local), permissions, locating , files and blocks   
     information etc. 
  2. Sqoop: Used for integrating hdfs to relational databases and hive. Creating jobs to perform delta uploads or 
     merging to the existing files or tables.
  3. Hive: Used to create  warehouse to convert unstructured data to structured to perform analytics on it.
     Query performance was improved by creating  dynamic and static partitions using list, range and hash techniques and   
     saving the files in avro, parquet, orc, json, text using compressions like snappy, gzip etc.
  4. Pyspark: Structured and unstructured data was analyzed using spark RDD, SparkSql, Python dataframe operations to 
              clean, manipulate and generate analysis on it.
              Reading the data from different file formats like parquet, avro, json, sequence, text, csv, orc format and 
              saving the results/output using gzip, snappy to attain efficiency and converting Rdd to dataframes or 
              dataframes to RDD 
  5. Mysql Database: To export and import the relational data to/from HDFS.
  6. Unix/linux Shell: For managing local file operations as well as finding, locating the driver files,  
                       config files and installing/uninstalling applications.
  7. Cluster: To simulate the real-time scenario i have used 12 nodes hortonworks cluster.(https://labs.itversity.com/#/)


## Data Model Used during this project:
![data model](https://user-images.githubusercontent.com/23733029/30353365-47ca306c-97da-11e7-9866-ec52adfae318.png)

## Skillsets earned during this BootCamp:
  # Data Ingestion
   The skills to transfer data between external systems and your cluster. This includes the following:
   
    1. Import data from a MySQL database into HDFS using Sqoop
    2. Export data to a MySQL database from HDFS using Sqoop
    3. Change the delimiter and file format of data during import using Sqoop
    4. Ingest real-time and near-real-time streaming data into HDFS
    5. Process streaming data as it is loaded onto the cluster
    6. Load data into and out of HDFS using the Hadoop File System commands

## Transform, Stage, and Store
 Convert a set of data values in given format in HDFS into new data values or a new data format and write them into HDFS.
 
    1. Load RDD data from HDFS for use in Spark applications
    2. Write the results from an RDD back into HDFS using Spark
    3. Read and write files in a variety of file formats
    4. Perform standard extract, transform, load (ETL) processes on data

## Data Analysis
 Use Pyspark  to interact with the metastore programmatically in your applications. Generate reports  
 by using queries against loaded data.

    1. Use metastore tables as an input source or an output sink for Spark applications
    2. Understand the fundamentals of querying datasets in Spark
    3. Filter data using Spark
    4. Write queries that calculate aggregate statistics
    5. Join disparate datasets using Spark
    6. Produce ranked or sorted data
    
  
  Deliverables:
  Uploaded my Jupyter Notebook with the problem Scenarios and their solutions/approach to solve them.
  Here is the link to Notebook : 
  
    
 

