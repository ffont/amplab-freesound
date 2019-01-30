# amplab-freesound
Materials for the AMPLAB Freesound assignment


## Running the notebook

### Install docker

It is recommended to read the documentation about [Docker](https://docs.docker.com/)
and [docker-compose](https://docs.docker.com/compose/).

#### Windows
https://docs.docker.com/docker-for-windows/install/

#### Mac
https://docs.docker.com/docker-for-mac/install/

#### Ubuntu
https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/#install-docker-ce

### Install docker-compose
Follow [instructions](https://docs.docker.com/compose/install/).

## Run the notebook

First run the following command:

    docker-compose up

Then access `http://localhost:8888` on your browser and when asked for a password use **mir**.

Form the interface that you'll see in your browser you can open the three included Jupyter Notebooks and follow them in order:

 1) Create source sound collection
 2) Analyze source collection and target file
 3) Reconstruct target file with source collection frames
 
