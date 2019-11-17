# Experiment with k8s to do some works
In this repo, we experiment with Kubernetes (hereafter k8s) to deploy and run some apps. The intention is to cover the basic of Kubernetes and getting the hang of things, including:
1. dockerise app
1. deploy apps to kubernetes clusters
1. provisioning and scheduling on kubernetes
1. understanding the use of jobs, cronjobs, deployment, etc.
1. defining jobs dependency using e.g. argo.
1. have fun.

Overall, the motivation is Infrastructure as Code i.e. one can bring down a whole system and bringg it up again using simple script.

## Prequisite

### Tools
What we need?

1. Set up GCP projects
1. Download Google Cloud SDK: 
```
(New-Object Net.WebClient).DownloadFile("https://dl.google.com/dl/cloudsdk/channels/rapid/GoogleCloudSDKInstaller.exe", "$env:Temp\GoogleCloudSDKInstaller.exe")

& $env:Temp\GoogleCloudSDKInstaller.exe
```
1. Download Docker (see https://docs.docker.com/ee/) 
1. Get k8s CLI (one can download `kubectl` from gcloud SDK by followingg the command-line)

### Setting up a k8s on GCP
Note: Better to keep a file to save all the source code 
(Ti Beo fill in)
### Create  a Cluster

### Create a Node pool with preemtible node
1. explain what is preemtible noddes (to save £_£)
1. enable auto-scaling, explain what is auto-scaling

### Connect to the k8s 


### Deploying a toy example
1. Create an app in your favourite lang
1. dockerise
1. publish to gcp registry
1. run the app on gke
