# Wine Challenge Docker Image

This Docker image provides a pre-configured environment for the Wine Challenge project. Follow the steps below to pull and run the image on a machine with Docker installed.

## Pull the Docker Image

To pull the Docker image from Docker Hub, use the following command:

```bash
docker pull saydeaguilar/wine_challenge

```
## Run the Docker Image
Once the image is pulled, run the Docker container with the following command:

```bash
docker run -p 8888:8888 saydeaguilar/wine_challenge
```
After running the image, the terminal will display a link to access the server, providing access to the Jupyter Notebook.

Important:

## The host port is set to 8888.
Feel free to access the provided link and explore the Jupyter Notebook environment.

