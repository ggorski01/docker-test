
This will attach a local folder to work folder within Jupyter notebook container. Modifications to files within folder will reflect it locally.

docker run -it --rm -p 8888:8888 -v "C:\Users\ggorski\OneDrive - Morryde International\Documents\Github\docker-test\zoomcamp:/home/jovyan/work" jupyter/base-notebook

This remove all running containers
docker rm $(docker ps -q) --force