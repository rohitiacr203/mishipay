# mishipay jenkins docker setup
This repo conatians all the files which is required to host a static html page via docker and jenkins

Below are the commands which has been used manually to build docker container
docker build -t mishipay .
docker run -itd -p 80:80 mishipay /bin/bash
goto - http://localhost:8080
