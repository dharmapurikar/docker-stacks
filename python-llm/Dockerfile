# Use the official Python 3.11 image from the Docker Hub
FROM python:3.11-bullseye

# Install dependencies
RUN apt-get update && apt-get install -y curl zsh

# Install Poetry
RUN pip install --upgrade pip && pip install poetry

# Set the working directory
WORKDIR /app

# # Copy the project files
# COPY . .

# # Install project dependencies
# RUN poetry install

# Set the entrypoint to use the virtual environment
ENTRYPOINT ["/bin/zsh"]