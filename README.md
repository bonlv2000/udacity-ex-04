[![binlv2011](https://circleci.com/gh/bonlv2000/udacity-ex-04.svg?style=svg)](https://app.circleci.com/pipelines/github/bonlv2000/udacity-ex-04)

## Project Overview
  - Deploy python with docker and kubectl.
  - 
## Require
   -Python 3.7

## Start here

### Step 0
- Cloning a Repository.

### Step 1: Install dependencies
- To prepare the environment, execute "make setup". This action will establish a virtual environment named .devops in your home directory.
- To satisfy the project's dependencies, execute "make install".
- (Optional) Perform application linting (using hadolint).

### Step 2: Run the Docker container
- Run the application on docker by command `./run_docker.sh`

### Step 3: Upload to Docker Hub
- In the `./upload_docker.sh` file, modify the dockerpath (line 9) to include your desired path and update the Docker username to your personal username, or keep it as 'binlv2011/microproject:v1.0.0' if you intend to use the public image.
- To upload to docker hub service, run `./upload_docker.sh`

### Step 4: Kubernetes deployment
- To deploy to kubernetes, run `./run_kubernetes.sh`
