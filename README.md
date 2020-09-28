# dockerfiles

usage:

without using GPU 

docker run --rm -it -v dir1:dir2 docker/name


using GPU 

docker run --rm -it --gpus all -v dir1:dir2 docker/name
