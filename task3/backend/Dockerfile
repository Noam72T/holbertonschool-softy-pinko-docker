# Use the latest version of ubuntu as the base image
FROM ubuntu:latest

# Update the package lists for need updates
RUN apt-get update

# Upgrade all packages
RUN apt-get upgrade -y

# Install python3 and pip3
RUN apt-get install -y python3 python3-pip

# Install Flask
RUN pip3 install Flask

# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Make port 5000 available 
EXPOSE 5252

# Run app.py when the container launches
CMD ["python3", "app.py"]