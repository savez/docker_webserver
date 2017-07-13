# docker_webserver
An custom Docker compose for implementation of webserver LAMP for **MAC**

## dependences
- docker sync (http://docker-sync.io/)
- docker for mac (https://store.docker.com/editions/community/docker-ce-desktop-mac)

## Step for installation
- Install dependencies of docker sync
```
brew install unison
brew install eugenmayer/dockersync/unox
brew install rsync
```
- Customization docker-sync.yml and docker-compose.yml
- Copy files into root of the your project

## Execution
Go to root of the your project and run
```
docker-sync-stack start
```

## Customization of the files
### Docker-compose.yml
- at line 5, 20, 30: replace *"MYCONTAINER"* with the your project's name
- at line 8, 23, 33, 36: replace *"CUSTOM_NAME_CONTAINER_UNISON"*

### Docker-sync.yml
- at line 22: replace *"CUSTOM_NAME_CONTAINER_UNISON"*
