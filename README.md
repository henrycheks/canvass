# canvass
# Dockerize application
-Create image from the Dockerfile (use command below)
    - docker build -t webapi .
-Push this image to the docker registry (if you choose to build an image from Dockerfile) with command bellow
    - docker push webapi
# Kubernetes Cluster
-Create a Kubernetes Deployment file using docker image you created
-Create Service object of type NodePort or LoadBalancer
