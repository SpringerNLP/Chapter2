# Chapter 2 - Basics of Machine Learning
This case study explores the basics of machine learning. Two parts exist to this case study, a theory portion and a classification task for the [Higgs Bosson Challenge](http://opendata.cern.ch/collection/ATLAS-Higgs-Challenge-2014). The case studies are presented as jupyter notebooks inside Docker containers. 

## Requirements
* [Docker](https://docs.docker.com/install/) 

## Running the Docker Image
The docker images for this case study are located on dockerhub. Running the commands below will automatically download and start a jupyter notebook.

Run the Docker image:
```
docker run -p 8888:8888 --rm springernlp/chapter_2:latest
```


## Building the Docker image
If you want to build the Docker image from scratch, use the following command. 
```
docker build -t chapter_2:latest .
```
