# Build and push a Docker image
Build a Docker image and make it available on a publicly-accessible
registry.
1. `docker build -t <docker account>/k8s-test .`
2. `docker push <docker account>/k8s-test`

# Deploy to GKE
I am deploying my app to a GKE cluster. There are elided steps to connect `kubectl` running
on a remote machine to the cluster that are described
[here](https://cloud.google.com/kubernetes-engine/docs/how-to/cluster-access-for-kubectl).
`kubectl apply -f k8s`
