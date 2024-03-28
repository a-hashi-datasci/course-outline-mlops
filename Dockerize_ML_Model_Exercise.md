
# Sample Exercise: Preparing Your Model for Deployment with Docker

## Background
Deploying machine learning models efficiently into production is a crucial skill in the field of MLOps. Docker, a popular tool for creating lightweight, portable, and self-sufficient containers, plays a vital role in this task.

## Exercise: Dockerize Your Machine Learning Model

### Instructions
100 XP
- Specify the base image to use Python 3.8 in your Dockerfile.
- Copy your machine learning model file (`model.py`) and any dependencies file (`requirements.txt`) into the Docker container.
- Install the dependencies from `requirements.txt` inside the Docker container.
- Set the command to run your model file (`model.py`) when the Docker container starts.

### Dockerfile
```
FROM ______

# Set the working directory in the container
WORKDIR /app

# Copy the model and requirements files into the container
COPY ____________ /app/

# Install any dependencies
RUN pip install -r ____________

# Command to run on container start
CMD ["python", "__________"]
```
By completing this exercise, you'll gain hands-on experience with Dockerizing an application, which is a key aspect of MLOps practices.
