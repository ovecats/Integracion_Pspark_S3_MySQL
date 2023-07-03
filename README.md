# ***INTEGRACION de Spark con MySQL y S3***

Spark can read and write data from anywhere.

Spark puede leer y escribir datos desde cualquier lugar

# Why we need Integration ¿pq necesitamos integracion?

To fast data processing.

Para un procesamiento rapido de datos

# Extract , Tansformation and Load

To create data pipline we need ETL .

Para crear un tuberia necesitamos un ETL.

## PySpark Integration with S3.

Read data from S3.

# PySpark Integration with MySQL.

Read data from MySQL

#Requirements: AWS Cloud

- Amazon Simple Storage Service (Amazon S3)

# Code Description

    File Name : S3.ipynb , Mysql.ipynb, S3.py and Mysql.py
    DataSets : airlines1.csv
    File Description : Integration of pyspark with S3 and MySQL.

#NOTE :- use findspark library when executing python script

Use la biblioteca findspark al ejecutar el script

- import findspark
- findspark.init()

## Steps to Run

There are two ways to execute the end to end flow.

hay dos formas de ejecutar el flujo de extremo a extremo.

- Command Prompt => python script
- spark_path spark-submit file_path
- spark_path => <path_to_spark>>
- file_path => <path_to_file>
- Data file path is same as script file path

eg. <C:\Users\admin\Desktop\spark\bin>spark-submit C:\Users\admin\Desktop\Integration\S3.py>

- IPython

### Modular code

- Create virtualenv
- Install requirements `pip install -r requirements.txt`
- Run Code `python S3.py`
- Run Code `python Mysql.py`
- Check output for all the visualization

### IPython

Follow the instructions in the notebook `S3.ipynb`
Follow the instructions in the notebook `Mysql.ipynb`
