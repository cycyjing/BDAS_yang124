## Code Third Party Dependency

In this project, the following open source third-party packages are used. Need to install PySpark, imbalanced-learn, numpy, pandas, matplotlib.
The download link for imbalanced-learn is https://imbalanced-learn.readthedocs.io/en/stable/install.html

## Main Directory Structure of the Code

###  Operating Environment

1. The code run under JupyterNotebook, the server environment is Ubuntu 16.04.4 LTS (GNU/Linux 4.4.0-1065-aws x86_64), Python3.5, Spark 2.1.1, hadoop-2.7
2. The server environment is AWS, 1 cpu 1G memory. 


### Source Directory

The source function code is unified in the "src" directory.

1. BDAS_yang124/src/Data_Understanding.ipynb corresponds to Step 1-4 in the report. After processing the data, generating the data file normalizer_df_pandas.csv.
2. BDAS_yang124/src/Data_model.ipynb corresponds to Step 5-8 in the report. According to Data_Understanding, generating the data file normalizer_df_pandas.csv for data analysis.


### Report Directory

1. BDAS_yang124/Datasets/Collage.csv is original data file.
2. BDAS_yang124/Datasets/normalizer_df_pandas.csv is data file generated after Data_Understanding data process.


### Code Running

1. Run the BDAS_yang124/src/Data_Understanding.ipynb in the JuputerNotebook environment to generate the data file normalizer_df_pandas.csv.
2. Then run the BDAS_yang124/src/Data_model.ipynb file.

