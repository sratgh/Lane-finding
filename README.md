# Installation / Setup

1)
Install Docker environment
For mac: https://docs.docker.com/v17.12/docker-for-mac/install/

2)
Then pull the udacity docker environment with 

*docker pull udacity/carnd-term1-starter-kit*

3)
Run the jupyter notebook in a docker environment with the following command:

*docker run -it --rm --entrypoint "/run.sh" -p 8888:8888 -v `pwd`:/src udacity/carnd-term1-starter-kit*

