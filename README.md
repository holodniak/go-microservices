# Go microservices

## Running the project

### Requirements

 - Docker
 - Go
 - Make

Open all folders within a workspace, inside the project folder run the command

    make up_buid
  
After running this command, the service containers will be uploaded to Docker.
With all containers running, run the second command.

    make start

With this, just access the url http://localhost:80/ which will be running the fronend communicating with the backend!! :) 
