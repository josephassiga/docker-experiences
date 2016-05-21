DOKER IN DEVELOPEMENT
-----------------------
VM :
- Emulate a foreign environment

Containers(Docker):
- Make Application portable and self-contained.
- Configure an existing Terminal : docker-machine start default & eval $(docker-machine env default)
- To know the ip address of the machine(VM) that run Docker : docker-machine ip default
- login to the VM directly : docker-machine ssh default
- Dockerfile : is text file that contains a set of steps used to create an image.
- Registry : is a service responsible for hosting images, the default registry is Docker Hub
- Repository : a collection of images
- Tag : it is a version of a repository, alphanumeric
- Give a hostname : docker run -h CONTAINER -i -t debian /bin/bash
- Automating with Composer : docker-compose
