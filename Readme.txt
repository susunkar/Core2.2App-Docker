c:..\myapp
docker build -t myapp .
docker run -it --rm myapp


Once run
open other cmd
docker exec <containerID> ipconfig
get IP4 value 
paset in browser

ref url
https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/docker/building-net-docker-images?view=aspnetcore-2.2
https://www.c-sharpcorner.com/article/build-and-deploy-an-asp-net-core-web-application-as-docker-container-using-micr/