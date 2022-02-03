# Using the latest openjdk version
FROM openjdk

# Creates a new app directory for application files in the docker image
RUN mkdir /app 

# copying the files from the host machine (current directory) to the image  
COPY . /app

# setting the directory for executing future commands
WORKDIR /app

# Command to run the application
CMD java Main.java


