# Intro to Chrome Exploitation
## Docker Environment
To follow along with the class, you will need to create a container from the prebuilt docker image.
1. Install Docker:
  macOS: `brew cask install docker && brew install docker`
  Ubuntu: `sudo apt update && sudo apt install docker-ce`
  Windows: https://docs.docker.com/docker-for-windows/install/
1. Login to Docker with the creds provided in class.
1. Build: ./build -- This will pull the base image 'owasp2019chrome/class-env' from docker hub.
  - Add any customizations to the Dockerfile

### Managemnt
- `start` - Start the built image
- `stop`  - Stop the running image
- `connect [COMMAND]` - Connect to the running container. By default, if no second argument is provided, a new `tmux` session is created.

## Slides
Will be uploaded before class.
