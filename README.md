# Minikube-WebApp-MongoDB
This repository is for my first kubernetes project, in which i eploying webApp and MongoDB on miniKube single Node Cluster

ConfigMap and secret must be created first.Because Deployment needs them

after that MongoDb deployment and service should be created beacuse our webapp need the MongoDb

and in the Last Create the deployment and External-service for webApp so that is can be accessible through web browser

kubectl apply -f <FileName.yaml>
