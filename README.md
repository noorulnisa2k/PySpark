# PySpark Installation

#### Create WSL venv
(if you are on Windows, use WSL editor on PowerShell).

#### install library
```bash
  pip install pyspark==3.2.3
```
```bash
  pip install spark==3.2.3
```
#### Run the wget command to download Apache Spark
```bash
  wget https://downloads.apache.org/spark/spark-3.2.3/spark-3.2.3-bin-hadoop3.2.tgz
```

#### Untar the archive file
```bash
  tar -xzf spark-3.2.3-bin-hadoop3.2.tgz
```

#### Rename archive file to spark
```bash
  mv spark-3.2.3-bin-hadoop3.2 spark
```

#### Add Apache Spark environment variables to .bashrc or .profile file

open file in vi editor
```bash
  vi ~/.bashrc
```

Add below variables
```bash
  lyftrondata/spark
```
```bash
  export PATH=$PATH:$SPARK_HOME/bin
```
```bash
  Press:
    -Esc:
    -wq (write and quit)
```
#### Load environment variables
```bash
  source ~/.bashrc
```

#### Test Spark installation
```bash
  spark-submit --version
```


## Reference Link

 - [Spark installation documentation](https://sparkbyexamples.com/spark/spark-installation-on-linux-ubuntu/)
 - [Spark download](https://spark.apache.org/downloads.html)
 
