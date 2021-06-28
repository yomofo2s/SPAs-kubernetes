## Kubernetes SPAs##

The Dockerfile is created for rendertron application and build. The kubernetes resources I created as yaml files is located inside deploy-package\rendertron-workflow.

The image is uploaded on the Docker hub [yomofo2s/rendertron:latest](https://hub.docker.com/r/yomofo2s/rendertron)

A docker minikube cluster was setup as a local deployment

A nginx-ingress loadbalancer was setup to alllow access from outside.

A [Celeb-website](https://hub.docker.com/r/yomofo2s/celeb-website) was also built as a test url, the image is on DockerHub 

Credit
https://github.com/GoogleChrome/rendertron