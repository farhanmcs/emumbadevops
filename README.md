# minikube-devops

This is the base Version of assignment and work on it is still in progress.
For now the basic Deployments, Services and ConfigMaps are created.
Also for this version Minikube is needed to be installed on the System.
I have created docker images from preovided code repo and pushed them into my personal Docker Hub account and the Deployment files in this repo are fetching container images from there.

Please clone the repo and "cd" into it.
Once in the directory you can see a set of Yaml files. Please run the following command in this directotory.

"kubectl create -f ."