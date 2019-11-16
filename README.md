# k8s-google-cloud
Sample app for GKE

Just a bunch of samples to test GKE on Google Cloud. Using the repo to get access to YAML easily.
For just the pods and services run
kubectl create -f voting-app-pod-definition.yml
kubectl create -f voting-app-service.yml
kubectl create -f redis-pod.yml
kubectl create -f redis-service.yml
kubectl create -f postgres-pod.yml
kubectl create -f postgres-service.yml
kubectl create -f worker-app-pod.yml
kubectl create -f result-app-pod.yml
kubectl create -f result-app-service.yml

Test.
Turn it to Deployment so there is a replica set for auto scaling.

From the deployment folder simply run kubectl create -f . for
everything to be created.
