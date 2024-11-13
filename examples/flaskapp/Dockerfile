# Use the official Python image from the Docker Hub
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install the dependencies (Flask in this case)
RUN pip install flask

# Expose port 9090 to the outside world
EXPOSE 9090

# Run the application
CMD ["python", "app.py"]

