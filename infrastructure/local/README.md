# Model Texttractor
This service will let users extract text from images and search the results, this is the infrastructure meant to bring the code to life in the form of a functioning service composed of microservice... this consists of bothe  the lcoal excecution capability and the ability to run on a kubernetes cluster.

http://localhost:8086/?pgsql=db&username=postgres&db=postgres&ns=public
## Tasks

### Setup Docker Environment
You'll need to install docker https://docs.docker.com/install/. Open a new terminal within the project directory and run:

1. Build the images: `docker-compose -f docker-compose-build.yaml build --parallel`
2. Push the images: `docker-compose -f docker-compose-build.yaml push`
3. Run the container: `docker-compose up`

#