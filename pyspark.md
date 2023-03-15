# Install PySpark
Tutorial
- Go to https://spark.apache.org/downloads.html . There are several options to install pyspark

## Using PyPi
- Make sure you have installed python on the computer
- Open terminal and run this command
```python
pip install pyspark
```
- The process will run immediately
- If the process already done, you can check using python script
```python
import pyspark
print(pyspark.__version__)
```
- The version will show up in the terminal, it means the installing process is succeed
![Screenshot 2023-03-15 173117](https://user-images.githubusercontent.com/107783827/225282853-0fb3c1a7-d11e-4249-a270-ff73690a156e.png)


## Using Docker Compose
- I recommend to install the docker desktop first
- Go to https://hub.docker.com/r/apache/spark-py/tags and copy the code. Here's the code for the latest version
```powershell
docker pull apache/spark-py:latest
```
- You can freely choose the version you want
- Run the command in the terminal
- If it's already done, you can open the docker desktop to make sure pyspark images is installed
- Here is the preview. If spark is show up, the installing process is succeed
![Screenshot (318)](https://user-images.githubusercontent.com/107783827/225282334-ef70591d-6410-4608-b758-d33e776ed119.png)
