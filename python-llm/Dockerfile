# Use the official Python 3.11 image from the Docker Hub
FROM python:3.11-bullseye

# Install dependencies
RUN apt-get update && apt-get install -y curl zsh

# Install Poetry
RUN pip install --upgrade pip && pip install poetry

# Set the default command to use the virtual environment
CMD ["python"]