* Pull a Python image, e.g. `docker pull python:3.13.2-slim-bookworm`
* Pull a Jupyter Pyspark image, e.g. `docker pull quay.io/jupyter/pyspark-notebook:spark-3.5.3`

#### Docker and compose.yml

* Review compose.yml. Maybe we can improve it and add some functionality. Right now the one from practise sessions is used
* `docker compose -f project_1/compose.yml up -d`

* Move or copy the `example.ipynb` file and the entire `data` folder to the `mnt` folder
  * e.g. `cp -r project_1/data/ project_1/example.ipynb ˇproject_1/mnt/`
* Review Jupyter UI (localhost:8888), run the example notebook
* Review Spark UI (localhost:4040)