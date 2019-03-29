# Chapter 2 - Basics of Machine Learning
This case study explores the basics of machine learning. Two parts exist to this case study, a theory portion and a classification task for the [Higgs Bosson Challenge](http://opendata.cern.ch/collection/ATLAS-Higgs-Challenge-2014). The case studies are presented as jupyter notebooks inside Docker containers. 

## Requirements
* [Docker](https://docs.docker.com/install/) 

## Running the Docker Image
The docker images for this case study are located on dockerhub. Running the commands below will automatically download and start a jupyter notebook.

Run the Docker image:
```
docker run -p 8888:8888 jimmywhitaker/chapter_2:latest
```

You will see an output similar to this: 
```
[C 20:51:04.306 NotebookApp]

    To access the notebook, open this file in a browser:
        file:///home/user/.local/share/jupyter/runtime/nbserver-1-open.html
    Or copy and paste one of these URLs:
        http://(8e6d9075ce39 or 127.0.0.1):8888/?token=754744367af1168a4e4e286200cc026234f070d8313ba67b
```
Copy the token value (e.g. `754744367af1168a4e4e286200cc026234f070d8313ba67b`) and go to the webpage [http://localhost:8888](http://localhost:8888).

Paste the token value when prompted, allowing the jupyter session to be accessed.

## Building the Docker image
If you want to build the Docker image from scratch, use the following command. 
```
docker build -t jimmywhitaker/chapter_2:latest .
```