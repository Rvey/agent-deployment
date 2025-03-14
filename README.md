# agent-deployment

## Building the Docker Image

To build the Docker image, run the following command in the root directory of the project:

```sh
docker build -t your-dockerhub-username/agent-deployment:latest .
```

## Pushing the Docker Image to Docker Hub
### After building the Docker image, you can push it to Docker Hub with the following commands:

1. Log in to Docker Hub:

```sh
docker login
```

## Push the Docker image to Docker Hub:

```sh
docker push your-dockerhub-username/agent-deployment:latest
```

## Activating Virtual Environment and Installing Requirements
To set up the Python virtual environment and install the required packages, follow these steps:

1. Create a virtual environment:

```sh
python -m venv venv
```

2. Activate the virtual environment:

On Windows:

```sh
venv\Scripts\activate
```

On macOS/Linux:

```sh
source venv/bin/activate
```

3. Install the required packages:

```sh
pip install -r requirements.txt
```