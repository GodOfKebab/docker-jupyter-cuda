# Docker Project Template with Jupyter Notebook, PyTorch and CUDA

You might need to install some dependencies to get cuda behind docker.


Run below to spin up the docker container with jupyter notebook and cuda support.

```
docker compose up --build jupyter
```

You can specify the required python packages in the `docker/jupyter/requirements.txt` to embed them in the docker image.

