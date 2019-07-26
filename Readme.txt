c:..\myapp
docker build -t myapp .
docker run -it --rm myapp


Once run
open other cmd
docker exec <containerID> ipconfig
get IP4 value 
paset in browser