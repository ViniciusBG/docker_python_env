# docker_python_env

Since I've started dealing with Docker, I have never used python virtual or conda envs anymore. I've really liked it.

This repo brings a base image for python development with a Dockerfile and a docker-compose.yaml to create an isolated python env. 

Besides that, there's a makefile on the repo (which runs the "docker-compose up --build" command.

If you want to use it, just clone the repo, change the requirements.txt with the packages you want, and run:

```make start```

This will build the container for you.

**Note:** This also starts a jupyter notebook. If you want to access it, go to your browser and navigate to ```http://localhost:8888/```
