# Push-Images-to-Docker-Hub

HOW TO LOGIN TO DOCKER HUB FROM TERMINAl

PUSH THE CONTAINER IMAGES TO REGISTRY

docker login 
Copy  the link
https://login.docker.com/activate

docker images |grep tonymore

TO PUSH TO DOCKER HUB
docker push docker.io/tonymore/product-catalog:v1

SAME WAY PUSH ANOTHER IMAGE
docker push docker.io/tonymore/adservice:v1
docker push docker.io/tonymore/recommendationservice:v1

Refresh the docker hub you see the three images
