## About

This repository contains assigments completed for the Udacity Deep Learning Machine Learning Class.  All assignments are done using TensorFlow on Docker on Windows. I'll eventually add the steps to do this as it was quite detailed.

## Docker tips 

To have docker save the files after you close and restart the machine, this was the best solution I found:

Get your docker machine ip

``` docker-machine ip ```


The first time you run/pull the docker file from the google repo give it a name

``` docker run -p 8888:8888 -d --name tfudacity b.gcr.io/tensorflow-udacity/assignments ```


You can then start this docker by name:

``` docker start tfudacity ```

It will look like it's not doing anything but if you visit


``` <docker_ip>:8888 ```


in your browser the jupyter tree will be there with your files. 


To stop the docker: 

``` docker stop tfudacity ```

