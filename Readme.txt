c:..\myapp
docker build -t myapp .
docker run -it --name myapp

Once run
open other cmd
docker exec <containerID> ipconfig
get IP4 value 
paset in browser