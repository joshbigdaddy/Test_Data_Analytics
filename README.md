# Visualization project

This project is done with a docker container that allows to run pyspark jobs with a Jupyter Labs installed:

> docker pull jupyter/pyspark-notebook

For running the container:

> docker run -it --rm -p 8888:8888 jupyter/pyspark-notebook 

The files added in the repository should be in the jupyter to be run later as a document. As the task was made with some analytics over a csv file I found the best match with a more "Data Analysis" tool like this, which is a very good option to run litle pieces of code and starting to see some results.

It also fits the purpose of this test, as it allows me to explain better the ways I achieved the attributes asked. I also used pyspark with spark sql because it also shows my way of performing queries, which is something also interesting for this test.
