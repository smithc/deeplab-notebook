# Quickstart

1. Clone the DeepLab repo (Tensorflow/models)

    ```git clone https://github.com/tensorflow/models.git```

2. From the root of the repo, navigate to the following folder: ./research/deeplab

3. Run the docker container (built by the Dockerfile):

    ```docker run -it --rm -p 8888:8888 -v ${pwd}:/home/jovyan/work jupyter/deeplab```

    This will run jupyter on port 8888, and will mount the current host directory under the 'work' directory in the container.

4. Copy the URL out of the container once the jupyter server is up and running. It should include a token parameter that will allow you to login to your local instance.