# Base Image DL
$ docker pull datascientistus/ds-python-env

# run
docker run -v /Users/yukokanai/work/docker/my_python/my_datascientistist:/my_datascientistist -p 8888:8888 --name my-env datascientistus/ds-python-env