# podcast_Pipeline
In this project, we'll create a data pipeline using Airflow. The pipeline will download podcast episodes and automatically transcribe them using speech recognition. We'll store our results in a SQLite database that we can easily query.

Airflow can help us with a few things:

We can schedule the project to run daily
Each task can run independently, and we get error logs
We can easily parallelize tasks and run in the cloud if we want to
We can extend this project more easily (add speech recognition, summaries, etc) using Airflow
By the end of this project, you'll have a good understanding of how to use Airflow, along with a practical project that you can continue to build on.

Overview of Steps:

Download the podcast metadata xml and parse
Create a PostgresSQL database to hold podcast metadata
Download the podcast audio files using requests
Transcribe the audio files using vosk

Tech Stack:
Airflow 2.3+
Python 3.8+
Python packages(pandas,sqlite3,xmltodict,requests,vosk,pydub)

