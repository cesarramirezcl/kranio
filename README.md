## Quick Start

This command pulls the `jupyter/pyspark-notebook` from Docker Hub if it is not already present on the local host.
It then starts a container running a Jupyter Server and exposes the container's internal port `8888` to port `8888` of the host machine:

```bash
docker run --publish 8888:8888 --volume [your-path]:/home/jovyan/work jupyter/pyspark-notebook
```

Clone this repo at [your-path] to execute the test.

